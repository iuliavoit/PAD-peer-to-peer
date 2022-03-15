# PAD-peer-to-peer
Peer to peer file transfer.

# Team
<ul>
  <li>Iulia Voit</li>
  <li>Alin Vujde </li>
<li>Andrei Stelian Vasile</li>
<li>Radu Serban</li>
</ul>
# How to run files

<p>You must be running Linux/Ubuntu Terminal</p>
<p>chmod 700 server.c</p>
<p>chmod 700 structura.c</p>
<p>chmod 700 structura.h</p>
<p>gcc -c structura.c</p>
<p>gcc -Wall -D_REENTRANT -pthread -o sv server.c structura.o</p>
<p>./sv</p>
<p>chmod 700 client.c</p>
<p>gcc -c client.c</p>
<p>gcc -Wall -D_REENTRANT -pthread -o cl client.c</p>
<p>./cl</p>
