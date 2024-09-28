# Smart Gluco

A mobile application for quickly measuring blood sugar levels through the picture of the eye's retina.

> [!NOTE]
> This application doesn't `keep track of` / `store` pictures that you take for **security** reasons.

<br>

## Preview of the app

<img src="/preview/img1.jpg" alt="preview 1" width="270"/>  <img src="/preview/img4.jpg" alt="preview 2" width="270"/>

<img src="/preview/img2.jpg" alt="preview 3" width="270"/>  <img src="/preview/img3.jpg" alt="preview 4" width="270"/>

<br>

## Installation

<br>

### Front End 

This is a **React-Native** Application, made with the help of the *expo* framework.

Before installing, [download and install Node.js](https://nodejs.org/en/download/).

Installation is done using `npm install`

```console
$ cd front-end
$ npm install
```

To run the expo app use 

```console
$ npx expo start
```

The above command will start an expo development server through which we can connect to our visionary glucose app from a mobile phone.

<br>



<br>

### Server

To run this express server, you should have Node.js as said above.

Installation is done using `npm install`

```console
$ cd server
$ npm install
```
Start the server using 

```console
$ node index.js
```

You will need a `.env` file or set up the environment variables to run the server.

```.env
REACT_APP_PORT = 8081
REACT_APP_ATLAS_URI=mongodb+srv://<username>:<password>@data.uqt44o8.mongodb.net/?retryWrites=true&w=majority
```

It needs a **Mongo DB ATLAS** URI and a database on it to run the app smoothly.

> [!NOTE]
> The server is already hosted by us here `https://visonary-glucometer-server.onrender.com`
