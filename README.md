# Telnet Bruter

### Installation
```sh
user@domain:~# git clone https://github.com/Mango-git-dev/telnet-bruter.git
user@domain:~# cd ./telnet-bruter/
user@domain:~# gcc ./*.c -o telnet-bruter -pthread -std=c99 -fcommon
user@domain:~# zmap -p 23 | ./telnet-bruter <threads>
```

![image](https://user-images.githubusercontent.com/69421356/192002873-c8f5fd0d-9866-43dc-a18a-59b9ddf051f3.png)

