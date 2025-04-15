# 🎨 Meme Generator

Create your own memes in the browser with this easy-to-use **JavaScript Meme Generator**. Upload an image, add your own top and bottom text, and download the result as a PNG — all without leaving the page!

---

## 🚀 Features

- 🖼 Upload any image from your device
- ✍️ Add custom top and bottom text
- 🎨 Styled with bold **Impact** font, white fill, and black stroke — classic meme style!
- 📥 Download your meme with one click

---

## 💻 How It Works

### Step-by-step:

1. **Upload Image**  
   Click the **Browse** button to select an image from your computer.

2. **Enter Text**  
   Type in your meme’s **Top Text** and **Bottom Text** in the input fields.

3. **Generate Meme**  
   Click the **Generate Meme** button to preview your meme on the canvas.

4. **Download Meme**  
   Click **Download Meme** to save your meme as a `.png` file.

---

## 🧠 Tech Stack

- **HTML5 Canvas API**
- **Vanilla JavaScript**
- **FileReader API**
- No frameworks or libraries — just pure JavaScript fun!

---

## 📂 File Overview

```plaintext
index.html       # Contains the HTML structure with canvas and input fields
style.css        # (Optional) Your styling for layout & buttons
script.js        # Full meme generator logic
README.md        # This file!
```

---

## 🔧 Code Highlights

- `FileReader()` handles the image upload and renders it on the canvas
- `CanvasRenderingContext2D` draws the image and text with styling
- Download functionality uses `toDataURL()` and an anchor tag

---

## 📝 Example Code Snippet

```js
ctx.font = '30px Impact';
ctx.fillStyle = 'white';
ctx.strokeStyle = 'black';
ctx.textAlign = 'center';
ctx.fillText(topText, canvas.width / 2, 50);
ctx.strokeText(topText, canvas.width / 2, 50);
```

---

## 🧩 Future Ideas

- Mobile-friendly layout
- Text resizing and positioning options
- Multiple fonts or color customization
- Meme templates gallery

---

## 👩‍💻 Created By

Made with memes and JavaScript ❤️  
*Johanna Schnell* — [LinkedIn](https://www.linkedin.com/in/johanna-e-schnell/)
