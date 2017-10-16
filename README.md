# spring-security-ldap-example
Spring-Boot and Spring-Security LDAP Example.

**LDAP** stands for Lightweight Directory Access Protocol.
The Lightweight Directory Access Protocol (LDAP) is an open, vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network.

## **_Client and Server_**

The authentication process involves two computers: your PC and a server computer running LDAP software. A client program, such as email or some other application, resides on your computer, communicating over the network to the server computer. The application logs in to the server’s LDAP software by providing a user ID, password and other information. Based on this information, the server determines your access level and provides your client program with the data it needs, which may be an email directory for your department, a list of printers or other similarly organized information.

## **_Authentication Levels_**
LDAP authentication takes a few different forms. An anonymous authentication gives the least access to information, as it has no specific information that identifies the user; however, it is easy to perform. At the other end of the security scale, administrator authentication gives complete access not only to the information on the LDAP server but the ability to add and remove data from it. Typical users have LDAP access that lies between these extremes. For larger organizations that use LDAP, IBM recommends that the administrator create several management accounts capable of making server data changes. These need not have all the access granted to the administrator, though they let him delegate some of his daily tasks.

## **_Distinguished Name_**
To authenticate, your client program sends the LDAP server a piece of information called the DN, or Distinguished Name. Typically, a DN consists of your name or the user ID you use to log in to the computer. In addition, the DN has other information that identifies you uniquely on the network, such as a company name or the name of the server computer that runs LDAP. Associated with the DN are other data items such as the CN, or Common Name, such as “Mary Smith,” and givenName, which might contain your nickname, such as "Mae."


