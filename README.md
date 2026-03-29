# Todo 📋

This is a simple React + Vite project, created as an example during a class with my students.

2025 - 2026

## Prepare Application to publish in GotHub Pages

1. install gh-pages

```bash
npm install gh-pages --save-dev
```

2. modify `package.json` file

```json
{
  "homepage": "https://Pjotair.github.io/todoapp",
  "scripts": {
    "deploy": "gh-pages -d dist"
  },
  "devDependencies": {
    "gh-pages": "^6.3.0" // to jest nowa zaleźność developerska
  }
}
```

3. Send changes to GitHub

4. Set Pages settings

5. Tu biuld adn run
```bash
npm run deploy
```
