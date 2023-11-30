# Imgur-Upload
Upload images to Imgur via Javascript, no need Php.

## Demo
Click [here](https://duyplus.github.io/upload) to view now

## Getting Started
```bash
# Get the latest snapshot
$ git clone git@github.com:duyplus/upload.git
```

Register your app [click here](https://api.imgur.com/oauth2/addclient). Please choose “OAuth 2 authorization without a callback URL”. You will receive an client ID and client secret once you submit the form.

If you want to use your own clientID , you can change it [here](https://github.com/duyplus/upload/blob/main/assets/js/upload.js#L56) :
```js
new Imgur({ 
    clientid: '146def7f79c7a87', //You can change this clientID
    callback: feedback 
});
```

## Contributing
Check [CONTRIBUTING.md](CONTRIBUTING.md) for more information.

## License
[MIT](LICENSE)
