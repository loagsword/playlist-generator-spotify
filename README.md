# Playlist Generator for Spotify

Easily generate spotify playlists based on the Recommendations api from spotify.


## Start Developing

To get started playing around in this app first ofcourse clone this repo. 

This web app is build using a minimal Create React App setup and is all client-side. The app directly connects to the Spotify API. 

In order to connect to the Spotify Web API you need a Client ID in your environment variables. Create one at the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) for free.

For local development copy the `.env.example` into `.env` and set your `REACT_APP_SPOTIFY_CLIENT_ID` to your custom client ID.

After that start the same way as any Create React App.

```bash
$ npm install
$ npm start
```

## Deploying

Want to deploy directly into a instance live on [Zeit Now](https://zeit.co/now)? It's really easy. First we need to add your client ID into your 'secrets' environment variables in Zeit.

Then we can simply deploy `now`.

```bash
$ now secret add REACT_APP_SPOTIFY_CLIENT_ID=YOUR_CLIENT_ID
$ now
```

## Resources

* [Atomic Design Principles](https://github.com/ItsWendell/playlist-generator-spotify) - Methodology for creating design systems.
* [Zeit Now](https://zeit.co/now) - Global Serverless Deployments.
* [Create React App](https://github.com/facebook/create-react-app) - Set up a modern web app by running one command.
* [Spotify Web API](https://developer.spotify.com/documentation/web-api/reference/) - Spotify Web API Documentation.
* [Ant Design](https://ant.design/) - Design System and Component Library.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

--- ---

<p align="center">
    Made with :heart:
</p>
