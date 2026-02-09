# RandomThoughtsInTraffic.com

Where real traffic meets network traffic.

## Why this project exists
I built RandomThoughtsInTraffic.com as a production WordPress site focused on technical writing about web fundamentals (HTML, CSS, and JavaScript) with a human voice. It showcases my end-to-end WordPress development and operations work: content strategy, theme customization, plugin integration, performance tuning, and maintainable publishing workflows.

## Highlights
- **Content strategy:** I write long-form technical posts that translate complex topics into approachable narratives.
- **Platform engineering:** I manage WordPress core, caching, and performance-oriented plugin choices.
- **Web fundamentals:** I cover HTML, CSS, and JavaScript topics with real-world examples.
- **Production mindset:** I plan for backups, upgrades, and safe deployment practices.
- **Developer empathy:** I keep structure and workflows clear for editors and engineers.

## Live site
- https://randomthoughtsintraffic.com

## Tech stack
- **CMS:** WordPress
- **Runtime:** PHP
- **Database:** MySQL or MariaDB
- **Web server:** Apache (XAMPP compatible)
- **Theme:** Ashe (WP Royal)
- **Caching:** LiteSpeed Cache
- **Forms:** Contact Form 7
- **Utilities:** Insert Headers and Footers, Site Kit, Classic Widgets

## Content overview
Featured posts are indexed in [llms.txt](llms.txt) and include essays such as:
- JavaScript as the "support class" that quietly runs the game
- The quiet power of CSS
- HTML as the backbone of the web

## Project structure
This is a standard WordPress installation with content and configuration in the usual locations.
- Core runtime and admin: [wp-admin/](wp-admin/), [wp-includes/](wp-includes/)
- Site configuration: [wp-config.php](wp-config.php)
- Themes, plugins, and uploads: [wp-content/](wp-content/)
- Primary theme: [wp-content/themes/ashe/](wp-content/themes/ashe/)
- Database export (local/dev use): [u942215055_BodOV.sql](u942215055_BodOV.sql)

## Local development (XAMPP)
1. Install XAMPP and enable Apache and MySQL.
2. Place this project folder in the XAMPP web root.
3. Create a local database.
4. Import the database dump from [u942215055_BodOV.sql](u942215055_BodOV.sql).
5. Update [wp-config.php](wp-config.php) with your local database settings.
6. Visit the site in your browser and log in via /wp-admin.

## Development workflow
- **Content edits:** I use the WordPress editor for posts and pages.
- **Theme changes:** I update templates and styling in [wp-content/themes/ashe/](wp-content/themes/ashe/).
- **Plugin management:** I manage plugins in [wp-content/plugins/](wp-content/plugins/).
- **Uploads:** I store media in [wp-content/uploads/](wp-content/uploads/).

## Performance and SEO
- **Caching:** I use LiteSpeed Cache for page and asset caching.
- **SEO:** I focus on semantic HTML, clean typography, and readable content structure.
- **Core health:** I keep WordPress core auto-updates enabled for minor releases.

## Security notes
- I keep [wp-config.php](wp-config.php) out of public sharing or replace secrets before publishing.
- I update plugins and themes regularly.
- I use unique credentials and enable HTTPS in production.

## What to review (for technical evaluators)
- My content architecture and voice consistency
- My theme-level presentation and accessibility
- My plugin choices and operational tradeoffs
- My backup, update, and deployment strategy

## License and attribution
- WordPress: GPL
- Ashe Theme: GPLv3 or later (see [wp-content/themes/ashe/readme.txt](wp-content/themes/ashe/readme.txt))
- Third-party plugins remain under their respective licenses