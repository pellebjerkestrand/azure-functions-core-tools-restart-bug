To reproduce, run these commands.

```sh
npm ci
npm start
```

Visit the _wave_ function's route (http://localhost:7071/api/wave).

Notice your browser showing 👋.

Replace the 👋 in [app.js](app/app.js) with 🐛 (or something else).

Notice in the console

```sh
Worker process started and initialized.
```

Refresh your browser tab.

Notice your browser still showing 👋.

The browser is expected to show 🐛 (if that's what 👋 was replaced with).
