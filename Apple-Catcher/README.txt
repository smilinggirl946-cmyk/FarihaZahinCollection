# My Apple Catcher — Windows EXE project

This project is ready to build as a Windows `.exe` with GitHub Actions.

## Files
- `applecatcher.html` — the game
- `main.cjs` — Electron desktop wrapper
- `package.json` — Electron + electron-builder configuration
- `.github/workflows/build-exe.yml` — automatic Windows EXE build

## Build on GitHub
1. Upload these files to a GitHub repository.
2. Open **Actions**.
3. Select **Build Apple Catcher EXE**.
4. Click **Run workflow**.
5. Open the completed workflow run.
6. Download the artifact named **Apple-Catcher-Windows-EXE**.
7. Inside it is the `.exe` installer.

The current HTML is kept as supplied; the HOME-button change was not added.
