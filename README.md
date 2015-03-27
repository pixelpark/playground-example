Playground-example project
=====
## What is this?
This is an example project for the fic2-playground. It contains some files for a very basic project that can be handled by the playground.
 
## What to do?
The following needs have to be fulfilled to ensure that your enabler is compatible to the playground.
 
- create a GitHub repository or use an existing one
- there has to be some folder that contains your entire client site, production-ready code (for example a folder named "public_html")
- there has to be a file named "playground.json" in the root of your GitHub repository that contains the fields specified in [playground.json](playground.json)
  - the field "path" contains the path from your repositories root to the folder containing the client site code
  - the field "file" contains the name of your client site starting-file in the folder that contains the client site code (likely "index.html")
- you should provide a config.json (see [playground.json](public_html/config.json)) in your folder with client site code that configures the client and its connection to your backend
 