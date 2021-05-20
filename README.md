# Tsung Stress Test 

Most powerful stress test tool I've worked on. This architecture is made of erlang and your configuration is simple because write in xml.

Pre-requirements
 - Erlang
 - [Tsung](https://github.com/processone/tsung)

### Don't forget it:

If you wanna test in distributed, exchanged the keys. More important is the first machine as master and the others as replicas/secondary/etc. Only the master need the machines keys.

To install tsung, download the tsung repo and execute:
```
./configure
make
make install
```

The final step you need is write in your /etc/hosts with localhost and the names of your replicas/secondary machines.