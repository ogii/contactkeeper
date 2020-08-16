# ContactKeeper

ContactKeeper is a simple app to keep track of contacts.

## Configuring the App

After cloning the repository, install the required dependencies

```
npm install
```

In order to use the application, you must create a default.json file in the config folder,
and specify a mongoDB URI/jwtSecret in the following format:

```javascript
{
  "mongoURI": "",
  "jwtSecret": ""
}

```

### Acknowledgements

Thanks to [Brad Traversy](https://github.com/bradtraversy) for providing this project.
