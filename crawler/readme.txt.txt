Status of the project 2/9/19
The crawler
- Checks the gexf file
- Extracts the websites with the nodes, taking the homepage or just the name if no hp is set
- Compares the website to the already downloaded pages (using md5 hash)
 => note : need to check for the last website if all pages are downloaded
- For the first site for the moment, goes to the main page, create a folder, saves the main page as index.html, extracts all the links containing the main site and save all html from those links
