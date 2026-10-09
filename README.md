# Ali & Wishma — 1,000 Days of Us ❤️

A romantic, responsive static website customized for Ali Jalal and Wishma, with a live relationship counter, an expandable love letter, floating hearts, and a three-photo gallery. The three photos you supplied are included in the `images/` folder.

## Date note
Relationship start date is set to **February 25, 2024**. If the start date is counted as day one, the 1,000th day is **November 20, 2026**. The live counter displays elapsed time since midnight at the start date, so its displayed elapsed-day number may differ by one from inclusive anniversary counting.

## Preview on your computer
Open `index.html` in a modern browser. The counter and love-letter interaction work locally. Photo upload previews are temporary in-browser previews and are not automatically published.

## Publish free with GitHub Pages

1. Sign in to [GitHub](https://github.com/) or create an account.
2. Click **New repository**.
3. Name it `ali-wishma-1000-days` (or another available name).
4. Choose **Public**, then create the repository.
5. Upload `index.html`, `README.md`, and the entire `images` folder (containing all three photos) to the repository's root. You can use **Add file → Upload files**. If using GitHub's browser uploader, select all three files plus the photos inside `images` after creating the folder, or upload the folder contents into an `images` directory.
6. Open the repository's **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose branch **main** and folder **/(root)**, then click **Save**.
9. Wait a minute or two. GitHub will show the published website URL in **Settings → Pages**, typically `https://YOUR-USERNAME.github.io/ali-wishma-1000-days/`.
10. Open that URL on your phone and share it with Wishma.

## Add photos that appear for everyone
The gallery currently lets you choose local photos to preview on your own browser. For photos to be available to everyone on the published site:

1. Create a folder named `images` in the repository.
2. Upload three photos with simple names, e.g. `memory-1.jpg`, `memory-2.jpg`, `memory-3.jpg`.
3. In `index.html`, find the `<div class="gallery">` block. Replace each `<label class="photo">...</label>` gallery item with a structure like this, adjusting the filename and alt text:

   ```html
   <div class="photo">
     <img src="images/memory-1.jpg" alt="A favorite memory together" style="display:block">
   </div>
   ```
4. Repeat for each image and commit the change.

**Privacy tip:** A public GitHub Pages site can be seen by anyone with the link and may be indexed. Only upload photos and personal details you're both comfortable sharing. You can keep the repository private if your GitHub plan supports Pages for private repositories, or use a public repository with minimal personal information.

## Personalize the words
Edit `index.html` to adjust the timeline moments and letter. No build tools, framework, or paid hosting are required.
