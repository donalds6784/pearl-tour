# 🌍 Pearl Tour – Collaborative Landing Page Project

Welcome to the Practical Developers group project! This repository is part of our hands-on learning initiative, designed to simulate real-world open source workflows using Git and GitHub.

We’re building a responsive, accessible, and visually engaging **adventure-themed landing page** using semantic HTML and modular CSS. This project helps us practice frontend fundamentals while learning how to collaborate effectively as developers.

---

## 📄 Project Overview

# 🌍 Pearl Tour — Collaborative Landing Page Project

Welcome to the Practical Developers group project. This repository contains an adventure-themed landing page used to practice responsive, accessible, and semantic frontend development while collaborating with others.

---

## 📄 Project overview

The landing page will include:

-   A hero section with background imagery and a call-to-action
-   Feature highlights with icons and descriptions
-   A gallery or showcase section
-   A footer with contact info and social links

---

## 🎯 Learning objectives

-   Apply semantic HTML5 structure
-   Use CSS Flexbox and Grid for layout
-   Practice responsive design with media queries
-   Collaborate using Git and GitHub workflows
-   Follow component-based and BEM-friendly CSS patterns

---

## 🛠 Setup

1. Fork this repository to your GitHub account.
2. Clone your fork locally:

```bash
git clone https://github.com/your-username/pearl-tour.git
cd pearl-tour
```

3. Create a branch for your task:

```bash
git checkout -b feature/your-task-name
```

4. Make changes, commit with clear messages, push to your fork, and open a pull request:

```bash
git add .
git commit -m "Add responsive gallery section"
git push origin feature/your-task-name
```

---

## 🧱 BEM convention (quick guide)

BEM = Block, Element, Modifier. It helps keep class names predictable and components reusable.

| Part     | Description                        | Example                                 |
| -------- | ---------------------------------- | --------------------------------------- |
| Block    | Standalone component               | `.card`, `.nav`, `.hero`                |
| Element  | Child part of a block              | `.card__title`, `.nav__item`            |
| Modifier | Variation/state of a block/element | `.card--featured`, `.nav__item--active` |

### Syntax examples

```css
.block {
	/* base block */
}
.block__element {
	/* child element */
}
.block--modifier {
	/* variation */
}
.block__element--modifier {
	/* element variation */
}
```

### HTML + CSS example

```html
<div class="card card--featured">
	<h2 class="card__title card__title--large">Welcome</h2>
	<p class="card__description">This is a featured card.</p>
	<a href="#" class="card__button card__button--secondary">Learn More</a>
</div>
```

```css
.card {
	border: 1px solid #ccc;
	padding: 1rem;
}
.card--featured {
	border-color: gold;
}
.card__title {
	font-size: 1.2rem;
}
.card__title--large {
	font-size: 2rem;
}
.card__button--secondary {
	background-color: #7f8c8d;
}
```

---

## ✅ Code standards & requirements

Follow these to keep contributions consistent and review-friendly:

1. Use semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`).
2. Follow BEM naming for CSS classes.
3. Keep CSS modular — separate concerns by component when practical.
4. Use CSS variables in `:root` for colors, spacing, and typography scale.

Example CSS variables:

```css
:root {
	--primary-color: #1e90ff;
	--font-size-base: 1rem;
}
```

---

## 📌 Tasks you can contribute to

-   [ ] Build the hero section with background image and CTA
-   [ ] Create the feature highlights section with icons
-   [ ] Implement the gallery layout using Flexbox or Grid
-   [ ] Style the footer and add social media links
-   [ ] Improve accessibility (alt text, ARIA roles)
-   [ ] Refactor CSS for responsiveness
-   [ ] Add transitions and hover effects

---

## 🙋 How to join

1. Comment on the relevant GitHub issue and assign yourself (or ask to be assigned).
2. Create a branch and implement a focused change (one component/section per PR).
3. Push your branch and open a pull request with a clear description and screenshots if applicable.

---

## 🧑‍🤝‍🧑 Collaboration notes

-   Review fellow contributors' PRs and leave constructive feedback.
-   Use GitHub Discussions or the project chat for questions.
-   Weekly integration sessions will be scheduled to merge and test contributions.

---

## 📜 License

This project is licensed under the MIT License — see the `LICENSE` file for details.
