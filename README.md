# Luis Ramirez Portfolio

Static GitHub Pages portfolio for `luisramirez95.github.io`.

## Publish
1. Create a PUBLIC GitHub repository named `luisramirez95.github.io`.
2. Upload everything in this folder to the root of the repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. The site will be available at `https://luisramirez95.github.io`.

## Add photos
Put image files in `assets/images/` and replace a `.media-placeholder` block with:

```html
<img class="project-image" src="assets/images/your-image.jpg" alt="Description of image">
```

Add this to `styles.css` if desired:

```css
.project-image { width:100%; height:100%; object-fit:cover; display:block; border-radius:24px; }
```

## Add local videos
Put MP4 files in `assets/videos/` and replace a placeholder with:

```html
<video controls autoplay muted loop playsinline class="project-video">
  <source src="assets/videos/robot-demo.mp4" type="video/mp4">
</video>
```

For large videos, YouTube or Vimeo embedding is usually better than storing large files directly in GitHub.
