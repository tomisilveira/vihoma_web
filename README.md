# Vihoma Website

Static website for Vihoma Servicios Integrales.

## How to Run Locally ("Deploy" on computer)

Since this is a static website (HTML, CSS, JS), you can run it using several methods.

### Option 1: VS Code Live Server (Recommended)
If you are using Visual Studio Code:
1.  Install the **"Live Server"** extension (by Ritwick Dey).
2.  Open `index.html`.
3.  Click **"Go Live"** in the bottom right corner of VS Code.

### Option 2: Using Python (You have this installed)
Since you have Python installed, you can start a server instantly:
1.  Open your terminal in this folder.
2.  Run:
    ```bash
    python -m http.server 8000
    ```
3.  Open your browser to `http://localhost:8000`.

### Option 3: Using Node.js (You have this installed)
You can use `npx` to run a server without installing anything globally:
1.  Open your terminal.
2.  Run:
    ```bash
    npx serve .
    ```
3.  Open the URL shown (usually `http://localhost:3000`).

## Deployment to Internet (GitHub Pages)
Since this project is in a GitHub folder (`Documents\GitHub\web_vihoma`), the easiest way to share it is **GitHub Pages**:
1.  Push your code to GitHub.
2.  Go to the Repository **Settings**.
3.  Go to **Pages** (on the left sidebar).
4.  Select `main` branch and `/root` folder.
5.  Save. Your site will be online in a few minutes!
