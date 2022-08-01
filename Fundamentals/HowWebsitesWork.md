![Apresentação curso tecnologia para mulheres moderno neon (2)](https://user-images.githubusercontent.com/108016103/182218606-9a0c21a8-ee5c-4199-a2cd-70276b1d399e.png)
<p align="center">
 <a href="https://github.com/ahristudies/WebDevelopmentBootcamp">Home</a> •
 <a href="https://github.com/ahristudies/WebDevelopmentBootcamp/tree/main/Fundamentals">Back to main folder</a>
</p>
<p align="justify">
We already understand how the internet works, but how does accessing websites work? For this, we have two basic ways to understand. The simple that is already common knowledge and the advanced that is what we need to understand better, to become good web developers.
</p>

<h3>The first is how everyone accesses websites daily:</h3>
<ul>
  <li>You type google.com in the allowed area of your browser</li>
  <li>The website appears ready to use on your computer screen.</li>
</ul>

<h3>And this is the most detailed way:</h3>
<ul>
  <li>The first step is the same as a user, you type in your browser: google.com</li>
  <blockquote>This is the URL, the address of what you want to access. URL stands for <b>Uniform Resource Locator</b>, imagine that your site has numbers as an address (and it does, we'll see later), but it would be very confusing to always remember that number or sometimes it can change. The URL serves as a phone book that makes it easy for you to access a website, you just need the URL (which usually never changes).</blockquote>
  <li>The first thing your browser will do is transform this address into a protocol, the HTTP protocol.</li>
  <blockquote> You may have seen that some sites are written as: https://google.com, this S in HTTP is a newer version that brings more security. It has been used since the 90's. HTTP stands for <b>HyperText Transfer Protocol</b>, its function is to exchange messages between computers. These messages are sent in small packets of dates that are sent over the network.</blockquote>
   <li>So, as soon as you hit enter to access this website, a line of communication is created between your computer (<b>client</b>) and the <b>server</b> (where the files for that website are). This line of communication is another protocol, this is called the <b>TCP protocol</b>.</li>
  <blockquote>TCP - It stands for <b>Transmission Control Protocol</b>, its functionality is to ensure that all packets arrive correctly at their final destination.</blockquote>
     <li>Remember earlier, I said that the website address is can be a number? It is because in reality it is!</li>
  <blockquote>To access the server, TCP uses the IP which stands for <b>Internet Protocol</b>, it is a number that comes on all computers and is what allows access to the internet. So from google.com, it will be seen in your browser as: <b>172.16.254.1</b> - for example.</blockquote>
  <li>The DNS (<b>Domain Name Server</b>) turns this URL into an IP, its function is to look in your database to see which IP number is related to that URL. This is how the conversion is done.</li>
         <li>Now your request is going through several places, these are called proxy. Proxy is everything that gets in the way of the message, for example: router, other computers. It is he who directs the messages.</li>
   <li>Your request will reach the server, it will analyze your request and give you a response. If it is positive, it will have a whole way back (similar to the way out) and it will be where several files will be sent to your computer.</li>
  <li>These pieces of files are <b>HTML, CSS, JavaScript, images, audios, videos</b> and for each file, a new connection is created.</li> 
</ul>
<p align="center"><b>All this in milliseconds.</b></p>

<h2>What HTML, CSS and JavaScript does?</h2>
<p align="justify">
 As stated earlier, the way you view and use a website is when the server sends files to you. These files most used by developers are HTML, CSS and JavaScript, as it is the main basis for creating web applications. But what exactly do each of them do? </p>
 <p align="center">
<img src="https://user-images.githubusercontent.com/108016103/182231613-ed27bb6f-65fd-43c4-b772-a6fb8577f961.png" align="center" width="300px">
</p>
<p align="justify">
The image above shows a metaphor for each of these languages, it is the most used in courses, as it is the most "accurate".

 <b>HTML</b> - It's the structure of every website start, it's how you define where each column or header will go.

 <b>CSS</b> - HTML alone doesn't look pretty, after all it's a markdown language (very used in 90's websites), so today we have CSS that brings more beauty and design to the website. This is how buttons are customized, leaving a better positioned navigation bar on the site.

 <b>JavaScript</b> - If we already have the structure and the visual part already established, what do we need? Let it be a functional page! That's how Javascript works, it makes a button work, it brings motion perhaps to a slide of photos.
 </p>
