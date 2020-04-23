각 시스템의 소스코드는 아래 url에 있습니다. 

https://github.com/JJongMani/ReservationSystem.git
https://github.com/JJongMani/LibrarySystem.git
https://github.com/JJongMani/PaymentSystem.git
https://github.com/JJongMani/gateway.git

### 명령어 1 (도서관의 예약되어있는 자리수를 임의로 세팅) : 

http POST 52.231.117.52:8080/librarySystems totalCount=3
![image](https://user-images.githubusercontent.com/16271728/80061240-b1d8ed00-856b-11ea-95f9-8d225edf9219.png)

### 명령어 2 (studentId가 1001이 학생이 자리 예약) : 

http POST 52.231.117.52:8080/reservationSystems studentId=1001
![image](https://user-images.githubusercontent.com/16271728/80061324-eea4e400-856b-11ea-902c-e99a5335f340.png)

### 명령어 3 (도서관의 totalCount가 1 증가했는지 확인) : 

http 52.231.117.52:8080/librarySystems/1
![image](https://user-images.githubusercontent.com/16271728/80061655-e26d5680-856c-11ea-8ca4-6714c4d1a0d2.png)

