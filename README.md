# Future Scanner 🔮 

The Future Scanner is an interactive, funny web experience where users choose whether they want to see their “future”. Based on their choice, the website triggers animations, scanning effects, and the person gets the surprise based on their choices.

## 🚀 Features
✅ Interactive Popup

The website begins with a popup asking:
“Wanna see your future with AI?”

Two options:

Yes → Start scanning process

No → Play an alternative MP4 video

✋ Handprint Scan Animation (12 seconds)

Displays a glowing handprint.

A scanning bar moves up and down.

A blinking “Scanning your Fingers…” text creates a futuristic effect.

After 12 seconds, the “future reveal” video begins playing automatically.

🎥 Video Playback (Local MP4s)

YES video: plays after scanning animation ends

NO video: plays immediately when a user presses “No”

Both videos are played from local MP4 files (not YouTube embeds).

📂 Project Structure
/project-folder
│── index.html
│── style.css      (optional - currently inline)
│── document_6122847523968129324.mp4   (YES video)
│── no_video.mp4   (NO video)
│── README.md

🔧 How It Works (Logic Flow)
When user clicks YES:

Popup hides

Handprint appears

Scanner animation begins

After 12 seconds:

Scanner disappears

YES video is shown

Video begins playback automatically

When user clicks NO:

Popup hides

NO video (local MP4) appears

Video plays immediately

🛠 Technologies Used

HTML5

CSS3 (embedded styles)

JavaScript

Local video playback using <video> elements
