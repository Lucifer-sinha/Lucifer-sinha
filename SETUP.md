# 🚀 Setup Guide — Cyberpunk GitHub Profile

## Quick Start (5 minutes)

### Step 1: Create your profile repository

1. Go to GitHub → **New Repository**
2. Name it **exactly** your GitHub username (e.g., `anshgaur-dev`)
3. Make it **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 2: Upload the files

Copy the entire contents of this folder to your profile repo:

```
YOUR-USERNAME/
├── README.md              ← Main profile (the magic)
├── assets/
│   ├── header.svg         ← Cyberpunk holographic header
│   ├── neural-net.svg     ← Animated neural network divider
│   ├── terminal.svg       ← Animated hacker terminal
│   ├── tech-radar.svg     ← HUD-style skill radar
│   ├── pacman-game.svg    ← Pac-Man game divider
│   ├── wave-divider.svg   ← Animated wave section divider
│   └── footer.svg         ← Animated footer
└── .github/
    └── workflows/
        └── 3d-contrib.yml ← GitHub Action for 3D contribution city
```

### Step 3: Find & Replace YOUR-USERNAME

Open `README.md` and replace **every instance** of `YOUR-USERNAME` with your actual GitHub username.

**Quick way (in VS Code):**
- Press `Ctrl+H`
- Find: `YOUR-USERNAME`
- Replace: `your-actual-username`
- Click "Replace All"

### Step 4: Activate the 3D Contribution City

1. Go to your profile repo on GitHub
2. Click **Actions** tab
3. Find **"Generate 3D Contribution Graph"**
4. Click **"Run workflow"** → **"Run workflow"**
5. Wait ~2 minutes for it to complete
6. In `README.md`, uncomment this line:
   ```html
   <!-- <img src="./profile-3d-contrib/profile-night-rainbow.svg" ... /> -->
   ```
   And remove/comment the placeholder demo image below it.

### Step 5: Add your social links

In the "Connect & Collaborate" section near the bottom, replace the `#` links:

```html
<a href="https://linkedin.com/in/YOUR-LINKEDIN">
<a href="https://YOUR-PORTFOLIO.com">
<a href="mailto:YOUR-EMAIL@gmail.com">
<a href="https://twitter.com/YOUR-TWITTER">
```

---

## 🎨 Customization

### Change your name in the header

Edit `assets/header.svg` and find the text element containing `ANSH GAUR`. Replace it with your name.

### Change the terminal content

Edit `assets/terminal.svg` to modify:
- The username prompt (`ansh@universe`)
- The mission statement
- The skills list
- The philosophy quote

### Adjust colors

The color palette is consistent across all files:

| Variable | Color | Used For |
|----------|-------|----------|
| Primary | `#00F5FF` | Cyan accents, links |
| Secondary | `#8B5CF6` | Purple, AI/ML items |
| Accent | `#FF006E` | Hot pink highlights |
| Success | `#00FF41` | Green, terminal prompts |
| Warning | `#FFD700` | Gold, featured items |
| Background | `#0D1117` | Dark background |
| Text | `#E6EDF3` | Light text |
| Dim | `#7D8590` | Muted text |

### Add/remove technologies from the radar

Edit `assets/tech-radar.svg` and modify the technology dots and labels.

---

## 🔧 Troubleshooting

**Animations not playing?**
- GitHub caches SVGs. Wait a few minutes or add `?v=2` to the image URLs.
- Make sure SVG files are committed to the repo (not just the README).

**3D contribution graph not generating?**
- Go to Settings → Actions → General → Workflow permissions
- Select **"Read and write permissions"**
- Re-run the action

**Stats not showing?**
- The `github-readme-stats` service can be slow. If it shows errors, try again later.
- You can also self-host: https://github.com/anuraghazra/github-readme-stats

**Badges showing "invalid"?**
- Make sure you replaced ALL instances of `YOUR-USERNAME`
- Some badges (followers, stars) require public repos

---

## 📁 File Reference

| File | What It Does | Animation Type |
|------|-------------|----------------|
| `header.svg` | Cyberpunk header with glitch text, grid, particles | CSS @keyframes |
| `neural-net.svg` | Neural network with data pulses | SMIL + CSS |
| `terminal.svg` | Hacker terminal with typing effect | CSS @keyframes |
| `tech-radar.svg` | HUD radar with sweeping scan line | CSS @keyframes |
| `pacman-game.svg` | Pac-Man eating dots with ghosts | CSS @keyframes |
| `wave-divider.svg` | Animated wave section separator | CSS @keyframes |
| `footer.svg` | Footer with equalizer animation | CSS + SMIL |

---

**Enjoy your new profile! ⭐**
