dd if=/dev/zero of=/tmp/file.txt count=1024 bs=1048576

install jdk
wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" https://download.oracle.com/java/17/latest/jdk-17_linux-x64_bin.rpm
sudo rpm -Uvh jdk-17_linux-x64_bin.rpm


Monitoring
iotop -o
watch iostat -hxym



gradle shadowjar