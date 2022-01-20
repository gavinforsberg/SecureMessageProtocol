# SecureMessageProtocol
Secure Messenger (with RSA encryption) written in Java for CIS435 (Computer and Network Security).

Group #03:
#05 | Gavin Forsberg
#08 | Jacob Gnatz
#16 | Georges Samaha

Major Components:
Phase 1: Individual Testing Cases
Phase 2: Secure Message Protocol
Sender’s Operations
Receiver’s Operations.
Testing of SMS over Sender and Receiver
Submission
Sample Output


Objectives:
1. In this project, you will build a secure message system to simulate secure email communication across the Internet.  
2. You should NOT use any existing crypto liberties, not even the ones that are part of the standard java library,
   1. You CAN refer to the “Java Cryptography Architecture (JCA) Reference Guide for designing interfaces ”https://docs.oracle.com/javase/8/docs/technotes/guides/security/crypto/CryptoSpec.html
   2. You should NOT use the implementation of any existing crypto liberties to avoid “0” credit for this project. 
3. This project aims to implement a simplified, secure facility (Shift Cipher, Hash, and RSA etc) and secure message/Email communication.

Requirements:
In the secure facility, you need to implement the three algorithms, i.e., symmetric, hash function, RSA algorithms, as described in class. 

The secure facility enables 1) Confidentiality, 2) Message Integrity, and 3) Sender authentication and should be implemented in the System.  

You may use straightforward algorithms. For example,
* Hash function can be as simple as H(x) = x mod 13.
* The symmetric encryption algorithm can be as simple as “Shift Cipher”.
* RSA algorithm: You may use the ones manually calculated and provided in the ICE for testing purposes.

Major Components
The secure message system should include six basic components, 

Sender:
* generate a message (e.g., msg) 
* process the message using the SecMsg protocol 
* send the secure packet, i.e., a cipher to Network


Receiver:
* Receives the cipher, 
* use the SecMsg protocol to decrypt the message
* discard/accept the message
* Display results
	Packet
* The packet unit sent and received via the Internet/Network
	Network
* Simulate the Internet,
* Can get a packet from the sender, 
* deliver a packet to the receiver. 
* A packet may get hacked during transmission. 
	SecMsg
* Implement the secure message protocol, as shown in Tables 1  & 2,  
* Provide an interface for the sender and the receiver to exchange messages securely.
* Simulates SSL
	Cryptography
* A simplified, secure facility (Shift Cipher, Hash, and RSA) 
	CA
* validate the user’s identities and bind them to cryptographic keys
