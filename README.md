# Abir Aldin Aotul — E-Portfolio

A responsive, single-page academic and professional portfolio built with HTML, CSS and vanilla JavaScript. It is prepared for GitHub Pages.

## Included
- `index.html` — complete portfolio website
- `assets/profile.jpg` — supplied profile photo
- `assets/project-aiub-course-scheduling.png` — supplied featured project banner
- `assets/project-super-shop-sales.png` — supplied featured project banner
- `assets/abir-cv.pdf` — supplied CV
- `assets/certificate-vibe-coding-ai-dev-fest-2026.pdf` — supplied Vibe Coding certificate
- `assets/certificate-ai-adoption-seminar.pdf` — supplied 6sense seminar certificate

## Publish with GitHub Pages

Your GitHub username, based on the repositories you supplied, is `abir-aldin`.

1. Sign in to GitHub.
2. Create a **new public repository** named exactly: `abir-aldin.github.io`
3. Extract this ZIP file on your computer.
4. Upload **the contents inside** the `abir-eportfolio` folder (not the folder itself) to the root of the new repository. `index.html` must be at the repository root, and the `assets` folder must sit beside it.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then save.
8. After GitHub finishes publishing, your site should be available at:
   `https://abir-aldin.github.io`

## Before final submission
- Add your introduction video. The faculty brief asks for a short self-introduction video, but no video file has been supplied yet. The website currently marks this section as pending.
- Review the project descriptions and add project screenshots if you have them.
- Check the published site on both desktop and mobile.
- Open every CV and certificate link after publishing.

## Add the introduction video later
When you have recorded your video, place the MP4 file in `assets/` (for example, `assets/introduction-video.mp4`). Then replace the placeholder `<div class="video-placeholder">...</div>` in `index.html` with:

```html
<video controls playsinline preload="metadata" style="width:100%;border-radius:17px">
  <source src="assets/introduction-video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

## Privacy
The portfolio intentionally uses your professional email and public profile links. Your residential address and phone number from the CV have not been published on the website.

- `assets/project-hostel-meal-manager.png` — supplied Hostel Meal Manager application screenshot
