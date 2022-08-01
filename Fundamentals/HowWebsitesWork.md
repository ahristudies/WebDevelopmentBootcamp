For this we have two ways to go, the first is how everyone accesses websites daily.

You type google.com in the allowed area of ​​your browser
The website appears ready to use on your computer screen.

However, as we want to be web developers, we need to understand each step in order to create more complex applications.

The first step is the same as a user, you type in your browser: google.com <- This is the URL, the address of what you want to access. URL stands for Uniform Resource Locator, imagine that your site has numbers as an address (and it does, we'll see later), but it would be very confusing to always remember that number or sometimes it can change. The URL serves as a phone book that makes it easy for you to access a website, you just need the URL (which usually never changes).

The first thing your browser will do is transform this address into a protocol, the HTTP protocol. You may have seen that some sites are written as: https://google.com, this S in HTTP is a newer version that brings more security. It has been used since the 90's. HTTP stands for HyperText Transfer Protocol, its function is to exchange messages between computers. These messages are sent in small packets of dates that are sent over the network.

So, as soon as you hit enter to access this website, a line of communication is created between your computer (client) and the server (where the files for that website are). This line of communication is another protocol, this is called the TCP protocol.

TCP - It stands for Transmission Control Protocol, its functionality is to ensure that all packets arrive correctly at their final destination.

Remember earlier, I said that the website address is can be a number? It is because in reality he is! To access the server, TCP uses the IP which stands for Internet Protocol, it is a number that comes on all computers and is what allows access to the internet. So from google.com, it will be seen in your browser as: 172.16.254.1 - for example.

The DNS (Domain Name Server) turns this URL into an IP, its function is to look in your database to see which IP number is related to that URL. This is how the conversion is done.

Now your request is going through several places, these are called proxy. Proxy is everything that gets in the way of the message, for example: router, other computers. It is he who directs the messages.

Your request will reach the server, it will analyze your request and give you a response. If it is positive, it will have a whole way back (similar to the way out) and it will be where several files will be sent to your computer.

These pieces of files are HTML, CSS, JavaScript, images, audios, videos and for each file, a new connection is created. All this in milliseconds.
