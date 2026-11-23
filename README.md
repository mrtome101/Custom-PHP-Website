<div align="center">

  <h1>⚡ BrutMC — Minecraft Server Website & Live Admin Customizer</h1>
  <p>
    A sleek, lightweight, database-free PHP web template and real-time visual customizer built specifically for Minecraft servers.
  </p>

  <p>
    <img src="https://img.shields.io/badge/PHP-8.1%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.1+" />
    <img src="https://img.shields.io/badge/Database-None%20(JSON)-10B981?style=for-the-badge&logo=json&logoColor=white" alt="JSON Storage" />
    <img src="https://img.shields.io/badge/Pterodactyl-Ready-00B4D8?style=for-the-badge" alt="Pterodactyl Ready" />
    <img src="https://img.shields.io/badge/Mobile%20%26%20PC-Preview-A3E635?style=for-the-badge" alt="Responsive Preview" />
  </p>

</div>

---

## ✨ Features

* **🎨 Live Visual Customizer (`/admin/`):** Change primary colors, background tones, fonts, and logo sizes with an instant side-by-side live preview before saving[cite: 28, 49].
* **📱🖥️ Mobile & PC View Switcher:** Built-in responsive preview toggle inside the Admin Panel so you can inspect both mobile and 1280px desktop layouts in real time[cite: 49].
* **🚀 Zero Database Required:** All configurations, texts, rules, and staff profiles are stored cleanly in `data/settings.json`—no MySQL setup needed[cite: 22, 23].
* **👥 Interactive Staff Roster & Profile GUI:** Manage staff ranks, custom 3D Minecraft skins, profile banners, Discord handles, and bios directly from the panel[cite: 21, 28].
* **📜 Dynamic Rules & Vote Pages:** Add unlimited rule sections with custom icons and color highlights (`[[text]]` & `**bold**`), plus customizable vote links[cite: 20, 21, 28].
* **🌐 Live Server & Discord Status:** Real-time player count and Discord online member counter with automatic proxy fallbacks[cite: 8, 43].
* **✨ Interactive Particle Backgrounds & Effects:** Customizable `tsParticles` background network, announcement banner bar, and one-click maintenance mode[cite: 21, 28, 35].

---

## 📂 Project Structure

```text
www/
├── admin/              # Admin dashboard, live preview, themes & auth config
├── core/               # Vendor libraries (FontAwesome, jQuery, Prism)
├── custom/templates/   # Cobalt-inspired dark UI stylesheets & particle scripts
├── data/               # JSON configuration files (defaults.json & settings.json)
├── inc/                # Core PHP helpers, content renderers & editable fields
├── rules/              # Clean URL routing for /rules/
├── staff/              # Clean URL routing for /staff/
├── vote/               # Clean URL routing for /vote/
├── uploads/            # Logos, banners, favicons & custom admin uploads
└── index.php           # Main landing & news page
