# 🍽️ Restaurant Static Website

Welcome to the **Restaurant Static Website** repository! This project is a fully responsive, modern, and lightweight static website template for restaurants, built using [Hugo Scroll](https://github.com/zjedi/hugo-scroll), a theme for the Hugo static site generator. If you are looking to create an online presence for a restaurant, cafe, or food-related business, this template provides a great starting point.

## 🌟 Features

- 📱 **Responsive Design** – Works perfectly on desktops, tablets, and mobile devices.
- 🎨 **Modern UI/UX** – Elegant and visually appealing layout.
- ⚡ **Fast and Lightweight** – Optimized for performance.
- 🔗 **Easy Navigation** – Smooth scrolling and simple menu structure.
- 📍 **Google Maps Integration** – Show your restaurant location easily.
- 📞 **Contact Form** – Simple form for customer inquiries (requires a backend to process messages).
- 📷 **Image Gallery** – Showcase delicious meals with a stunning gallery.
- 🔥 **SEO Optimized** – Basic SEO best practices implemented.

## 📂 Project Structure

This project follows a **two-folder approach**, separating the Hugo source files from the generated public website files.

```
restaurant-website/
│── site/               # Hugo source files
│   ├── config.toml     # Hugo configuration file
│   ├── content/        # Markdown content files
│   ├── static/         # Static assets (CSS, images, etc.)
│   ├── themes/scroll/  # Hugo Scroll theme
│── public/             # Generated static website (output from Hugo build)
│── README.md           # Documentation (this file)
│── LICENSE             # License file
```

## 🚀 Getting Started

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/restaurant-website.git
   ```

2. **Navigate to the Project Directory**
   ```sh
   cd restaurant-website/site
   ```

3. **Run Hugo Server**
   ```sh
   hugo server -D
   ```

4. Open your browser and go to `http://localhost:1313/` to preview the site.

## 🌐 Deployment

You can easily deploy this website using GitHub Pages:

1. Build the static website files:
   ```sh
   hugo --minify -d ../public
   ```
2. Push the `public/` folder to the `gh-pages` branch.
3. Go to **Settings > Pages** in your repository.
4. Under "Source," select `gh-pages` branch.
5. Click "Save" and wait a few minutes for the site to go live.

Alternatively, you can host it on Netlify, Vercel, or any other static hosting service.

## 🎨 Customization

- **Logo & Branding:** Replace the logo and update colors in `site/static/css/custom.css`.
- **Menu Items:** Edit `site/content/menu.md` to add/update food items.
- **Contact Form:** If using a backend, configure it in `site/content/contact.md`.
- **Images:** Replace images in the `site/static/images/` folder with your own.

## 🛠️ Technologies Used

- [Hugo](https://gohugo.io/)
- [Hugo Scroll Theme](https://github.com/zjedi/hugo-scroll)
- HTML5
- CSS3
- JavaScript

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! Feel free to fork this repo and submit a pull request.

## 📧 Contact

For any questions or suggestions, feel free to reach out!

---

🚀 **Enjoy building your restaurant website!** 🍕🍔🥗

