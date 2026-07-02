# Java 소켓 프로그래밍 (TCP)

- ServerSocket.accept()는 blocking — 클라이언트 접속 전까지 대기
- BufferedReader/PrintWriter로 소켓 스트림을 문자열 단위로 주고받음
- 멀티스레드(Runnable + Thread)로 여러 클라이언트 동시 처리 구현
- SSH도 동일한 소켓 구조 위에 원격 셸 실행 기능을 얹은 것이라는 점을 이해
