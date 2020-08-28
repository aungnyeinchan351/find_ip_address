# English

## Finding IP address using python

Hello guys, I will show you how to get IP address with python using socket module. Any phone, computers, tablets have their own ip address. Now, we will get that ip using socket module.

There are (4) steps for getting IP address of devices.
```
1. Importing socket module
2. Getting host name of device
3. Finding IP address of host
4. Printing IP
```
Now, let work with these steps.

### Importing socket module

We will import **socket** module using the **import** keyword.
```
#importing socket
import socket
```

### Getting host name 

Get the host name of device using gethostname() function from socket
```
#get host name
host = socket.gethostname()
```

### Finding IP address

Find IP address of host using gethostbyname()function. This function need host name as argument.
```
#finding ip address
ip = socket.gethostbyname(host)
```
### Printing IP address

This is final step 
Print ip address that is stored in a variable named **ip**.
```
#printing IP
print("IP address is ",ip)
```
The whole program is 
```
#Import socket module
import socket
#get host name
host = socket.gethostname()
#find ip address
ip = socket.gethostname(host)
#Print IP address
print("IP address is ",ip)
```
### Output

The output of this program is 
```
IP address is  127.0.0.1
```
Follow me on[GitHub](https://GitHub.com/aungnyeinchan351)

Follow me on [Facebook](https://facebook.com/zinyaw3063)


