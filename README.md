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

### Boot

to start this project do the clone and inside the project run in your terminal

```bash
npm install
```
and 

```js
adonis serve --dev
```

### Routes

to list all available routes next to your method to make the request run in your terminal

```js
adonis route:list
```


