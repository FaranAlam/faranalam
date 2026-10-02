# GitHub Profile Setup — Fix for Broken Images & Real Contributions

1. Open your profile repository: https://github.com/FaranAlam/faranalam
2. Extract this ZIP on your computer. Upload `README.md`, the **whole** `assets/` folder, and `.github/workflows/snake.yml` to the root of the `main` branch. Preserve folder names. Do not upload the ZIP as one file.
3. If GitHub currently shows `engineering.svg` beside README at the repository root, delete that old root file **after** uploading `assets/engineering.svg`. README expects `assets/engineering.svg`.
4. Check image path in the browser: https://github.com/FaranAlam/faranalam/blob/main/assets/engineering.svg — if 404, the folder was not uploaded correctly. All other artwork uses `assets/...` too.
5. In your profile repository go to **Actions → Generate contribution snake → Run workflow**. Repository Settings → Actions → General → Workflow permissions may need **Read and write permissions** for output branch publishing.
6. After workflow finishes successfully, check `https://raw.githubusercontent.com/FaranAlam/faranalam/output/github-contribution-grid-snake-dark.svg` in a browser. If it displays, uncomment the image in README's REAL GITHUB CONTRIBUTION ACTIVITY section and remove the instructional text in that collapsible section if desired.
7. The button to your native GitHub contribution calendar works immediately, independent of any external graph service. GitHub does not provide a supported direct live embed of its native calendar into a README. The snake is real contribution data after its first successful workflow run.

If an image remains broken, open its `assets/...` path directly in your repository and check capitalization. GitHub renders only files actually committed, not files sitting in a ZIP.
