# Argly

## About

Argly is an application to support online argumentation. Arguments can be created, analyzed and critiqued.

## Usage

In a terminal, from the cloned project folder, run:

```bash
docker compose up
```

NGINX will now serve files in the app/public folder. Visit localhost in your browser to check.
PHPMyAdmin is accessible on localhost:8080

If you want to stop the containers, press Ctrl+C.

Or run:

```bash
docker compose down
```

### Client app

From the `app/public/assets/js/argly` directory, run:

- `npm i`
- `npm run dev`

To build:

- `npm run build`

## TODO

- setup directory structure
- env file
- import bootstrap
- create basic design

## To cover

- project structure
- dir includes: require_once(**DIR**. "/home.php");
- formatting Intellephense
- routing
- low-fi approach
- function/scoping
- types
- interfaces
- falsey
- code in markup
- layers responsibility
- postman
- php global and use, function scope
- typeish (more like hints)
