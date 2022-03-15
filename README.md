# PAD-peer-to-peer
Peer to peer file transfer.

# Team
<ul>
  <li>Iulia Voit</li>
-Alin Vujde
-Andrei Stelian Vasile
-Radu Serban
</ul>
# How to run files

-You must be running Linux/Ubuntu Terminal
-chmod 700 server.c
-chmod 700 structura.c
-chmod 700 structura.h
-gcc -c structura.c
-gcc -Wall -D_REENTRANT -pthread -o sv server.c structura.o
-./sv
-chmod 700 client.c
-gcc -c client.c
-gcc -Wall -D_REENTRANT -pthread -o cl client.c
-./cl
