# nixbot
Lightweight (POC) botnet coded in C++

Server:

`g++ main.cpp "../includes/file_send.cpp" -o main -lpthread --std=c++0x`

Client:

`g++ main.cpp includes/execute.cpp includes/http_bruteforce.cpp includes/ftp_bruteforce.cpp includes/ssh_bruteforce.cpp ../includes/file_send.cpp -o main -lpthread -lcurl -lssh2 --std=c++0x`

## Credits:

http://github.com/dotcppfile

http://github.com/aces421
