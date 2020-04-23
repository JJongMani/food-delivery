각 시스템의 소스코드는 아래 url에 있습니다. 

https://github.com/JJongMani/ReservationSystem.git
https://github.com/JJongMani/LibrarySystem.git
https://github.com/JJongMani/PaymentSystem.git
https://github.com/JJongMani/gateway.git

명령어 1 (도서관의 자리수는 0으로 세팅) : 

http POST 52.231.117.52:8080/librarySystems totalCount=0
.
.
명령어 2 (studentId가 1001이 학생이 자리 예약) : 

http POST 52.231.117.52:8080/reservationSystems studentId=1001
.
.
명령어 3 (도서관의 totalCount가 1 증가했는지 확인) : 

http 52.231.117.52:8080/librarySystems/1
.
.
