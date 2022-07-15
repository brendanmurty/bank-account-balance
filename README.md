# bank-account-balance

A small script to show your [Up bank](https://up.com.au/) account balance(s).

## Setup

1. [Install Deno](https://deno.land/#installation)
2. Setup your [Up Personal Access Token](https://api.up.com.au/getting_started) 
3. Copy `.env.example` to `.env`
4. Edit `.env` and set appropriate values for each variable

## Usage

### Terminal

```
deno run --allow-net --allow-read --allow-env cli.ts
```

### Local webserver

```
deno run --allow-net --allow-write --allow-read --allow-env server.ts
```

Then open [localhost:8001](http://localhost:8001/) in your web browser.
