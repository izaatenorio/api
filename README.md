# .env
HOST=127.0.0.1 <br>
PORT=3333 <br> 
NODE_ENV=development <br>
APP_NAME=AdonisJs <br>
APP_URL=http://${HOST}:${PORT} <br>
CACHE_VIEWS=false <br>
APP_KEY=Vgj6OzVXEA3T2fNG2vq6BrKb4Nr54Wsl <br>
DB_CONNECTION=pg <br>
DB_HOST=127.0.0.1 <br>
DB_PORT=5400 <br>
DB_USER=postgres <br>
DB_PASSWORD=12345 <br>
DB_DATABASE=api <br>
HASH_DRIVER=bcrypt <br>

# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
