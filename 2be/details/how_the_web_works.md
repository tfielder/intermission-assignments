## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
  Your computer looks for the info on www.example.com in the cache to see if it has info on this website in the first place.  It also sends out a query to get the information from www.example.com via the internet going from your
  computer to your router/modem, to your ISP (internet service provider), which queries other ISPs for the server
  containing the info for www.example.com.  The website address has been converted into a four part binary URL.  This URL is included in the query along with additional info on the different stops the info has taken along the way to
  query the server.  Once the server receives the query, it sends packets of info back along the same channel to
  the computer and ultimately to the browser to be interpreted by the client computer.

1.  What does HTTP stand for?
    HTTP stands for Hyper Text Transfer Protocol, which is generally used as the way info is served and sent
    through the internet to send and receive web pages.
1. 	What protocol does the World Wide Web use?
    The World Wide Web generally uses HTTP for sending and receiving web pages, although HTTPs (secure) is
    commonplace as well.
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
    IP stands for Internet Protocol.
1. 	What does DNS stand for?      **** A  Domain Name System
  * A. Domain Name System        
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service
1. 	How are text domain names matched to their respective numeric IP addresses.
    There is a registry system in which website names are assigned their respective numeric IP addresses.
    An authoritative name server stores the matching names with numeric IP addresses.
1. 	What is the client? *****E The computer which the IP address belongs to
  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * C. The software which requests information from a server (browser)
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to
1. 	What does URL stand for?
    URL stands for Uniform Resource Locator.  It is a web address.
1. 	What are protocols  
 * A. The standardisation of IP addressess
 * B. The DNS standard method for data transfer
 * C.	The standardised network address system
 * D.	The standardised method for transferring data or documents over a network
 * E.	The standardised method for prioratising data or document storage over a network
1. What does DNS stand for?
    DNS stands for Domain Name System.
1. what is the `www` portion of a url?
    It stands for world wide web and it is the subdomain for many URLs.
1. What is The markup language used for all web documents?
    For most web documents, HTML or hypertext markup language is standard.
1. What is the organization that monitors web technologies?
    The World Wide Web consortium is a group of druids who meet annually to monitor web technologies.
1. What is the Protocol for transferring web documents on the Internet?
    FTP or file transfer protocol is a protocol for transferring documents on the internet.
1. What matches the domain names with numeric IP addresses?
    The authoritative name server matches the domain names with the numeric IP address based on domain name registry.
