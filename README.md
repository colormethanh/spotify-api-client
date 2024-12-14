# What is this?

This repo contains a file spotifyApiClient that returns a class SpotifyClient.

This is an ongoing project and more methods will be added in the future.

## Get started

**_ Prerequisites_:** Make sure you have node installed before using and an developer account with spotify

```
const SpotifyClient = require("./spotifyApiClient")

const client = new SpotifyClient(<your client ID>, <you client secret>);

const playlistData = await client.getPlayList(<spotifyID>)
```
