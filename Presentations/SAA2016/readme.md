# Web Archiving Tools at Rhizome

One of the projects I worked on during my NDSR residency at Rhizome was assisting with preserving artworks in the "Archive as Artwork" collection. This collection includes artworks created on the Instagram and Tumblr social media platforms, as well as hand-coded websites.  We used a combination of tools to address the challenges  for capture posed by the combination of dynamic content and the large # of overall pages in many of the sites.  

[Archive as Artwork Collection at the Rhizome Artbase]
(https://rhizome.org/art/artbase/collections/collection-artist-made-web-archives/)

An additional challenge posed by this group of works is that some of these artworks are ongoing projects. "Veteranas and Rucas", for example, has added many posts since the archived state we created.  Rhizome hosted an event at the New Museum with a panel discussion about many of the issues involved in collecting social media work. The recording of that even can be viewed here on Livestream:

["Who Owns Digital Social Memory?"] (http://livestream.com/newmuseum/events/4837386)

### wget
Wget is an open-source program runs in the command line and provides the ability to recursively traverse an entire site and pull down all the content, as well as many options for scoping crawls of websites. 

Wget is very well-documented online, and the GNU wget manual is great place to start, for learning about how to construct crawls. The GNU Wget manual is here: 

[GNU Wget Manual] (http://www.delorie.com/gnu/docs/wget/wget.html#SEC_Top)

Within the manual, the scenarios provided on the [examples] (http://www.delorie.com/gnu/docs/wget/wget_29.html) page are especially helpful, and walk through different kinds of crawls at three levels of complexity. 

The Archive Team wiki's Wget page is another great reference to check for Wget. This page offers an introduction to using wget and helpful advice about some common problems. It also has a list of essays and other sources on wget. There are also instructions for installing wget in Windows 7, which I did not try but might be useful to have! 

[Archive Team wiki Wget] (http://www.archiveteam.org/index.php?title=Wget) 

### webrecorder

Webrecorder is a free and open-source browser-based tool that is specifically focused on capture of dynamic web content. Using Webrecorder allowed us to explore the artworks visually, browsing the site as a user would, while also capturing pages as we went. Because Webrecorder runs in the browser, javascript on each page is executed as the user explores a website, and many resources that would not be captured with wget are retrieved. This process is very time-consuming, however. For many sites, the overall number of pages to capture makes this method impractical, which is why combining wget with Webrecorder, via pywb as described below, worked well. 

Webrecorder is currently in development, and addressing what role automation could play in the process of "symmetrical web archiving" is one of the questions that the project is exploring. These presentation below, by the Webrecorder development team at Rhizome, gives an overview about some of differences between Webrecorder and previous approaches to web archiving. 

[Tools for Preserving Performative Media] (http://labs.rhizome.org/presentations/talk-20160722#/)  

One of the larger issues at stake in thinking about the inevitable incompleteness of web archiving, is how to define the boundaries of anything on the web. This article from June 2016, in the New York Times Magazine, discussed some particularly relevant considerations about the scale and nature of the web, for who and what will have their history preserved. 

[How an Archive of the Internet Could Change History] (http://www.nytimes.com/2016/06/26/magazine/how-an-archive-of-the-internet-could-change-history.html?_r=0)

### pywb
Pywb is a suite of tools for building collections of captured WARC files, and replaying the captured web content inside the collections, which was also created by Ilya Kreymer, the developer of Webrecorder. I used the documentation provided at Ilya's github repository for pywb to learn how to use this tool, and I especially recommend the tutorial he created for creating and managing collections, which is here: 

[Auto Configuration and Web Archives Collections Manager] (https://github.com/ikreymer/pywb/wiki/Auto-Configuration-and-Web-Archive-Collections-Manager)

I also wrote a post on the NDSR-NY blog which is a simplified version of Ilya's documentation, and has screenshots for walking step-by-step through the instructions for installing python, piptools, and pywb, and for using some of pywb's functions. 

[Pywb post on NDSR-NY blog]
(http://ndsr.nycdigital.org/shared-conferences-diy-web-archives/)

### Other Resources

This paper presents a very thorough and clearly-defined explanation of the problems of client-side technologies for web archiving, and also proposes a crawl method for capturing resources that are missing from most crawls. Although the scope of this paper exceeds the individually-scaled approaches I've discussed here, the literature review and definitions of terms provided by this paper are an essential frame of reference for anyone interested in learning more about web archiving. 

[Adapting the Hypercube Model to Archive Deferred Representations and Their Descendants] (http://arxiv.org/abs/1601.05142)


