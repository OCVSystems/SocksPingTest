Just playing fair:
I had a lot of help writibng this app from here.
https://msdn.microsoft.com/en-us/library/system.net.sockets.socket.aspx
I know it is likely not wise admitting to using someone else's work but I'd rather not get this job than be dishonest about it.  Honestly, I have never used raw sockets before.  

I have played a lot with sockets especially in the "pre .net" time.  I built a lot of client/server applications, doing everything from playing MP3s on remote computers, to doing sendkeys instructions to remote systems.  I loved it.  Nowadays, Web API and JSON web services took over the fun.  SOAP too.

The only place I have ever used sockets in the ".net" time, is when I talk to my Arduinos.  I send commands to the Adruinos and then wait in a seperate thread for the response from the Arduino.

Any way.  Here goes.  To use this app:
browse to ~\Sockets test\Socks1\Socks1\bin\Debug

Run the executable file Socks1.exe.  Use these parameters: IPAddress port.

The command should look something like this:
C:\Source\GitHub\Sockets test\Socks1\Socks1\bin\Debug\Socks1 127.0.0.1 80
This will ping the localhost.  Pipe the output to an HTML file like so:
C:\Source\GitHub\Sockets test\Socks1\Socks1\bin\Debug\Socks1 127.0.0.1 80 > test.html
If you open the HTML file in a normal browser, you'll see the results.