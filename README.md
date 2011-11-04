# Example App for [Design.io](https://github.com/viatropos/design.io)

[![Here's a video tutorial on vimeo](http://i.imgur.com/JunAS.png)](http://player.vimeo.com/video/31589739?title=0&amp;byline=0&amp;portrait=0&autoplay=true)

First, clone this app.

```
git clone https://github.com/viatropos/design.io-example.git
```

Then `cd` into the example project and install design.io and friends:

```
cd design.io-example
npm install
```

Next, start the server:

```
node server.js
```

Finally, run the `design.io` command:

```
design.io --watch ./src
```

That `design.io --watch [directory]` command will watch a directory for changes and inject JavaScripts and StyleSheets into the LIVE example web app whenever you hit save.  It does it in a clean an optimized way.

So, edit the files in `./src` and watch the stuff in the page change in real time.
