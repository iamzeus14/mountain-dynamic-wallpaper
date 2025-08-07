# 🏔️ Mountain Dynamic Wallpaper for GNOME

A beautiful time-based dynamic wallpaper for Linux desktops (like GNOME), featuring smooth transitions between mountain images throughout the day.

---

## 📁 Files Included

- `mountain-fixed.xml` — The XML file that defines image transitions
- `1.jpg` to `7.jpg` — Mountain wallpapers used throughout the day

---

## 🛠️ How to Install

### 📦 Step-by-Step (GNOME Desktop)

1. **Clone this repository:**

```bash
git clone https://github.com/iamzeus14/mountain-dynamic-wallpaper.git


2. ** Create a local backgrounds folder:**

mkdir -p ~/.local/share/backgrounds/mountain


3.**Copy all files into that folder:**

cp mountain-dynamic-wallpaper/* ~/.local/share/backgrounds/mountain/


4.Apply the dynamic wallpaper:

gsettings set org.gnome.desktop.background picture-uri "file://$HOME/.local/share/backgrounds/mountain/mountain-fixed.xml"

                                      OR
YOU CAN DIRECTLY APPLY THIS FROM SETTINGS 

##🧪 Compatibility ##

✅ Works on GNOME

⚠️ May not work on KDE/XFCE without external tools


🧰 Credits

Made using Dynamic Wallpaper Editor

Wallpaper by @iamzeus14


---

### ✅ Next Step

Now save it:

```bash
nano README.md
