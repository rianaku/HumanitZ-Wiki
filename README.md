# 🧡 HumanitZ Community Wiki  
*A fan-maintained knowledge base for the survival game **HumanitZ***  

Welcome to the GitHub repository for the **HumanitZ Community Wiki**, a fully open-source project built to document everything about the world, mechanics, systems, and strategies of *HumanitZ*.

This repository powers the public site:

👉 **https://rianaku.github.io/HumanitZ-Wiki/**

Our goal is to create a **professional, organized, and complete wiki** that is:

- Easy to navigate  
- Accurate  
- Up-to-date  
- Beautiful and readable  
- Open to contributions from anyone  

---

## 📘 What This Repo Contains

This repository includes:

### 🖥 GitHub Pages Wiki

Powered by **Jekyll** and a custom **orange/black HumanitZ theme**, the wiki core lives in:

- `index.md`
- `pages/*.md`
- `_layouts/wiki.html`
- `_includes/header.html`
- `_includes/footer.html`
- `assets/css/style.scss`

### 📄 Markdown Content

All wiki articles are written in simple **Markdown**, then rendered to HTML through Jekyll.

### 🎨 Custom Theme

A custom-designed stylesheet replicates the HumanitZ aesthetic:

- Black backgrounds  
- Orange headers (`#E79543`)  
- Grey text  
- Styled tables, code blocks, collapsible sections  

### 🧭 Shared Navigation

A single **header** and **footer** include inject shared navigation and footer content into all pages, so the site stays consistent and easy to maintain.

---

## 📚 Visit the Wiki

The live wiki:

👉 **https://rianaku.github.io/HumanitZ-Wiki/**

Example content areas:

- Game Overview  
- Getting Started  
- Survival Mechanics  
- Weapons & Gear  
- Loot & Crafting  
- Tips & Strategy  
- Glossary  
- And more…

---

## 🛠️ Contributing

Everyone is welcome to help.

### 1️⃣ Fork the Repository

Click **Fork** at the top right of the GitHub page.

### 2️⃣ Create a Branch

Create a feature branch for your changes:

```bash
git checkout -b add-survival-fire-info
````

Use a descriptive branch name that reflects your change.

### 3️⃣ Edit or Add Wiki Pages

All main content lives in:

* `pages/`

Each page should:

* Start with front matter at the top:

  ```yaml
  ---
  title: "Page Title"
  layout: wiki
  ---
  ```

* Use clean Markdown

* Only use raw HTML when necessary (e.g., advanced layout, icons, or special formatting)

* Follow the existing tone and structure for consistency

If you add new pages:

* Place them in `pages/`
* Give them a clear, kebab-case filename (e.g., `weapons-gear.md`, `map-environments.md`)
* Make sure they’re linked from the main navigation and/or index page

### 4️⃣ Submit a Pull Request

Once you’re happy with your changes:

```bash
git add .
git commit -m "Add survival fire mechanics section"
git push origin add-survival-fire-info
```

Then open a **Pull Request** on GitHub.

In your PR, briefly explain:

* What you changed
* Why you changed it
* Any related in-game context, screenshots, or references that help review

A maintainer will review and merge (or request tweaks).

---

## 🎨 Writing & Style Guidelines

To keep the wiki consistent and useful:

### Formatting

* Use `##` for main sections, `###` for subsections, and avoid overusing `#` (top-level) inside content pages.
* Use lists and tables where they make information clearer.
* Keep paragraphs relatively short for readability.
* Use `<details>` blocks for long, optional, or spoiler-like sections:

  ```html
  <details>
  <summary>Click to expand detailed breakdown</summary>

  Long explanation here…

  </details>
  ```

### Tone

* Neutral and informative
* Avoid speculation or unconfirmed rumors
* When possible, base content on in-game testing, verified patch notes, or official dev communication

### Images

If you add screenshots or diagrams, place them under an images folder (you can create this if it doesn’t exist yet):

* `assets/images/`

Reference them like this:

```md
![Short description](/assets/images/example.png)
```

Use meaningful alt text so the wiki is accessible.

---

## 💻 Running the Wiki Locally (Optional)

If you want to preview your changes locally before opening a PR:

### 1️⃣ Install Ruby & Bundler

On Windows, install Ruby from:

* [https://rubyinstaller.org/](https://rubyinstaller.org/)

Then install Bundler and Jekyll:

```bash
gem install bundler jekyll
```

### 2️⃣ Install Dependencies

From the repo root:

```bash
bundle install
```

### 3️⃣ Run the Wiki

```bash
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000/HumanitZ-Wiki/
```

You’ll see the site as GitHub Pages will render it.

---

## 📁 Repository Structure

```text
HumanitZ-Wiki/
│
├── index.md                 # Wiki homepage
├── README.md                # Repository documentation (you are here)
│
├── pages/                   # All main wiki content pages
│   ├── game-overview.md
│   ├── getting-started.md
│   ├── survival-mechanics.md
│   ├── weapons-gear.md
│   ├── loot-crafting.md
│   ├── enemies-threats.md
│   ├── map-environments.md
│   ├── multiplayer-co-op.md
│   ├── tips-strategy.md
│   ├── glossary.md
│   └── contribute.md
│
├── _layouts/
│   └── wiki.html            # Shared layout for wiki pages
│
├── _includes/
│   ├── header.html          # Global navigation bar
│   └── footer.html          # Global footer (contribution info, timestamp, etc.)
│
├── assets/
│   └── css/
│       └── style.scss       # Custom HumanitZ dark theme (extends the Jekyll theme)
│
└── _config.yml              # Jekyll configuration (theme, markdown engine, etc.)
```

---

## 🤝 Credits

This project is community-driven and **not** officially affiliated with the developers of *HumanitZ*.

Thanks to everyone who contributes corrections, data, screenshots, builds, and guides to make the wiki better.

---

## 📬 Contact / Issues

Found a mistake?
Want to request a page or section?
Need help contributing?

Open an issue here:

👉 [https://github.com/rianaku/HumanitZ-Wiki/issues](https://github.com/rianaku/HumanitZ-Wiki/issues)

---

## 🧡 Thank You

Your contributions help new players survive a little longer in the brutal world of **HumanitZ**.

Stay alive out there.
