# SRE Interview Question 1

In this directory there is a file `data.csv` which contains the information for users logging into our website. 

Our security team needs to get the info of the users from the cidr range `207.0.0.0/8`.

Write an `output.txt` file that contains a list of emails coming from this range.

#### Disclaimer
All data is fake and generated with https://www.mockaroo.com/

## Available tools

```
$ sed --version
sed (GNU sed) 4.4

$ node -v
v14.17.0

$ python --version
Python 3.8.10

$ ruby -v
ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-linux-gnu]

$ java --version
openjdk 11.0.11 2021-04-20
OpenJDK Runtime Environment (build 11.0.11+9-Ubuntu-0ubuntu2.18.04)
OpenJDK 64-Bit Server VM (build 11.0.11+9-Ubuntu-0ubuntu2.18.04, mixed mode, sharing)

$ bash --version
GNU bash, version 4.4.20(1)-release (x86_64-pc-linux-gnu)

$ go version
go1.14.7 linux/amd64

$ grep --version
grep (GNU grep) 3.1

$ awk -W version
mawk 1.3.3 Nov 1996, Copyright (C) Michael D. Brennan
```

And others not listed here. Use the console to see if your favorite language is installed.

## Discussion

Does your script handle cidr ranges other than the given question?

How is the script handling duplicate users or users without emails?