## Executive Summary   
In Lab4 we will be covering cybersecurity and encryption, internet architecture, HTML5/CSS, URLs/file paths and file/folder compression.   

### Cybersecurity and Encryption  
It would be my job to make sure that customer information is private and only accusable to them, information regarding products is always accurate and allow customers to access our website.   

For gmail I must use my password, then the pin they give me on the Google Authentication application on my phone.   

My phone uses my finger print and it can require a pin to unlock along with the finger print scan.   

My home computer only needs a password to log into. I could get a RFID reader so that it requires my phone or an authorized devise (a card or fob) to log in as well.  

ACL is when you have a list of users who you give individual permissions to. RBAC is when you create roles with permissions attached to them and you assigned the users a role.  ACL is very simple to assign permissions to users, but you must assign the permissions individually. With RBAC you can create roles with multiple permissions assigned to them making it easier to change the role rather than multiple permissions, a drawback of RBAC can be that you would have to create multiple rolls with different combinations of permissions.   

One person will write a message and their public key will encode it, turning it into ciphertext making it difficult for anyone who intercepts the message to read it. The recipient will receive the message and use their private key to turn the message back into plain text or its original message.   

With public keys we can send messages to anyone using them, but they can't be read without that person's private key that they have the only copy of. This way only the intended recipient can decode messages and it's less likely that the decryption key will be compromised.  

#### Cryptography  
The secret message was 'test' and came out as 'grfg'. All the letters were moved up by 14 since that's what I selected.   

The frequency fingerprint exploration tool shows what letters are most commonly used in the message compared to the letters most commonly used in the English language. This would not work with other languages since it is based on what letters we use in the English language.   

A polyalphabetic cipher is when you shift the letters in the message based on a secret word that only the sender and the recipient should have. Each letter in the secret word holds its number value and in order you shift each letter of the encrypted message by these values. This way each letter of the message is shifted by a different number, making it harder to find a trend and crack the encryption.  

Using the polyalphabetic exploration, I entered 'this is a test' as my secret message and 'test' as my shift word, making the secret message read 'nmbm cx t nyxm'. Each letter in the secret message was shifted by a different number according to my shift word. This makes the trend harder to find when looking for a frequency fingerprint.  

##### Brute-Force  
Brute-force uses every possible combination of letters to unlock the cipher and read the secret message. Kerckhoff's principle is that a cipher should still be secure even if everyone knows the method of encryption and hold a copy of the ciphertext. By this principle the Caesar Cipher isn't secure and can be easily cracked by brute-force, but when you are using a polyalphabetic cipher with a shift word or a key it can't be cracked without knowing what the key to the ciphertext is (like a private key).   

### Internet Architecture  

##### Internet Protocol  
IP addresses are numbers assigned to nodes and websites to help these systems communicate over the internet by using packets of information being sent between the IP addresses. IPv4 is an internet protocol that uses four separate numbers separated with dots (each between the number 0 and 255). IPv6 is an internet protocol that uses hexadecimal characters seperated by colons instead of dots.   

ICANN is a nonprofit group who organizes and maintains RIRs around the world.  

##### TCP/IP  
TCP and IP are protocols that decide how data travels through networking hardware allowing nodes to communicate and access the internet.  

A client requests connection to an IP or a domain on a server, the server answers the request and sends data back to the client initiating a connection.  

Protocol stacks allow changes in sending protocols without having to change the application or software. 

The applications that are being ran are the transfer protocols such as HTTP, HTTPS and FTP. 

##### Internet Security  
HTTP is a transfer protocol that displays a website on your browser, and it decides how the data will be transferred over the internet. In this case it will be transferred in plain text. 

HTTPS uses two protocols SSL and TLS. SSL and TLS is when your computer asks for a website and the server for that website sends an SSL certificate to your computer to show that it can be trusted before sending the encrypted data through HTTPS.  

##### Securing your Web Browser  
It is important to secure your browser because people can collect your private data or take control of your computer. 

ActiveX being installed on your system puts you at risk of having an attacker taking control of your computer through Internet Explorer. 

### Internet Programming  
Tim Berners-Lee is the creator and director of W3C. His intention is to make sure the web is at its full potential and is benefiting humanity. 

I think Web architecture is an important standard because it supports protocols and the technologies involved with the foundation of the web. 

##### HTML5 and CSS  
HTML5 is an easy to read language like python used to program web pages. Using HTML5 I made a page with a simple title for my topic, a short paragraph covering the topic and an embedded link taking you to the website related to the topic. CSS let me change the background color, text color and create a border around my paragraph to give my web page a different look. 

##### HTML and XML  
XML is used to store and transfer data where HTML is used to display data. 

### Components of a URL  
Scheme - https 

Domain -  www.amazon.com 

Top level domain - .edu 

Default page - no file path provided 

Parameters - result of search 

Anchor - specific location on a page 

### File Compression  

File compression is used to make file sizes smaller in order to make them more convenient to send and share.  

The original file was 3.58KB and was 899Bytes after compression. A jpg file would only have a slightly smaller difference in file size compared to the svg file after compression 

### Conclusion  

In Lab4 we learned different ways that we can protect ourselves from cyber attacks, keeping our data safe on the web, how web pages are made with HTML5 and file compression. 
