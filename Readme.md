# Gossip Membership Protocol

This repository contains first computer programming assignment of [Coursera's Cloud Computing Course](https://www.coursera.org/learn/cloud-computing/) which is implementation of a membership protocol. I implemented gossip membership protocol which discussed in the course. 

__For documentation of code and 3 layers design refer to `mp1_specifications.pdf`__


## How to run
To run this code you should compile it at first and then run the program with a `.conf` file which can be fined in testcases folder.
```
make
./Aplication ./testcases/singlefailure.conf
```

You can also run all testcases and get theri completeness and accurcy using `run.sh`.
```
chmod +x run.sh
./run.sh
```
