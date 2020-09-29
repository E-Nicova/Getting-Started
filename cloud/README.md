[go back](../README.md)

   #### Create an ssh key pair to be used with all the environments.
  
   #### Create a free tier [GCP](https://cloud.google.com/) account:
    Requires a card but prepaid mastercard/visa can’t be used
    
    1. Create a ubuntu 16.04 vm

    2. ssh into the vm created at step a. and run the following: ip a

    3. Paste the output here: 
    1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
    2: ens4: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1460 qdisc mq state UP group default qlen 1000
    link/ether 42:01:0a:a8:00:02 brd ff:ff:ff:ff:ff:ff
    inet 10.168.0.2/32 brd 10.168.0.2 scope global ens4
       valid_lft forever preferred_lft forever
    inet6 fe80::4001:aff:fea8:2/64 scope link 
       valid_lft forever preferred_lft forever

    4. ssh into the vm create at step a. and run the following: ifconfig

    5. Paste the output here:
    ens4      Link encap:Ethernet  HWaddr 42:01:0a:a8:00:02  
          inet addr:10.168.0.2  Bcast:10.168.0.2  Mask:255.255.255.255
          inet6 addr: fe80::4001:aff:fea8:2/64 Scope:Link
          UP BROADCAST RUNNING MULTICAST  MTU:1460  Metric:1
          RX packets:328 errors:0 dropped:0 overruns:0 frame:0
          TX packets:290 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000 
          RX bytes:781495 (781.4 KB)  TX bytes:36294 (36.2 KB)
      lo        Link encap:Local Loopback  
          inet addr:127.0.0.1  Mask:255.0.0.0
          inet6 addr: ::1/128 Scope:Host
          UP LOOPBACK RUNNING  MTU:65536  Metric:1
          RX packets:0 errors:0 dropped:0 overruns:0 frame:0
          TX packets:0 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000 
          RX bytes:0 (0.0 B)  TX bytes:0 (0.0 B)

    

    6. Share sample test output results from below.
    
   #### Create a free tier [AWS](https://aws.amazon.com/free) account:
    Requires a card but prepaid mastercard/visa can be used

    1. Create a ubuntu 16.04 vm

    2. ssh into the vm create at step a. and run the following: ip a

    3. Paste the output here:

    4. ssh into the vm create at step a. and run the following: ifconfig

    5. Paste the output here:
    
   #### Create a free [Azure](https://azure.microsoft.com/en-us/free/) account:
    Requires a card but prepaid mastercard/visa can’t be used
    
    1. Create a ubuntu 16.04 vm

    2. ssh into the vm create at step a. and run the following: ip a

    3. Paste the output here:

    4. ssh into the vm create at step a. and run the following: ifconfig

    5. Paste the output here:

   #### Create a free tier [Oracle Cloud](https://www.oracle.com/cloud/free) account:
    Requires a card but prepaid mastercard/visa can’t be used

    1. Create a ubuntu 16.04 vm

    2. ssh into the vm create at step a. and run the following: ip a

    3. Paste the output here:

    4. ssh into the vm create at step a. and run the following: ifconfig

    5. Paste the output here:
