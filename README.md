# Siwach Auto Repairs - Website

This is a modern, premium, pure HTML/CSS/JS website for Siwach Auto Repairs. It features glassmorphism design, glowing interactions, and smooth `IntersectionObserver` scroll animations, completely without heavy frameworks.

## Project Structure

- `index.html` - The main structure of the site, containing all sections (Hero, Services, Why Choose Us, How It Works, Book Appointment, Contact).
- `styles.css` - All custom styling, variables, CSS animations, and layout grids.
- `script.js` - Minimal vanilla JavaScript to handle scroll animations and initialize the Lucide icons.

## Local Development

To view the website locally on your computer, simply double-click the `index.html` file to open it in your browser. 
Alternatively, you can serve the directory using a simple HTTP server (like `npx serve .` or `python -m http.server`).

## Publishing to GitHub Pages

This project is perfectly set up and ready for **GitHub Pages**, as it requires no build steps or bundlers.

**Step 1: Push to GitHub**
1. Create a new empty repository on your GitHub account (e.g., `siwach-auto-website`).
2. Open your terminal in this folder and run:
   ```bash
   git add .
   git commit -m "Initial commit of pure HTML/CSS website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   git push -u origin main
   ```

**Step 2: Enable GitHub Pages**
1. Go to your repository on GitHub.
2. Click on **Settings** > **Pages** (on the left sidebar).
3. Under "Build and deployment", set the **Source** to `Deploy from a branch`.
4. Select your `main` branch and the `/ (root)` folder, then click **Save**.
5. Wait a minute or two, and GitHub will provide you with a live link to your deployed website (usually `https://yourusername.github.io/yourrepository/`)!
