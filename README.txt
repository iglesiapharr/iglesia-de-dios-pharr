IGLESIA DE DIOS SEPTIMO DIA PHARR — WEBSITE

FILES
- index.html: page content and structure
- style.css: colors, layout, and mobile design
- script.js: language toggle, menu, carousel, and sermon controls
- data.js: the only file normally edited for banners and weekly sermons

LOCAL PREVIEW
1. Keep all four files together in this folder.
2. Double-click index.html. It will open in your browser.
3. For the most accurate preview, install the free Visual Studio Code editor.
4. In VS Code, install the “Live Server” extension.
5. Open this folder, right-click index.html, and choose “Open with Live Server.”

WEEKLY BANNER/SERMON UPDATES
1. Open data.js in Notepad, TextEdit, or VS Code.
2. In slides, change the text inside quotation marks. Replace image with a direct image URL.
3. For YouTube, paste only the video ID after youtubeId. Example: for youtube.com/watch?v=ABC123, use ABC123.
4. Set showVideo to true and showAudio to false for YouTube.
5. For audio, place an MP3 in a media folder, set audioFile to media/sermon.mp3, showVideo to false, and showAudio to true.

PRAYER FORM SETUP
1. Create a free account at formspree.io.
2. Create a new form and copy its form endpoint.
3. In index.html, replace https://formspree.io/f/YOUR_FORM_ID with that endpoint.

DONATION SETUP
In index.html, find https://www.paypal.com/donate and replace it with the church's real PayPal, Stripe Payment Link, or giving-platform URL.

CLOUDFLARE PAGES — DIRECT UPLOAD
1. Sign in at dash.cloudflare.com.
2. Open Workers & Pages.
3. Choose Create application, then Pages, then Upload assets/Direct Upload.
4. Enter a project name such as iglesia-de-dios-pharr.
5. Drag this entire unzipped folder into the upload area.
6. Click Deploy site.
7. Cloudflare will give you a free address similar to iglesia-de-dios-pharr.pages.dev.
8. For later changes, open the Pages project, choose Create new deployment, and upload the updated folder again.
