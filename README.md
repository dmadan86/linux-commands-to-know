## Linux commands 
Programmers has to know these commands to make life easy 


#### **lsof** (Identify Open Files) - [info](https://linux.die.net/man/8/lsof)

###### To know which port is opened by an application
```sh
lsof -i :<port_no>
```

###### List processes which opened a specific file
```sh
lsof /var/log/syslog
```

###### List opened files under a directory
```sh
lsof +D /var/log/
```

