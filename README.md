

# the iready thing

A JavaScript hack for I-Ready that adds a UI with button clicking automation thing, shutting some AI voice up, and a calculator. (Calculator doesn't pop out.)
## Features

- **Please shut up** – Mutes audio and speeds up spoken dialogue so you can get to questions faster.
- **Next** – Automatically clicks the Next/Continue button when possible.
- **Nah, I'd win** – Forces navigation to the next part by unlocking and clicking the forward button.
- **5 seconds not wasted** – Skips instructional animations and example videos.
- **Quick calculator** – Built-in calculator for quick calculations.

## Setup 
# PC
1. Open your browser's Developer Tools on I-Ready:
   - **Chrome / Edge:** `Cmd + Option + J` on Mac or `Ctrl + Shift + J` on Windows.
   - **Firefox:** `Cmd + Option + K` on Mac or `Ctrl + Shift + K` on Windows.
2. Select the **Console** tab.
3. Paste the copied JavaScript (`main.js`) into the console and press Enter. (if it doesn't work, type "allow pasting")
4. The floating control panel should appear on the page.
   
# Mobile (assuming you're on the chrome app)
1. Click the three dots in the top right.
2. Go to "Bookmarks".
3. Create a new bookmark with the URL set to the contents of `bookmarklet.js`. (copy & paste)
4. Go on I-Ready and use the bookmark.
5. The floating control panel should appear on the page.

## Controls

| Control | Description |
|---|---|
| Please shut up | Mutes and speeds up audio and speech |
| Next | Automatically advances through available sections |
| Nah, I'd win | Manually forces the next section (fire) |
| 5 seconds not wasted | Skips videos and animations |
| Quick calculator | Performs calculations inside the panel |

## Interface

The script adds a draggable floating panel directly into the page.

- Minimize the panel into its header using the `-` button.
- Close the panel using the `X` button.
- Drag the header to reposition it.
- The status indicator displays... stuff idk.

## Notes

- Automatic next does not click when an answer is still required or you get something incorrect.
- Some features may behave differently depending on the lesson and page structure. (No reading support yet, but stuff half works)
- The script relies on I-Ready's page elements, so website updates may break the script.

---

**the iready thing**
