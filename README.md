# 🎮 Gaming Site

A modern, responsive gaming e-commerce website built with **React** and **Vite**. The site showcases a game store experience with a home page, shop with category filtering, individual product detail pages, and a contact page with an embedded map.

## 📸 Screenshots

### Home Page
![Home Page](https://github.com/ALI-RAZA816/Gamingsite/blob/d8150d269d66c11fdd3a42d8486f28676727e648/gamesite_screenshot1.PNG)

### Shop Page
![Shop Page](https://github.com/ALI-RAZA816/Gamingsite/blob/d8150d269d66c11fdd3a42d8486f28676727e648/gamesite_screenshot2.PNG)

### Product Page
![Product Page](https://github.com/ALI-RAZA816/Gamingsite/blob/d8150d269d66c11fdd3a42d8486f28676727e648/gamesite_screenshot3.PNG)

## ✨ Features

- **Home Page** – Hero banner, top games, most-played games, category browsing, and a shop preview section
- **Shop Page** – Full catalog with category filters (Show All, Adventure, Strategy, Racing) and pagination
- **Product Details Page** – Game hero section, game intro, and a tabbed Description/Review section
- **Contact Page** – Contact hero section with an embedded map
- **Responsive Navigation** – Sticky header on scroll with an animated mobile menu
- **Client-Side Routing** – Smooth navigation between pages without full page reloads

## 🛠️ Tech Stack

- **[React 19](https://react.dev/)** – UI library
- **[Vite](https://vitejs.dev/)** – Build tool and dev server
- **[React Router DOM](https://reactrouter.com/)** – Client-side routing
- **[React Icons](https://react-icons.github.io/react-icons/)** – Icon library
- **CSS Modules** – Scoped component styling
- **ESLint** – Code linting

## 📁 Project Structure

```
Gamingsite/
├── public/
│   └── assets/
│       └── images/           # Static images (logo, icons, etc.)
├── src/
│   ├── Component/
│   │   ├── HomePage/         # Header, HeroSection, TopGames, MostPlayed,
│   │   │                       Categories, Shop, Footer, HomePageContainer
│   │   ├── ShopPage/         # ShopHeroSection, MenusGames, Portion1-4, PageNumber
│   │   ├── ProductPage/      # ProductHero, GameIntro, Description, Paragraph1
│   │   └── ContactPage/      # ContactHero, MapSection
│   ├── App.jsx                # Root component
│   ├── App.css                # Global styles
│   └── main.jsx                # App entry point
├── index.html
├── vite.config.js
└── package.json
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes bundled with Node.js)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd Gamingsite
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Available Scripts

| Command           | Description                              |
|--------------------|-------------------------------------------|
| `npm run dev`      | Starts the Vite development server        |
| `npm run build`    | Builds the app for production             |
| `npm run preview`  | Previews the production build locally     |
| `npm run lint`     | Runs ESLint to check code quality         |

## 🗺️ Routes

| Route       | Page              |
|-------------|-------------------|
| `/`         | Home              |
| `/shop`     | Shop / Catalog    |
| `/product`  | Product Details   |
| `/contact`  | Contact Us        |

## 📌 Roadmap / Possible Improvements

- Connect to a real backend/API for product data
- Add a shopping cart and checkout flow
- Add user authentication (Sign In / Sign Up)
- Add search functionality
- Migrate to React Router v6+ (project currently uses v5 syntax)

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, create a feature branch, and open a pull request.

## 📄 License

This project is open source and available for personal or educational use. Add a license file (e.g., MIT) if you'd like to formally license it.