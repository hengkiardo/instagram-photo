# Instagram Photo Printing App


## Install Dependancies
```
npm i
```

## Run the App
```
node app.js
```

## app.js
Here we define the basic server setup, and include our `instagram.js` component.

## instagram/config.js

Configuration for Lob API Keys and Instagram Credentials

```
var config = {
  lob_api_key: 'xxxxx',
  instagram_redirect_uri: 'http://localhost:3000/handleauth',
  instagram_client_id: 'xxxxxx',
  instagram_client_secret: 'xxxxx'
}
```

## instagram/index.js
Here we declare the routes and business logic for the functionality of our Instagram App
