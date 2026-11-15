# Multi Data Fusion

## Run in development

From this directory, install dependencies once and start Vite:

```powershell
npm install
npm run dev
```

Open the local URL printed by Vite. Edit `src/App.tsx` and `src/index.css` to
change the app; the browser reloads changes automatically.

## Build the Windows executable

On Windows, run:

```powershell
npm run package:win
```

The portable x64 executable is written to
`release/Multi-Data-Fusion-0.0.0.exe`. It does not need a separate installer.
Because it is unsigned, Windows may show an unknown-publisher warning when it
is first launched.

Build and lint checks can also be run separately:

```powershell
npm run build
npm run lint
```
