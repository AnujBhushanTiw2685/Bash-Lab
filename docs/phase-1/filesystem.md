### Linux Filesystem
## Structure of linux filesystem:

```
/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin
├── srv
├── sys
├── tmp
├── usr
└── var

```


# / 
this depicts root of the filesystem.

# /root
this is the home directory of the root user.

# /etc
generally contains system and application configuration files.

# /var
contains data that changes frequently.

# /tmp
temporary files (applications can use it for temporary data).

# /usr
contains a large portion of user-space programs, libraries and related files.

e.g. :- 
```
/usr/bin
/usr/sbin
/usr/lib

```
# /bin
traditionally contains essential commands binaries

eg: - 

```
ls
cp
mv
cat

```

# /dev
linux represents many devices as files under `/dev `
eg: -
```
/dev/sda
/dev/null

```

# /proc
virtual filesystem containing inoformation about processes and the kernel
eg :- 
```
/proc/cpuinfo
/proc/meminfo

```
meaningful when you learn about commands like `ps` , `top` , `free`


# /sys
another virtual filesystem providing information and interfaces related to devices and the kernel 



--- will keep updating further --- 

