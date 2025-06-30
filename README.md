# 🛍️ Frontend Mentor - Product Preview Card Component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) on Frontend Mentor.
It's a small, focused project aimed at building a clean, responsive product card layout using Tailwind CSS with a semantic and scalable structure.

## 📌 Summary

In this challenge, I built a responsive product preview card that includes:

- A featured product image

- Product category and title

- Product description

- Original and discounted prices

- Call-to-action button

The project served as a practice to improve my CSS utility usage, HTML semantics, and responsiveness.

## 📸 Screenshots

### 🖥️ Desktop view

![](./assets/design/desktop-preview.jpg)

### 📱 Mobile view

![](./assets/images/image-product-mobile.jpg)

## 🌐 Live Preview

- 🔗 **Live web page**: [https://michaeljara905.github.io/Recipe-page-main/](https://michaeljara905.github.io/Recipe-page-main/)
- 💻 **Source code**: [https://github.com/MichaelJara905/Recipe-page-main.git](https://github.com/MichaelJara905/Recipe-page-main.git)


## 🛠️ Technology Stack

- Semantic HTML5
- Tailwind CSS
- Custom fonts (Fraunces & Montserrat, self-hosted)
- Responsive design (mobile-first approach)

## My workflow
### 📁 Project Setup

input.css is used to import:

  - @import "tailwindcss";
  - Custom fonts via @font-face
  - CSS variables inside @theme for colors and fonts

Compiled with Tailwind CLI using:

    npx tailwindcss -i ./input.css -o ./output.css --watch

Organized assets inside /public/fonts and /images

### 🧱 Structure and Layout

- Semantic HTML tags like <head>, <main>, and <button>
- Layout built entirely with Tailwind utility classes (grid, rounded, shadow, space-y, etc.)

### 🎨 Styling

Custom HSL-based CSS variables:

    --color-Green-500: hsl(158, 36%, 37%);
    --color-Green-700: hsl(158, 42%, 18%);
    --color-Black: hsl(212, 21%, 14%);
    --color-Grey: hsl(228, 12%, 48%);
    --color-Cream: hsl(30, 38%, 92%);
    --color-White: hsl(0, 0%, 100%);

Fonts used:

    --font-montserrat: 'Montserrat', sans-serif, system-ui;
    --font-fraunces: 'Fraunces', serif, system-ui;

### 🚀 Deployment

- Project deployed using GitHub Pages for easy public access on any device.

## 📚 What I Learned

- How to integrate variable fonts (.woff2) and host them locally
- Defining reusable design tokens via @theme in Tailwind
- Using utility-first classes for pixel-perfect responsive layouts

## 🔍 What I Would Do Differently

- Add transitions and hover animations to the button
- Refactor layout into components for use with React or Vue.
- Convert layout into a reusable component for a framework (React/Vue/Svelte)
- Add accessibility features like ARIA labels

## 👤 Author

- Frontend Mentor - [@MichaelJara905](https://www.frontendmentor.io/profile/MichaelJara905)
- Instagram - [@jaramillo_maicol_0](https://instagram.com/jaramillo_maicol_0)
- GitHub - [@MichaelJara905](https://github.com/MichaelJara905)

## ✅ Conclusion

This challenge was a quick yet effective way to reinforce layout precision, semantic HTML, and Tailwind configuration.
Projects like these continue to strengthen my frontend development foundation.