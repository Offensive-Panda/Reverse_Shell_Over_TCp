# Reverse_Shell_Over_TCp
I have created a reverse connection client from scratch in the C# programming language and execute arbitrary commands to perform C&amp;C on the target system.  To connect to the host with port, you need to pass the IP address in the first parameter and integer port number as the second argument.


I used netcat for listening which i started on Kali Linux. After executing client application you will get the reverse shell over tcp using sockets. This is fully undetected by AV's.

USAGE:
1) Extract the given file using winrar
2) Open solution file in visual studio to compile
3) Before executing client application start listening using netcat e.g, (netcat -l -p )
4) Execute file and boooooo you will get reverse shell.





@CyberSecurityEngineer
@Mal-Dev
@Offensive_Panda
