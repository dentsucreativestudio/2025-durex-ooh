# Durex OOH Previewer

This project serves as a visual preview tool for Durex Out-Of-Home (OOH) creative assets. It randomly displays images from the `/images` folder inside a simulated digital billboard format.

## 🔗 Live Preview

View the live preview here:  
👉 [https://dentsucreativestudio.github.io/2025-durex-ooh/previewer.html](https://dentsucreativestudio.github.io/2025-durex-ooh/previewer.html)

---

## 📁 Uploading Images

To display new images in the previewer:

1. Go to the `images` folder in the repo:
   👉 [https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images](https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images)

2. Click the **“Add file”** button → **“Upload files”**.

3. Drag and drop your images (JPG). Keep you image below 2Mb file size.

4. Click **“Commit changes”** to upload them.

---

## 🗑️ Deleting Images

To remove an image:

1. Visit the `images` folder:  
   👉 [https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images](https://github.com/dentsucreativestudio/2025-durex-ooh/tree/main/images)

2. Click on the image you want to delete.

3. In the top-right corner, click the **trash can icon** 🗑️.

4. Optionally edit the commit message.

5. Click **“Commit changes”** to finalize.

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
