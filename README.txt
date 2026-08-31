QR Bird Marker AR

What this demo does
- Opens a camera view in Safari.
- Detects the supplied QR marker with jsQR.
- Draws a flapping bird only inside the detected QR footprint.
- The bird follows the QR when the paper is moved or rotated.
- If the QR is lost, the bird disappears.

Files
- index.html: WebAR-style camera tracker.
- bird_tracking_marker.png: printable tracking QR.

How to publish
1. Create a new public GitHub repository.
2. Upload index.html and bird_tracking_marker.png.
3. In GitHub: Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main / root.
6. GitHub will give you an HTTPS URL such as:
   https://YOUR_USERNAME.github.io/REPOSITORY_NAME/
7. Open that URL on your iPhone, tap Start camera, and point at the printed marker.

Important
The tracking QR contains a fixed marker payload, not the website URL.
This is intentional: after the AR page is open, the camera tracks the same printed marker.
You can create a separate launcher QR containing the GitHub Pages URL after publishing.
