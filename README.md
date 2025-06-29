
# 🎨 Muse-AI-um

**Muse-AI-um** is an immersive digital museum experience that blends **artificial intelligence** with **human creativity**. This web app lets users explore exhibitions, generate AI art, and discover cultural and historical artworks—all in one beautifully crafted React application.

---

## 🚀 Live Features

### ✨ Highlights
- 🖼️ 1,000+ AI Artworks  
- 🌍 Global Visitors  
- 🧠 AI Artists Showcase  
- 🎪 Real-Time Exhibitions  

---

## 🧩 Project Structure

```
src/
├── components/
│   ├── About.jsx
│   ├── AiArtCreator.jsx
│   ├── ArtWorkDetail.jsx
│   ├── AuthModal.jsx
│   ├── Exhibitions.jsx
│   ├── Footer.jsx
│   ├── Gallery.jsx
│   ├── Header.jsx
│   ├── Hero.jsx
├── App.jsx
├── main.jsx
├── App.css
├── index.css
public/
  └── assets/
      └── react.svg
```

---

## 🧠 Key Components

### `App.jsx`
- Main application layout with routing of major sections:
  - Header, Hero, Exhibitions, Gallery, About, Footer
  - `AuthModal` for login/signup
  - `ArtworkDetail` for image popups

### `Header.jsx`
- Responsive navigation bar  
- User profile dropdown and "Visit Now" authentication modal

### `Hero.jsx`
- Landing hero section with animated modal popups:
  - AI-Generated Art  
  - Cultural Impact  
  - Future Vision

### `AiArtCreator.jsx`
- Interactive canvas using generative algorithms
- Style and palette customization
- Download, save, and share functionality

### `Exhibitions.jsx`
- Displays featured and ongoing exhibitions
- Each exhibition includes date, location, image, description

### `Gallery.jsx`
- Displays a categorized grid of artworks:
  - Paintings, Sculptures, Wonders, Cultural Dance, Photography
- Hover preview + click to open full artwork detail

### `ArtWorkDetail.jsx`
- Popup modal showing:
  - Artwork image, description, views, likes
  - Like, Share, and Download buttons

### `AuthModal.jsx`
- Email-based login/signup modal
- Frontend validation
- Avatar generation and mock authentication

### `About.jsx`
- Project mission, stats, and unique value propositions

### `Footer.jsx`
- Contact info, newsletter subscription, and social icons

---

## 🎨 Styles and Assets

### `App.css`
- Global layout and hover effects  
- Logo spin animation

### `index.css`
- TailwindCSS base + custom animations:
  - Floating objects
  - Smooth scroll
  - Gradient backgrounds  
- Custom scrollbar and selection styling

---

## ⚙️ Setup & Run

### 🛠 Installation

```bash
npm install
```

### ▶️ Start Dev Server

```bash
npm run dev
```

### 📦 Build for Production

```bash
npm run build
```

---

## 🧪 Tech Stack

- **React 18**
- **TailwindCSS**
- **Lucide Icons**
- **Canvas API**
- **JSX-based modal & routing**
- **Responsive Design** with full mobile support

---

## 📧 Contact Info

- 📍 Location: Machilipatnam, Andhra Pradesh  
- 📬 Email: TheInnovators1819@gmail.com  
- 🔗 LinkedIn, Twitter, Facebook, YouTube (icon links in footer)
