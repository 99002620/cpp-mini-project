
* Multi Client Handling Server using select()<br>
* Read / Write at same time using timers and non-blocking mode<br>
* File transfer ( Under Development ) <br>
* Group Chat<br>
* Online Clients information<br>
* User friendly GUI <br>
* Login System ( Enter username, default password is password ) <br>

Some features are underdevlopment due to lack of time and other subject pressures! <br>
Gtk used over to Qt as Qt was not permitted to use<br>

Usage:<br>
* set the ip address and port in the server.hpp and client.cpp as per requirements<br>
* build and run server.cpp on terminal <br>
* build main.cpp on other terminal<br>
* open the exe file as much as you can and enjoy chatting. (10 max Clients)<br>

->for server:<br>
 g++ server.cpp -o server<br>
 ./server<br>
 >
 ->for client<br>
 g++ main.cpp Client.cpp -o main `pkg-config --cflags --libs gtkmm-3.0`<br>
 ./main
>
Detailed Information given in report.pdf file
