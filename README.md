# 1 Abstract

We compare and contrast File Transfer Protocol (FTP) and Secure-FTP (SFTP) as well as discuss our own implementation of SFTP. Our implementation of SFTP, built on the shoulders of existing FTP technology, uses industry-standard cryptographic hashing algorithms to ensure secure file transfer over the network. This project outlines the design, security, and performance of securely sending files over a network. 

First, we discuss the architecture and existing implementations of FTP and SFTP. We focus on the history and relevance of both technologies. We show that FTP is vulnerable to {network attacks} and how SFTP manages to be resilient towards attacks that are effective on FTP connections. We will briefly compare the two protocols. 

Next, we will discuss some common attacks that FTP is vulnerable to, how SFTP secures these attacks, and what cryptographic algorithms SFTP employs to become secure.

[View Full Paper Here](https://github.com/karldamus/SFTP-Implemetation-Research-Paper/blob/master/4203ProjectPaper_YeagerDamus.pdf)

- - -
Authors: Karl Damus, Jack Yeager
