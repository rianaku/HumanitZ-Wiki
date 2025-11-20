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

### **🖥 GitHub Pages Wiki**
Powered by **Jekyll** and a custom **orange/black HumanitZ theme**, the wiki lives in:
/index.md
/pages/*.md
/_layouts/wiki.html
/_includes/header.html
/_includes/footer.html
/assets/css/style.scss


### **📄 Markdown Content**
All wiki articles are written in simple Markdown, then rendered to HTML through Jekyll.

### **🎨 Custom Theme**
A custom-designed stylesheet replicates the HumanitZ aesthetic:

- Black backgrounds  
- Orange headers (#E79543)  
- Grey text  
- Styled tables, code blocks, collapsible sections  

### **🧭 Shared Navigation**
One header + one footer file injects consistent navigation into all pages.

---

## 📚 Visit the Wiki

The live wiki:

👉 **https://rianaku.github.io/HumanitZ-Wiki/**

Popular pages:

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

### **1️⃣ Fork the Repository**
Click **Fork** at the top right.

### **2️⃣ Create a Branch**
Example:
git checkout -b add-survival-fire-info

### **3️⃣ Edit or Add Wiki Pages**
All content lives in:
/pages/


Follow the established formatting style:

- Start each file with front matter:
  ```yaml
  ---
  title: "Page Title"
  layout: wiki
  ---
Use clean Markdown

Avoid raw HTML unless necessary

Use the existing tone/style for consistency

4️⃣ Submit a Pull Request

Explain:

What you changed

Why

Links/screenshots if helpful

A maintainer will review/merge your PR.

🎨 Writing & Style Guidelines

To keep the wiki consistent:

Formatting

Use ## and ### for headings — avoid overusing #

Use tables where appropriate

Keep paragraphs short and readable

Use collapsible <details> blocks for long sections

Tone

Neutral

Informative

No speculation

Cite in-game evidence when relevant

Images

Place in an /assets/images/ folder (you may create one).
Use:
![Description](/assets/images/example.png)

💻 Running the Wiki Locally (Optional)

If you want to preview your changes locally:

Install Ruby + Bundler

On Windows:
Install Ruby from https://rubyinstaller.org/

gem install bundler jekyll

Install dependencies
bundle install

Run the wiki
bundle exec jekyll serve
Visit:
http://localhost:4000/HumanitZ-Wiki/

---

🤝 Credits

This project is community-driven and not officially affiliated with the developers of HumanitZ.

Special thanks to contributors who help expand and maintain this wiki.

---

📬 Contact / Issues

Found a mistake?
Want to request a page?
Need support?

Create an issue:

👉 https://github.com/rianaku/HumanitZ-Wiki/issues

---

🧡 Thank You

Your contributions help new players survive a little longer in the brutal world of HumanitZ.

Stay alive out there.


---
