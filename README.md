# JSON Server Demo

A demo for [json-server](https://github.com/typicode/json-server) and it's [custom routes](https://github.com/typicode/json-server#add-custom-routes) feature

## Installation

```bash
npm install
```

## Start JSON Server

```bash
npm start
```

## Examples

### Change pagination parameter `_page` & `_limit` to `page` & `limit`

1. Start JSON server

    ```bash
    npm start
    ```

2. Go to [http://localhost:3000/posts?page=2&limit=2](http://localhost:3000/posts?page=2&limit=2), you'll get:

    ```json
    [
      {
        "id": 3,
        "title": "json-server",
        "author": "typicode1"
      },
      {
        "id": 4,
        "title": "json-server",
        "author": "typicode1"
      }
    ]

    ```

See [routes.json](./routes.json) for custom route configuration details.
