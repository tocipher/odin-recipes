# odin-recipes

A simple static recipe website built with pure HTML (for now).

## Highlights

- Clean, minimal homepage listing all recipes.
- Individual recipe pages include a description, ingredient list, and step-by-step directions.
- Includes high-resolution images of each completed dish.

## Running Locally

This project uses [`live-server`](https://www.npmjs.com/package/live-server) for local development. 

### Option 1: Using `live-server`

Install globally:
```bash
npm install -g live-server
```

Clone and serve the site:
```bash
git clone https://github.com/tocipher/odin-recipes.git
cd odin-recipes
live-server
```

### Option 2: Using Python (`http.server`)
If you prefer not to install additional tools:
```bash
git clone https://github.com/tocipher/odin-recipes.git
cd odin-recipes
python -m http.server
```

After starting a server, the terminal will display a local address (e.g., `http://127.0.0.1:8080`) where the site can be accessed.

---
Created for educational purposes following [The Odin Project](https://www.theodinproject.com) Foundations Course.
