# AnimeVerse

![AnimeVerse Screenshot](/public/animeverse.png.png)

AnimeVerse is a Next.js 14 server-side application designed to provide an immersive experience for anime enthusiasts. Featuring infinite scroll and dynamic animations powered by Framer Motion, AnimeVerse delivers a seamless way to discover and explore anime.

## Features

- **Infinite Scroll**: Effortlessly load more anime cards as you scroll down the page.
- **Dynamic Animations**: Smooth animations for anime cards, enhancing the user experience.
- **Server Actions**: Optimized server-side functionality with Next.js 14.
- **Responsive Design**: A fully responsive layout using Tailwind CSS.

## Tech Stack

- **Next.js 14**: Server-side rendering and server actions.
- **Framer Motion**: For fluid animations.
- **Tailwind CSS**: Modern and responsive styling.
- **Intersection Observer**: Efficient infinite scroll implementation.

## Installation

Follow these steps to run AnimeVerse locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/adlichalbi/animeverse.git
   ```

2. Navigate to the project directory:

   ```bash
   cd animeverse
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Usage

- **Discover Anime**: Browse through a collection of anime cards.
- **Infinite Scroll**: Scroll down to load more content without refreshing the page.

## Folder Structure

```
.
├── app
│   ├── _data.ts         # Data fetching utilities
│   ├── action.tsx       # Server actions and API handlers
│   ├── favicon.ico      # Favicon for the website
│   ├── globals.css      # Global styles
│   ├── layout.tsx       # Layout wrapper
│   └── page.tsx         # Main page component
├── components
│   ├── AnimeCard.tsx    # Anime card component
│   ├── Footer.tsx       # Footer component
│   ├── Hero.tsx         # Hero section component
│   ├── LoadMore.tsx     # Infinite scroll component
│   └── Motion.tsx       # Framer Motion wrapper
├── public
│   ├── logo.svg         # Logo and other assets
│   └── various .png/.svg files for social media and UI elements
└── README.md            # Project documentation
```

## Demo

![Scrolling through AnimeVerse](/public/demo.gif.gif)

## Contributions

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## API Provider

Anime data is sourced from the [Shikimori API](https://shikimori.one), ensuring accurate and up-to-date anime information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy scrolling through AnimeVerse! 🌟
