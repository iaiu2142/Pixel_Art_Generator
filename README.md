# 🎨 Pixel Art Generator  

Turn your photos into retro-style **pixel art** 🎮 using Python & Google Colab.  
This project transforms any image into pixelated artwork with customizable **pixel size**, **color palette**, **dithering**, and **outlines**.

---

## ✨ Features
- 📂 Upload any image (JPG/PNG)  
- 🎛 Control pixel size (how chunky the blocks look)  
- 🎨 Reduce colors with K-means clustering  
- 🎚 Optional **Floyd–Steinberg dithering** for smooth gradients  
- ✏️ Optional outlines for sharper details  
- 💾 Download your pixel-art result as PNG  

---

## 🚀 Quick Start (Google Colab)
1. Open the notebook in **Google Colab**  
2. Run all cells  
3. Upload your image when prompted  
4. Get instant **Original vs Pixel Art** output  
5. Download your final PNG  

---

## ⚙️ Parameters
You can tweak the following values inside the notebook:

- `PIXEL_SIZE` → Bigger = larger chunky pixels, smaller = more detail  
- `PALETTE_K` → Number of colors in the palette (lower = simpler, more retro)  
- `USE_DITHER` → Enable/disable Floyd–Steinberg dithering  
- `ADD_OUTLINES` → Overlay outlines to highlight edges  
- `OUTLINE_STRENGTH` → Control how strong the outlines appear  
## Example 📸
| Original                           | Pixelated                            |
| ---------------------------------- | ------------------------------------ |
| ![original](examples/original.jpg) | ![pixelated](examples/pixel_art.png) |
