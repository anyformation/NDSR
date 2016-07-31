# Web Archiving Tools at Rhizome

One of the projects I worked on during my residency was assisting my NDSR host site mentor at Rhizome to preserve works in the "Archive as Artwork" collection. This collection includes artworks created on the Instagram and Tumblr social media platforms, as well as hand-coded websites.  We used a combination of tools to address the challenges  for capture posed by the combination of dynamic content and the large # of overall pages in many of the sites.  
[Archive as Artwork Collection]
(https://rhizome.org/art/artbase/collections/collection-artist-made-web-archives/)

An additional challenge posed by the Art of The Artwork collection is that some of these artworks are ongoing projects. "Veteranas and Rucas", for example, has added many posts since the archived state we created.  Rhizome hosted an event at the New Museum with a panel discussion about many of the issues involved in collecting social media work. The recording of that even can be viewed here on Livestream:

["Who Owns Digital Social Memory?"] (http://livestream.com/newmuseum/events/4837386)

### wget
Wget runs in the command line provides many options for scoping crawls of websites. 

Wget is very well-documented online; some of the most helpful sites I discovered were: 

### webrecorder

Webrecorder allowed us to explore the artworks visually, browsing the site as a user while also capturing pages as we went. This process is very time-consuming, however. For many sites, the overall number of pages makes this method impossible.  


### pywb
Pywb is a suite of tools for building collections of captured WARC files, and replaying the captured web content inside the collections. 

I used the documentation provided at Ilya's github repository for pywb to learn how to use pywb. I especially recommend the tutorial he created for creating and managing collections, which is here: 

[Auto Configuration and Web Archives Collections Manager] (https://github.com/ikreymer/pywb/wiki/Auto-Configuration-and-Web-Archive-Collections-Manager)

I wrote a post on the NDSR-NY blog which is a simplified version of Ilya's documentation, and has screenshots for walking step-by-step through the instructions for installing python, piptools, and pywb, and for using some of pywb's functions. 

[Pywb post on NDSR-NY blog]
(http://ndsr.nycdigital.org/shared-conferences-diy-web-archives/)


### Other Resources

