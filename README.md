## Updated Project Setup

### How to Install
1. Install dependencies:
   ```bash
   npm install
   ```

### How to Run
1. Start the website using a lightweight HTTP server:
   ```bash
   npx http-server -c-1 --proxy http://localhost:8080/ /buy_or_rent
   ```
2. Open your browser and navigate to `http://localhost:8080/buy_or_rent`.

### How to Build
1. Bundle the project for deployment:
   ```bash
   npm run build
   ```
2. The bundled files will be available in the `dist` folder, ready for deployment.

### How to run the dist

```
npx http-server dist -c-1 --proxy http://localhost:8080/ /buy_or_rent
```