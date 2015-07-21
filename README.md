##### Requirements / Set Up:

If you don't have Browserify, Watchify, or Babel already installed globally, first do the following:

```
$ npm install -g browserify

$ npm install -g watchify

$ npm install -g babel
```

Then clone this repo and run the following commands:

```
$ npm install

$ npm run watch
```

If you already have those 3 above installed, just "npm install" and "npm run watch", and you are ready to go!

##### Running In The Browser:

Once the above set up has been completed, just open the **index.html** in your browser, and if you see the message below, everything is working correctly.

```
This is my own React dev starter kit :)
```

##### Developing:

The application code is in **app.jsx** and the CSS is in the **style.css** file. These are both in the **src** directory. The app code you write will be "auto transpiled" on file save. Refresh the browser to see your changes.

I tried to keep this dev playground relatively simple, as far as build automation tools go, and without getting into a full-stack app set up. This starter kit is more so you can start building out small components right away.

Go forth and build :)
