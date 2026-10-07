# 🌐 WordPress

A practical collection of **WordPress setup, administration, architecture, themes, plugins, user management, and migration notes** for cybersecurity, web administration, and hands-on learning.

This repository brings together the fundamentals needed to understand how a WordPress environment is installed, configured, managed, customized, and migrated.

---

## 📚 What This Repository Covers

The notes progress from **environment setup and WordPress fundamentals** to **users, themes, plugins, administration, and migration**.

### Learning Path

**Server Setup → WordPress Fundamentals → CMS Technology → User Roles → Core Features → Themes → Plugins → Migration**

---

## 📂 Contents

| # | Topic | Description |
|---|---|---|
| 1 | [Apache, PHP, phpMyAdmin, MySQL & WordPress Setup](./1.%20Apache%20PHP%20Phpmyadmin%20MySQL%20and%20WordPress%20Setup.md) | Environment and application-stack setup for WordPress |
| 2 | [What is WordPress?](./2.%20What%20is%20WordPress.md) | WordPress fundamentals, editions, components, uses, advantages and limitations |
| 3 | [CMS Technology Stack](./3.%20%20CMS%20Technology%20Stack%20%282025%29.md) | CMS concepts and comparison of WordPress with other CMS platforms |
| 4 | [User Roles & Capabilities](./4.%20User%20Roles%20and%20Capabilities.md) | WordPress roles, permissions, and capability boundaries |
| 5 | [WordPress Themes](./5.%20WordPress%20Theme.md) | Theme structure, files, types, customization, and installation |
| 6 | [WordPress Core Features](./6.%20WordPress%20Core%20Features%20Explanation.md) | Dashboard, posts, media, pages, users, tools, settings, and administration |
| 7 | [WordPress Themes – Extended Notes](./7.%20Wordpress%20THEMES.md) | Additional theme concepts, block themes, installation, and examples |
| 8 | [WordPress Plugins](./8.%20WordPress%20Plugins.md) | Plugin functionality, installation, categories, maintenance, and examples |
| 9 | [WordPress Migration](./9.%20WordPress%20Migration.md) | Backup, file/database migration, domain changes, configuration, and post-migration checks |

---

## 🖥️ 1. WordPress Environment Setup

The setup guide covers the main components required to host a WordPress installation:

**CentOS → Apache HTTPD → PHP → phpMyAdmin → MySQL → WordPress**

The note also includes references for configuring the underlying server components before deploying WordPress.

---

## 🧠 2. WordPress Fundamentals

The fundamentals section introduces:

- WordPress as an open-source CMS
- WordPress.org vs WordPress.com
- Themes
- Plugins
- Common WordPress use cases
- Advantages and limitations

It provides the foundation for understanding how WordPress sites are structured and managed.

---

## 🧱 3. CMS Technology Stack

The CMS notes explain what a **Content Management System (CMS)** is and compare different CMS categories.

Covered areas include:

- Open-source CMS platforms
- E-commerce CMS platforms
- Headless CMS
- Proprietary/SaaS CMS
- Learning Management Systems
- Specialized CMS platforms

WordPress is discussed alongside technologies and platforms such as Drupal, Joomla, Shopify, Magento, Ghost, Strapi, and others.

---

## 👥 4. User Roles & Capabilities

WordPress provides role-based permissions for controlling what users can do.

The notes cover:

| Role | Scope |
|---|---|
| Super Admin | Multisite network |
| Administrator | Full single-site administration |
| Editor | Content management |
| Author | Own content management |
| Contributor | Draft and submit content |
| Subscriber | Basic profile and site access |

The section also includes a capability comparison covering publishing, editing other users' content, user management, settings, file uploads, and multisite administration.

---

## 🎨 5. Themes

Themes control the **visual presentation and layout** of a WordPress website.

The notes cover common theme components such as:

`style.css` · `index.php` · `functions.php` · `header.php` · `footer.php` · `sidebar.php` · `page.php` · `single.php` · `archive.php`

They also cover:

- Free themes
- Premium themes
- Custom themes
- Theme frameworks
- Block themes
- Full Site Editing
- Theme installation through the dashboard
- Manual installation through FTP
- Theme examples such as Astra, OceanWP, Divi, and Rife Free

