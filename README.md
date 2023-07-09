# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Static Server

For environments using Node, the easiest way to handle this would be to install serve and let it handle the rest:

```
npm install -g serve
serve -s build
```

The last command shown above will serve your static site on the port 3000. Like many of serve’s internal settings, the port can be adjusted using the -l or --listen flags:

```
serve -s build -l 4000
```

Run this command to get a full list of the options available:

```
serve -h
```

See the section about [deployment](https://create-react-app.dev/docs/deployment/) for more information.
