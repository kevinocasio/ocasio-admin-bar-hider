=== Ocasio Admin Bar Hider ===
Contributors: ocas
Tags: admin bar, hide admin bar, toolbar, hide toolbar, non-admin
Requires at least: 6.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Hides the WordPress admin bar for non-administrators on the front end and keeps your dashboard clean.

== Description ==

If you run a membership site, online store, or client website, you don't want every logged-in user seeing the WordPress top bar on your public pages. It clutters your design, confuses customers, and shows links they can't even use.

Ocasio Admin Bar Hider fixes this with one simple setting. When turned on, it hides the top toolbar for non-administrators across your entire front end. Inside the WordPress dashboard, it strips out useless clutter and keeps only the essential links: your site name, user profile, and logout button.

Administrators keep full access to everything. Your clients and subscribers get a clean, distraction-free experience.

= Features =

* **Zero Front-End Bloat:** Runs on clean PHP hooks. It doesn't load extra CSS or JavaScript files on your public pages.
* **Smart Role Detection:** Automatically hides the bar for subscribers, customers, editors, and authors while keeping full tools for site administrators.
* **Minimalist Dashboard Toolbar:** Strips out third-party plugin clutter in the backend for non-admin users.
* **Profile Option Guard:** Hides the "Show Toolbar when viewing site" checkbox on profile screens so users can't accidentally turn it back on.
* **Instant Dashboard Switch:** Turn the feature on or off in one click directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-admin-bar-hider` folder to your `/wp-content/plugins/` directory, or install it directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Go to **Ocasio Plugins -> Dashboard** in your sidebar to toggle your settings.

== Frequently Asked Questions ==

= Will this slow down my website? =
No. The plugin runs on lightweight PHP filters and doesn't load extra stylesheets or scripts on your public pages.

= Can administrators still see the admin bar? =
Yes. Administrators always see the full WordPress admin bar on both the front end and backend.

= What happens if I deactivate the plugin? =
If you turn off or delete the plugin, WordPress goes right back to its default behavior. No leftover database tables or junk files remain.

== Changelog ==

= 1.0.0 =
* Initial public release.