---

## 🧩 6. WordPress Core Features

The core administration notes walk through the main areas of the WordPress dashboard:

**Dashboard · Posts · Media · Pages · Comments · Appearance · Plugins · Users · Tools · Settings**

The material explains the purpose of each section and gives practical examples of common administration tasks.

---

## 🔌 7. Plugins

Plugins extend WordPress functionality without changing the WordPress core.

The notes cover plugin categories such as:

- SEO
- Security
- Caching and performance
- Page builders
- E-commerce
- Backup
- Analytics
- Forms
- Membership and LMS
- Image optimization
- Multilingual support

The repository also includes examples of commonly used WordPress plugins and installation methods.

### Plugin Management Principles

The notes emphasize:

- Keep plugins updated
- Prefer maintained and compatible plugins
- Remove unused plugins
- Consider plugin conflicts
- Focus on quality rather than installing excessive plugins

---

## 🚚 8. WordPress Migration

The migration guide covers moving a WordPress site between environments.

### Common Scenarios

- Changing hosting providers
- Changing domains
- Moving from localhost to a live server
- Creating a staging/development copy

### Migration Workflow

**Backup → Transfer Files → Import Database → Update `wp-config.php` → Update URLs → Test → Clean Up**

The notes also cover:

- phpMyAdmin database export/import
- FTP and file-manager transfers
- Database configuration
- Domain URL replacement
- Serialized-data-aware migration tools
- Permalink refresh
- Verification after migration
- Removal of temporary migration files and backups

---

## 🔐 WordPress Administration & Security Relevance

From a security perspective, understanding WordPress administration helps identify areas that commonly require careful review during authorized assessments.

Important areas include:

| Area | Security Relevance |
|---|---|
| User Roles | Access control and privilege boundaries |
| Plugins | Third-party attack surface and maintenance |
| Themes | Custom code and application behavior |
| Core Updates | Patch and vulnerability management |
| File Management | Exposure of application files and configuration |
| Database | Application data and configuration storage |
| Migration | Backup, secrets, URLs, and deployment hygiene |
| Site Health | Operational and maintenance visibility |

The repository is primarily focused on administration and learning rather than a dedicated WordPress exploitation methodology.

---

## 🛠️ Technologies & Tools Referenced

**Apache · PHP · phpMyAdmin · MySQL · WordPress · FTP · FileZilla · WP-CLI**

The notes also reference ecosystem tools and services such as:

**UpdraftPlus · All-in-One WP Migration · Duplicator · Better Search Replace · WP Migrate DB · WordPress.org**

---

## 🧪 Suggested Hands-On Lab

A simple learning environment can be structured as:

`Linux Server`  
↓  
`Apache`  
↓  
`PHP`  
↓  
`MySQL / phpMyAdmin`  
↓  
`WordPress`

Then practice:

1. Install WordPress
2. Create users with different roles
3. Install and activate a theme
4. Install and manage plugins
5. Review the dashboard and core settings
6. Create a backup
7. Perform a test migration in an isolated lab

---

## 📖 Recommended Study Order

For efficient learning:

**1. Setup → 2. WordPress Fundamentals → 3. CMS Concepts → 4. Users & Roles → 5. Core Features → 6. Themes → 7. Plugins → 8. Migration**

After understanding the platform, move into dedicated **WordPress security testing, vulnerability assessment, and web application penetration-testing** material.

---

## ⚠️ Responsible Use

Use these notes for:

**Education · Personal Labs · CTFs · Development · Authorized Security Testing**

Do not test WordPress installations, user accounts, plugins, themes, or servers without explicit authorization.

When working with real environments:

- Keep backups before administrative changes
- Protect database credentials and configuration files
- Remove temporary migration artifacts
- Keep WordPress, themes, and plugins maintained
- Respect user privacy and data-access boundaries

---

## 👤 Author

**Kartik Yadav**

Cybersecurity | Web Application Security | Penetration Testing

GitHub: [KartikkYadav](https://github.com/KartikkYadav)

---

⭐ **A practical WordPress reference covering installation, administration, CMS concepts, users, themes, plugins, and migration.**
