## Updated Project Setup

### How to Install
1. Install dependencies:
   ```bash
   npm install
   ```

### How to Run
1. Start the website using `live-server` with a mount point:
   ```bash
   npx live-server --mount=/buy_or_rent:.
   ```
2. Open your browser and navigate to `http://127.0.0.1:8080/buy_or_rent`.

### How to Build
1. Bundle the project for deployment:
   ```bash
   npm run build
   ```
2. The bundled files will be available in the `dist` folder, ready for deployment.

### How to run the dist

```
npx live-server --mount=/buy_or_rent:dist
```