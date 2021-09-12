# Code_Injector
this program will let you to inject any java script code to website ont he target machine connected in same network.
how to use 
pip install netfilterqueue
servive apache2 start 
edit the code by changing the injection code on line number 23.
iptables -I FORWARD -j NFQUEUE --queue-num 0
now in other terminal 
python code_injector.py
after you have completed your task 
iptables --flush
