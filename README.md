<div align="center">
<h1>📄 Privacy PDF Merger 🔒</h1>

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/7fd72de1e43547e5809e119a075af5cf)](https://app.codacy.com/gh/R0mb0/Privacy_pdf_merger/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![pages-build-deployment](https://github.com/R0mb0/Privacy_pdf_merger/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/R0mb0/Privacy_pdf_merger/actions/workflows/pages/pages-build-deployment)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Privacy_pdf_merger)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Privacy_pdf_merger)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

<p>
A modern, sleek, and 100% client-side PDF merging tool. Combine, reorder, and manage your PDF files locally right in your browser. Featuring intuitive drag-and-drop mechanics, live thumbnails, and uncompromising privacy—your files never leave your device. Perfect for secure document management! 🚀
</p>

<div align="center">
  <a href="http://paypal.me/R0mb0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Light.svg">
      <img alt="Saved you time? Support the dev" src="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Default.svg">
    </picture>
  </a>
</div>

## [👉 Click here to launch the App! 👈](https://r0mb0.github.io/Privacy_pdf_merger/)

[![01.png](https://github.com/R0mb0/Privacy_pdf_merger/blob/main/Readme_imgs/01.png)](https://r0mb0.github.io/Privacy_pdf_merger/)
[![02.png](https://github.com/R0mb0/Privacy_pdf_merger/blob/main/Readme_imgs/02.png)](https://r0mb0.github.io/Privacy_pdf_merger/)
[![03.png](https://github.com/R0mb0/Privacy_pdf_merger/blob/main/Readme_imgs/03.png)](https://r0mb0.github.io/Privacy_pdf_merger/)
[![04.png](https://github.com/R0mb0/Privacy_pdf_merger/blob/main/Readme_imgs/04.png)](https://r0mb0.github.io/Privacy_pdf_merger/)


</div>
<hr>

<h2>🚀 Features</h2>
<ul>
<li><strong>100% Local Processing</strong>: Zero server uploads. Absolute privacy is guaranteed because the merging process happens entirely in your browser using <code>pdf-lib</code>.</li>
<li><strong>Interactive Reordering</strong>: A fluid, drag-and-drop grid powered by <code>SortableJS</code>. Simply click, drag, and drop to set the perfect order for your documents.</li>
<li><strong>Live Thumbnails</strong>: Instantly generates high-quality visual previews of the first page of every uploaded PDF using <code>PDF.js</code>.</li>
<li><strong>Bilingual Support</strong>: Built-in localization! Seamlessly adapts the interface to English or Italian based on your system's language settings.</li>
<li><strong>Dark/Light Theme Ready</strong>: Built with Tailwind CSS, the app automatically adapts to your system's color scheme with a beautiful, modern, and rounded aesthetic.</li>
<li><strong>Fully Responsive</strong>: An elegant layout that splits cleanly on desktop and stacks perfectly on mobile devices.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>File Selection:</strong> Load multiple PDFs at once using the large drag-and-drop zone or the standard file dialog.</li>
<li><strong>Client-Side Parsing:</strong> <code>PDF.js</code> instantly processes the local files, extracting the first page and drawing it onto an HTML canvas to generate a lightweight image thumbnail.</li>
<li><strong>The Grid Array:</strong> The DOM updates dynamically. Every time you move a card to reorder your files, the underlying JavaScript array synchronizes automatically.</li>
<li><strong>The Merge Process:</strong> Upon clicking "Merge", <code>pdf-lib</code> constructs a new PDF document in memory. It sequentially copies every page from your selected files, tracks the progress visually, and outputs a downloadable Blob URL.</li>
</ol>

<h2>🏆 What makes it special?</h2>
<ul>
<li><strong>No Cloud Dependencies</strong>: Unparalleled peace of mind for professionals handling sensitive documents like NDAs, invoices, contracts, or personal IDs.</li>
<li><strong>Single-File Architecture Ready</strong>: The entire structure can run without complex backends, making it incredibly lightweight, fast, and easily hostable on static platforms like GitHub Pages.</li>
</ul>

<h2>💡 Why use this project?</h2>
<ul>
<li><strong>Speed & Privacy</strong>: Stop uploading your sensitive data to third-party ad-filled websites just to merge two files together. Do it instantly, safely, and beautifully right from your local machine.</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Simply open the <a href="https://r0mb0.github.io/Privacy_pdf_merger/">Live Demo link</a> on any browser and start dropping your files!</p>

<h3>Local Installation</h3>
<p>Want to run it locally or use it entirely offline?</p>
<ol>
<li><strong>Clone this repository</strong> or download the source code ZIP.</li>
<li>If you want offline capabilities, ensure the linked JavaScript libraries (Tailwind, pdf-lib, PDF.js, SortableJS) are downloaded into the same directory and correctly referenced in the <code>index.html</code>.</li>
<li>Double-click <code>index.html</code> to open it in your browser. That's it!</li>
</ol>

<h2>⚠️ Troubleshooting: Memory Cleanup</h2>
<p>
  Because this app processes files locally in your RAM using Blob URLs, working with incredibly massive PDFs (hundreds of megabytes) might slow down older devices. <br><br>
  If you notice any stuttering after multiple heavy merges, simply click the <strong>Start Over</strong> button. The app is programmed to automatically execute <code>URL.revokeObjectURL()</code> to clean up the browser's memory and give you a fresh, clean slate!
</p>

<br>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Crafted with AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDefault.svg">
</picture>
</a>
