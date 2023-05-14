# What happens when you type google com in your browser and press enter.

When you type “https://www.google.com" into your web browser and hit enter, a chain of events is set in motion that ultimately results in the webpage being displayed on your screen. Let’s take a closer look at the steps involved in this process:

The first thing your browser does is to send a DNS (Domain Name System) request to a DNS server. This request asks the DNS server to translate the domain name “www.google.com" into an IP address. This is necessary because computers communicate using IP addresses, but humans find it easier to remember domain names.

Once the DNS server responds with the IP address of the web server that hosts Google, your browser initiates a TCP/IP (Transmission Control Protocol/Internet Protocol) connection with that server. TCP/IP is the set of protocols that enables computers to communicate over the internet.

Before the TCP/IP connection is established, the web server’s firewall may inspect the incoming request to make sure it is not malicious or unauthorized. If the request passes the firewall’s inspection, the TCP/IP connection is established.

Once the TCP/IP connection is established, your browser and the web server negotiate a secure connection using HTTPS (Hypertext Transfer Protocol Secure) and SSL (Secure Socket Layer) protocols. This is important to ensure that any data transferred between your browser and the web server is encrypted and secure from eavesdropping.

In some cases, the web server may be behind a load-balancer, which distributes incoming requests to multiple web servers to ensure high availability and optimal performance. The load-balancer may inspect the incoming request to determine which web server is best suited to handle it.

Once the secure connection is established, your browser sends an HTTP (Hypertext Transfer Protocol) request to the web server, asking for the webpage at the specified URL. The web server processes the request, retrieves the necessary data from its file system, and generates an HTTP response.

In some cases, the web server may need to communicate with an application server to generate the response. For example, if you are searching Google for something, the web server may need to communicate with Google’s search application to retrieve the relevant search results.

In some cases, the application server may need to communicate with a database to retrieve the data needed to generate the response. For example, if you are searching for a product on an e-commerce website, the application server may need to retrieve the product information from a database.

Once the web server has generated the HTTP response, it sends it back to your browser over the secure connection. The response typically includes HTML, CSS, JavaScript, and other files needed to render the webpage in your browser.

Finally, your browser receives the HTTP response and uses the HTML, CSS, and JavaScript files to render the webpage on your screen. The rendering process includes parsing the HTML code, applying the CSS styles, and executing any JavaScript code. Once the rendering is complete, the webpage is displayed in your browser for you to interact with.

In conclusion, typing “https://www.google.com" in your browser and hitting enter triggers a complex process involving multiple layers of technology, from DNS requests to database queries. Understanding this process can help you appreciate the complexity of the modern web and the infrastructure required to deliver it to your screen.


https://medium.com/@chuqudeeokereafor/what-happens-when-you-type-google-com-in-your-browser-and-press-enter-45810b252d61
