# netflix-1080p

_Based on [https://github.com/truedread/netflix-1080p](https://github.com/truedread/netflix-1080p)_

This addons allows Firefox users to watch Netflix in 1080p instead of (artificially) restricted 720p.

After installation you can verify if it's working by checking: [https://www.netflix.com/watch/80018585](https://www.netflix.com/watch/80018585)

## Building

###  Prerequisites
Generate API credential via https://addons.mozilla.org/developers/addon/api/key/

### Compiling
```
npm install
./node_modules/.bin/web-ext sign -s src --api-key "<YOUR_KEY>" --api-secret "<YOUR_SECRET>"
```
