1. Explanatory Paragraph
When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser
acts as a client and sends a request to the web server. The browser and server communicate using HTTP
(Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure). HTTPS encrypts communication to
help protect information. The server processes the request and, when necessary, gets information from a
database. It then sends a response containing resources such as HTML, CSS, JavaScript, and images. The
browser reads these resources and displays the website on the screen. This process of sending a request and
receiving a response is called the request-response cycle. A static website usually displays fixed content, while a
dynamic website can show changing content based on user actions, server-side processing, or information stored
in a database.
2. Important Terms
Browser: Software, such as Google Chrome, used to open and view websites.
Client: The user's device or application that sends a request to a server.
Server: A computer or software that receives requests and sends website resources or data.
Database: An organised collection of data that a website can store, retrieve, or update.
HTTP: Hypertext Transfer Protocol; a protocol used to transfer data between a browser and a web server.
HTTPS: Hypertext Transfer Protocol Secure; HTTP protected with encryption using TLS.
3. Request-Response Cycle
1. The user enters a URL in the browser.
2. The browser finds the server's address and sends an HTTP/HTTPS request.
3. The server processes the request and may access a database.
4. The server sends an HTTP response, including a status code and requested resources.
5. The browser processes the resources and displays the website.
4. Difference Between Static and Dynamic Websites
Static Website Dynamic Website
Content is usually fixed until files are changed. Content can change based on user actions or data.
Often uses HTML and CSS, with JavaScript if needed. May use frontend code, server-side code, and databases.
Usually simpler to build and host. May need more processing and a backend.
Example: a simple informational page. Example: an online shopping site or social media feed.
5. Practical: Inspect Requests in Chrome DevTools
1. Open Google Chrome and visit https://example.com.
2. Open DevTools by pressing Ctrl + Shift + I (Windows).
3. Select the Network tab.
4. Reload the page by pressing Ctrl + R.
5. Observe columns such as Name, Status, Type, Size, and Time.
6. Take a screenshot showing the Network tab and list of requests, then insert it below.
Observation
The Network tab shows the resources requested by the browser while loading a website. It provides details such
as each request's name, status code, resource type, size, and loading time. This helps us understand
communication between the browser and the server.
