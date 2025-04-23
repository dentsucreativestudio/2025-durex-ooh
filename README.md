# Durex OOH Previewer

This project serves as a visual preview tool for Durex Out-Of-Home (OOH) creative assets. It randomly displays images from the `/images` folder inside a simulated digital billboard format.

## 🔗 Live Preview

View the live preview here:  
👉 [https://dentsucreativestudio.github.io/2025-durex-ooh/previewer.html](https://dentsucreativestudio.github.io/2025-durex-ooh/previewer.html)

---

## 📂 Uploading New Images

To add or update images in the previewer:

1. Go to the `images/` folder in the repository:  
   👉 [https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images](https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images)
2. Click **Add file** > **Upload files**.
3. Drag and drop your JPG files.
4. Click **Commit changes** at the bottom.

✅ Supported formats: `.jpg`, `.jpeg`, // please try to keep the images below than 2Mb filesize.

New images will be automatically picked up by the previewer when you reload the page.

---

## 🛠 How It Works

- The `previewer.html` page uses the GitHub API to fetch all image files inside the `/images` folder.
- One image is chosen at random each time the page loads.
- The image is scaled to fit a simulated vertical screen (1080x1920px).
- Fallback support is included in case an image fails to load.

---

## 📎 Notes

- Ensure your images are optimized for web use.
- GitHub Pages automatically serves the latest version when the repo is updated.

---

Made with ❤️ by the Dentsu Creative Studio team.
