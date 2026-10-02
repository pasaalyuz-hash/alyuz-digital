ALYUZ DIGITAL — STATIC WEBSITE

FILES
- index.html
- styles.css
- script.js
- favicon.svg

BEFORE GOING LIVE
1. Contact email is set to pasha@alyuzdigitalaccess.com.
2. Replace the founder portrait placeholder once the final portrait is created.
3. Review the copy. It intentionally says your digital experience dates to 2005; it does not claim Alyuz Digital itself was founded in 2005.

FOUNDER PHOTO
When the finished founder image is ready, the simplest implementation is to:
- save it as founder.webp in the same folder
- replace the .portrait-placeholder block in index.html with:
  <img class="founder-photo" src="founder.webp" alt="Pasa Alyuz, founder of Alyuz Digital">
- then add this CSS:
  .founder-photo { width:100%; aspect-ratio:4/5; object-fit:cover; display:block; filter:saturate(.88) contrast(1.03); }

CLOUDFLARE PAGES
This is plain static HTML/CSS/JS, so there is no build step required.
You can put these files in a GitHub repository and connect that repository to Cloudflare Pages.
