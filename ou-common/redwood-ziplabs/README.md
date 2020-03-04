# Redwood Zip Labs common template

## How to use the redwood-ziplabs rendering engine
* Copy the manifest.json and index.html files from this folder into your project folder.
* Make sure you are using the Zip Labs CSS style classes
* Copy the content.md file from /templates/redwood-zip folder into your project folder.
* Edit the manifest.json file:
    *  Modify the title element - the title is displayed in a content menu on the right
    * Modify the filename to point to the Markdown file in your project folder. The path should be relative to the index.html file. 
	
   
* You can test locally using any local HTTP server, for example, [simplehttpserver](https://www.npmjs.com/package/simplehttpserver), [http-server](https://www.npmjs.com/package/http-server), [live-server](https://www.npmjs.com/package/live-server) and others.

* When deployed to GitHub, provide your customers the link to a GitHub page (oracle.github.io) that includes the path to the index.html file in your project. 