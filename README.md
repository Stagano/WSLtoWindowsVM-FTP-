# WSLtoWindowsVM-FTP-


1. WSL의 IP 확인
    Host> hostname -I

2. 해당 IP로 바인딩
    Host> python3 -m http.server 8000 --bind "(1) get Ip"
    guest> http://"get ip":8000 으로 Web 접속

3. 0.0.0.0으로 바인딩
    python3 -m http.server 8000 --bind 0.0.0.0

