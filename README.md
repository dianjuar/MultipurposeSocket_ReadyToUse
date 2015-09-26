# Multipurpose Socket, Ready To Use - C++

A multipurpose Sockets ready to use written on C++ using the framework QT.

These classes are thought for every use. Just inherit what kind of socket you want to create a Client or a Server. Pass via parameter the settings than you want to the socket work for, like port to connect or listen, address to be listened, address to connect.

The classes are optimized, using signals and slot, no threads.

This only works on QT

How to use?
----------------------------------------
Select your type of socket, client or server. Whatever you choose inherit the selected class and use these parameters:

For Client class:

    - Host to connect.
    - Port to connect.
    
    
For Server class:

    - Address to listen.
    - Port to listen.


How is the setting up?
-------------------------------------------------
Just write the following line on your .pro file

    QT       += network


How I analyze the incoming data?
-----------------------------------------------------
Just overwrite the virtual method dataAnalizer(QString) and you are able to reading the incoming data. 
Simple eh?

Credits to:

    - Me, Diego Juliao Armenta ( @dianjuar )
    - The youtube channel VoidRealms
