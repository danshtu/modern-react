# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


### Local API using json-server:
> `npx json-server --watch data/db.json --port 8000`

#### Endpoints:
- `GET /blogs` - Fetch all blogs
- `GET /blogs/{id}` - Fetch a single blog
- `POST /blogs` - Add a new blog
- `DELETE /blogs/{id}` - Delete a blog
