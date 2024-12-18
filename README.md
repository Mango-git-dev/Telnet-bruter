# Telnet Bruter

### Installation

- Centos / RHEL :
```
sudo yum update -y
sudo yum install git -y
```
- Ubuntu / Debian
```
sudo apt update
sudo apt install git -y
```

- Importan

```sh
git clone https://github.com/Mango-git-dev/telnet-bruter.git
cd ./telnet-bruter/
gcc ./*.c -o telnet-bruter -pthread -std=c99 -fcommon
sh bruter.sh
```
- Note : 
```
Zmap hoạt động như hình thức dưới đây
zmap -p 23 | ./telnet-bruter <threads>
->> nên chỉnh threads ở trong file bruter.sh để có thể scan phù hợp với sever
```
![image](https://user-images.githubusercontent.com/69421356/192002873-c8f5fd0d-9866-43dc-a18a-59b9ddf051f3.png)

