# Local glTF Viewer

Open the viewer locally to preview your `.glb` files in a browser.

1. From your project root (where your `.glb` files are), start a simple HTTP server:

```powershell
python -m http.server 8000
```

2. Open this URL in your browser:

http://localhost:8000/viewer/index.html?model=cup.glb

3. Use the dropdown to switch models or drag-and-drop a `.glb` file onto the page.

Notes:
- The server must run from the repo root so the viewer can access files like `./cup.glb`.
- If Python is not installed, install it or use any static file server.
