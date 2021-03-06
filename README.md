# rucio-notifier
Rucio Notification Utility with a graphical user interface.
The app uses React v16.13.1 and Electron v7.0.0.
This repo (viveknigam3003/rucio-notifier) has been ported to [rucio/notifier](https://github.com/rucio/notifier).

## Getting Started
Fork the repository or clone it directly to run on your system.

```BASH
$ git clone https://github.com/<your-username>/rucio-notifier.git
$ cd rucio-notifier
```

__Starting the React and Electron Servers (Dev)__

To start the React dev server

```BASH
$ npm install && npm start
```

To run the electron app window with React. Open a new terminal window and run

```BASH
$ npm run electron
```

This will start the React dev server inside of an Electron window. Any changes will be refleted live in the app.

## Troubleshooting

In case of an `code ELIFECYCLE` npm error, perform the following steps

```BASH
$ npm cache clean --force
$ rm -rf node_modules package-lock.json
$ npm install && npm start
```

## Notes

This project is under development as part of the Google Summer of Code 2020 project for CERN-HSF's Rucio.
It is not yet ready for production release.
