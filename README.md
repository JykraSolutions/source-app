# Source App
This is the client side ionic app for the Source App.


## Installation
To run this app
```
npm install
```

## Development
By default. Source-App will attempt to connect with the production API. This is so we can update to the build with the production URL in place.

To run in development mode just uncomment out line 2 of `app.js` and run

```
ionic serve
```
Don't forget to comment it out when you make your merge request.



## Contributing
Once you have forked the repo and run the steps in installation,

```
git remote add upstream https://github.com/source/source-app
```

Once you are ready to start working on a feature
```
git checkout -b feature/<your-feature-branch>
git add .
git commit -m "<a summary of your changes>"
git push origin feature/<your-feature-branch>
```
Once in GitHub, create a pull request to upstream. Once it is approved you will have to then
```
git checkout master
git pull upstream master
```
