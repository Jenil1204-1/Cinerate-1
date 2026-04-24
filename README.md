# 🎬 CineRate — Movie Review & Rating Analysis Website

> A fully interactive movie review platform with rating calculation, image slider, show/hide reviews, and a contact form. Designed in Figma and deployed via Google Sites embed.

---

## 📌 Project Information

| Field | Details |
|---|---|
| **Project Title** | Movie Review & Rating Analysis Website |
| **Subject** | Web Design & Development |
| **Platform** | Google Sites (via HTML Embed) |
| **Design Tool** | Figma |
| **Technology** | HTML5, CSS3, Vanilla JavaScript |
| **Author** | Jenil — KU2507U0548 |
| **University** | Karnavati University |

---

## 🎯 Objective

To design and develop a movie review platform that allows users to browse movies, read and hide reviews, calculate ratings using an interactive calculator, submit their own reviews, and contact the platform — all within a visually rich, cinema-themed interface.

---

## 🗂️ Pages

| Page | Description |
|---|---|
| **Home** | Hero banner, image slider (3 featured films), trending movies grid, buttons showcase, about strip |
| **Movies** | Full movie grid (12 films), genre filter buttons, rating badges, per-card action buttons |
| **Reviews** | Rating calculator with sliders, submit review form, user review cards with show/hide |
| **Contact** | Contact form, info cards (email, location, response time), social links |

---

## 🖱️ Required UI Buttons (All 5 Implemented)

| Button | Location | Function |
|---|---|---|
| **View Review** | Movie cards, Review cards | Shows the hidden review text |
| **Hide Review** | Movie cards, Review cards | Hides the review text |
| **Calculate Rating** | Reviews page, Movie cards | Computes average from 5 category sliders |
| **Submit Review** | Reviews page form | Adds a new review card dynamically to the page |
| **Contact** | Navbar, Home page, Contact form | Navigates to Contact page / submits the form |

---

## ⚙️ Functional Features

### 🖼️ Image Slider
- 3 featured movie slides with auto-play (4 seconds interval)
- Left / Right arrow navigation
- Dot indicator navigation
- Auto-play pauses on mouse hover

### 👁️ Show / Hide Reviews
- Each review card has independent View Review and Hide Review buttons
- Review text toggles visibility without page reload
- Toast notification confirms the action

### 🧮 Rating Calculator
- 5 category sliders: Story, Acting, Direction, Visuals, Music
- Each slider ranges from 1–10
- Live average is recalculated on every slider move
- Final result displayed in large format with a Calculate button

### ✍️ Submit Review (Dynamic)
- User fills Movie Name, Their Name, Review text, and Star Rating
- On submit, a new review card is injected at the top of the reviews list
- Form clears after successful submission
- Validation ensures no empty fields

### 📩 Contact Form
- Fields: Full Name, Email, Subject, Message
- Validation on submit
- Toast confirmation on success

### 🔍 Genre Filter (Movies Page)
- Filter buttons: All, Action, Drama, Sci-Fi, Comedy, Crime
- Movies grid re-renders instantly based on selected genre

---

## 🗃️ File Structure

```
cinerate-project/
│
├── cinerate-website.html     ← Main website file (single-file app)
├── README.md                 ← This file
```

> The entire site is a **single self-contained HTML file** — no external dependencies beyond Google Fonts (Bebas Neue + DM Sans loaded via CDN).

---

## 🚀 How to Deploy on Google Sites

Google Sites does not support direct code editing, but it supports embedding external URLs as iframes. Follow these steps:

### Step 1 — Host the HTML file on GitHub Pages (Free)

1. Create a free account at [github.com](https://github.com)
2. Click **New Repository** → Name it `cinerate`
3. Upload `cinerate-website.html` → rename it to `index.html`
4. Go to **Settings → Pages → Branch: main → Save**
5. Wait ~2 minutes → Your live URL: `https://yourusername.github.io/cinerate`

### Step 2 — Embed into Google Sites

1. Open [sites.google.com](https://sites.google.com) → Create a new site
2. On any page, click **Insert → Embed**
3. Select the **By URL** tab
4. Paste your GitHub Pages URL (e.g. `https://yourusername.github.io/cinerate`)
5. Click **Insert** → Resize the embed block to full width
6. Click **Publish** (top right corner)

✅ Your CineRate site is now fully visible and functional inside Google Sites.

---

## ⚠️ Important Note on Google Sites Limitations

| Method | What Works |
|---|---|
| ✅ Embed via URL (GitHub Pages) | Full JS, CSS, animations, all buttons |
| ❌ Paste raw HTML into embed box | JS is stripped, buttons won't work |

Always use the **hosted URL method** for full functionality.

---

## 🎨 Design Details

| Element | Choice |
|---|---|
| **Color Scheme** | Dark cinema theme — `#080810` background, `#E50914` red accent |
| **Fonts** | Bebas Neue (headings) + DM Sans (body) |
| **Card Style** | Dark glass cards with subtle border and hover lift |
| **Rating Badge** | Amber (`#F5A623`) pill badges on poster images |
| **Buttons** | 5 distinct styles — Red, Amber, Green, Blue, Ghost |
| **Slider** | CSS transition with JS-controlled transform |
| **Figma Design** | [View Figma File](https://www.figma.com/design/oBVaCNfMV7vphiupvt4ney) |

---

## 🧪 Testing Checklist

- [ ] Image slider auto-plays and arrows work
- [ ] Slider dots navigate correctly
- [ ] All 4 nav links navigate to correct pages
- [ ] Genre filters show correct movies
- [ ] View Review button makes text visible
- [ ] Hide Review button hides text
- [ ] Rating calculator sliders update average live
- [ ] Calculate Rating button shows toast
- [ ] Submit Review form validates empty fields
- [ ] Submitted review appears at top of list
- [ ] Contact form validates and shows confirmation
- [ ] All 5 required buttons present and functional
- [ ] Site renders correctly inside Google Sites embed

---

## 📚 Technologies Used

- **HTML5** — Semantic page structure
- **CSS3** — Custom properties, Grid, Flexbox, transitions, animations
- **Vanilla JavaScript** — DOM manipulation, event handling, dynamic rendering
- **Google Fonts CDN** — Bebas Neue, DM Sans
- **Figma** — UI/UX wireframe and design prototype

---

## 📄 License

This project is submitted as an academic assignment for Karnavati University. All movie titles and related content are referenced for educational purposes only.
