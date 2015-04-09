Playground-example project
=====
## What is this?
This is an example project for the fic2-playground of the [FIcontent](http://mediafi.org/) project. It contains some files for a very basic project that can be handled by the playground (think 'Hello, world').

## What to do?
If you follow these steps, you can prepare your enabler for the playground.
The following needs have to be fulfilled to ensure that your enabler is compatible to the playground.
 
1. create a GitHub repository or use an existing one
2. there has to be some folder that contains your entire client site, production-ready code (for example a folder named "public_html")
3. there has to be a file named "playground.json" in the root of your GitHub repository that contains the fields specified in [playground.json](playground.json)
  - the field "path" contains the path from your repositories root to the folder containing the client site code
  - the field "file" contains the name of your client site starting-file in the folder that contains the client site code (likely "index.html")
4. you should provide a config.json (see [config.json](public_html/config.json)) in your folder with client site code that configures the client and its connection to your backend
5. tell us when you are ready by creating an issue or a pull request to this readme.

## Enablers that are ready

- [PPnet](https://github.com/pixelpark/ppnet)
- [XML3D](https://github.com/dirkk0/simpleXML3D)
- [POIProxy](https://github.com/Prodevelop/POIProxy-playground)

 
