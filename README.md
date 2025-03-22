# YamCam Viewer

A simple and elegant web-based tool to automatically refresh and view images from a YamCam stream. Perfect for monitoring YamCam feeds that only provide static image URLs.

---

## Features ✨
- **Auto-Refresh**: Automatically refreshes the image at a user-defined interval (1–600 seconds).
- **Force Refresh**: Manually refresh the image anytime.
- **Fullscreen Mode**: View the image in fullscreen for better visibility.
- **Image Counter**: Tracks the number of images loaded.
- **Simple UI**: Clean and intuitive interface.
- **Cross-Platform**: Works on any device with a modern web browser.

---

## How to Use 🛠️

### Step 1: Get the YamCam Image URL
1. Open your YamCam stream in a browser.
2. If the stream only shows a static image (not a video), **right-click** the image and select **"Copy Image Address"** or **"Copy Image URL"**.
   - Example URL: `http://127.0.0.1:8888/out.jpg`

### Step 2: Use the YamCam Viewer
1. Open the [YamCam Viewer](https://your-github-username.github.io/yamcam-viewer) (replace with your GitHub Pages link).
2. Paste the copied URL into the **"Enter YamCam image URL"** field.
3. Set the refresh interval (in seconds) in the **"Refresh interval"** field.
4. Click **Start** to begin auto-refreshing the image.

---

## Example URL
If your YamCam stream provides a static image URL like this:
```
http://174.161.13.61:8888/out.jpg
```
Paste it into the tool, and it will automatically refresh the image at your specified interval.

---

## Features in Detail

### 1. **Auto-Refresh**
- The tool fetches the image from the provided URL at regular intervals.
- You can set the interval between **1 and 600 seconds**.

### 2. **Force Refresh**
- Use the **Force Refresh** button to manually load the latest image without waiting for the next interval.

### 3. **Fullscreen Mode**
- Click the **Full Screen** button to view the image in fullscreen mode.
- Press `Esc` or click the button again to exit fullscreen.

### 4. **Image Counter**
- The tool keeps track of the number of images loaded.
- The counter is displayed in the bottom-right corner of the image container.

---

## Keyboard Shortcuts ⌨️
- **Enter**: Start auto-refresh (if not already running).
- **Escape**: Stop auto-refresh or exit fullscreen mode.

---

## Why Use This Tool?
- **No Browser Caching**: The tool forces the browser to fetch a fresh image every time by adding a unique timestamp to the URL.
- **Lightweight**: No heavy libraries or frameworks—just pure HTML, CSS, and JavaScript.
- **Customizable**: Set your preferred refresh rate and enjoy seamless monitoring.

---

## Deployment
You can easily deploy this tool:
1. **GitHub Pages**: Host it for free using GitHub Pages.
   - Push the code to a GitHub repository.
   - Go to **Settings > Pages** and enable GitHub Pages for the repository.
2. **Local Use**: Simply open the `index.html` file in your browser.

---

## Contributing
Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

Enjoy using the YamCam Viewer! If you have any questions or feedback, feel free to open an issue on GitHub.

---
