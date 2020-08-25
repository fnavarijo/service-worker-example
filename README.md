# Service Worker example

### Simple App to test Service Worker functionality.

To test it, install [http-server](https://www.npmjs.com/package/http-server).
```
npm i http-server
```

And then start the webserver:
```
http-server
```

### How Service Worker... well, works
When the app starts, will install the service worker and cache the paths set in PRECACHE_URLS variable.

If you set the network to offline, and try to get this cached files will work as if it where online.

If you try to get this assets beign offline since the beginig, will show you the typicall dinosaur screen.