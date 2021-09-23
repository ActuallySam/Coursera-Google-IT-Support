If a TCP socket is ready and listening for incoming connections, it's in the ______ state.

ESTABLISHED

CLOSE_WAIT

SYN_SENT

->LISTEN
Correct
Nice job! The LISTEN state means that a port is waiting for something to connect to it.



The most common example of a connection-oriented protocol is _____

UDP

->TCP
Correct
Great work! Other examples of connection-oriented protocols exist, but TCP is, by far, the most common.

IP



HTTP is an example of a(n) ______ layer protocol.

transport

data-link

->application
Correct
Right on! There are lots of application layer protocols, but HTTP is one of the most common ones.

network



Ports that are generally used to establish outbound connections are known as ______ ports.

system

reserved

->ephemeral
Correct
Nice job! The exact ports used are different, depending on the operating system, but they're all known as ephemeral ports.

registered



How many bits are used to direct traffic to specific services running on a networked computer?

->16
Correct
Great work! A port is a 16-bit number that's used to direct traffic to specific services running on a networked computer.

8

12

32



A user requests an unencrypted webpage from a web server running on a computer, listening on the Internet Protocol address 10.1.1.150. What will be the socket address?

10.1.1.150.21

->10.1.1.150:80
Correct
You got it! The socket address will be 10.1.1.150:80.  Unencrypted web traffic uses port 80 and ports are normally denoted with a colon after the IP address.

10.1.1.150:21

10.1.1.150.80



A connection has been terminated and no communication is possible. What is the Transmission Control Protocol (TCP) socket state?

->CLOSED
Correct
Woohoo! The TCP socket will be in the CLOSED state when the connection has been fully terminated and no further communication is possible.

CLOSE_WAIT

FINISHED

FIN_WAIT



Which field in a Transmission Control Protocol (TCP) header provides the next expected segment?

Data offset

Checksum

->Acknowledgement number
Correct
Well done! The acknowledgement number is the number of the next expected segment.

Sequence number



A communication between two devices is over the maximum limit of an ethernet frame size. The Transmission Control Protocol (TCP) splits up the data into segments. Which field in the header helps keep track of the many segments?

Urgent pointer

Acknowledgement number

Checksum

->Sequence number
Correct
Nice job! The sequence number is used to keep track of where in a sequence of TCP segments that the packet is expected to be.



A connection, at which layer, implies that every segment of data sent is acknowledged?

Network

->Transport
Correct
Well done! Sequence numbers allow the data to be put back together in the correct order.

Application

Data link




A communication sent through Transmission Control Protocol (TCP) arrives out of order. What allows the data to be put back together in the correct order?

Acknowledgement number

->Sequence numbers
Correct
Well done! Sequence numbers allow the data to be put back together in the correct order.

Preamble

Checksum




How many Transmission Control Protocol (TCP) control flags are there?

->6
Correct
You got it! There are 6 TCP control flags.

8

7

5




One side in a Transmission Control Protocol (TCP) connection has not been able to properly recover from a series of malformed segments. Which Transmission Control Protocol (TCP) flag will be used?

PSH

->RST
Correct
Awesome! The RST flag is short for reset.  This flag will start the communication from scratch, if one side cannot recover from a series of missing or malformed segments.

FIN

SYN




Which Transmission Control Protocol (TCP) flag is used to make sure the receiving end knows how to examine the sequence number field?

ACK

URG

PSH

->SYN
Correct
Well done! The SYN flag is used to make sure the receiving end knows how to examine the sequence number field.

