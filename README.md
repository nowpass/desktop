# NOWPASS Desktop Application

> Please note that NOWPASS is currently in an early alpha stage and not ready for productive use.

This is the Desktop application of the NOWPASS Open Source password manager based on Electron.

## Installation Instructions

Download one of the prebuilt release packages for your operating system or build it yourself, by cloning this repository (See Development).

## Development

### Getting Started

These instructions will get you a copy of the project up and running on your local machine. 

#### Prerequisites

Clone the project and install all dependencies needed to run the application.

```
git clone --depth 1 https://github.com/nowpass/desktop
```

#### Installing

After checking out the repository, you first have to install all needed dependencies.

```
cd desktop
npm install
```

After this you need to create (e.g. npm run build) the *.js dependencies from the NOWPASS vue-frontend project (e.g. app.js, manifest.js and vendor.js) and put them into the static/js folder.

### Running the Application

```
npm start
```

This starts the desktop application.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/nowpass/desktop/tags). 

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details
