# Barustore

A WooCommerce storefront theme project for Barustore, based on the Woodmart theme framework.

This repository contains the theme source used for the storefront presentation and configuration. It is intended to be used inside a WordPress installation under `wp-content/themes/woodmart` or adapted into a custom theme package for deployment.

## Project purpose

- Build and manage a premium e-commerce storefront
- Extend the Woodmart theme with custom storefront logic and styling
- Support WooCommerce catalog and product pages
- Keep theme source in version control for easier updates and deployment

## Project structure

- `inc/` – theme framework and custom integrations
- `js/` – frontend JavaScript assets
- `css/` – theme stylesheets
- `woocommerce/` – WooCommerce overrides and templates
- `header-elements/` – custom header elements and templates
- `languages/` – translation files

## Local setup

1. Place this folder into your WordPress installation under:
   `wp-content/themes/woodmart`
2. Activate the theme in WordPress admin:
   `Appearance > Themes`
3. Install and activate WooCommerce.
4. Configure theme settings and import demo content if needed.

## Requirements

- WordPress
- WooCommerce
- PHP 7.4+ recommended
- Modern browser support for the storefront experience

## Security note

This project was reviewed for injected activation/license overrides and malicious code patterns. The known fake activation code was removed from `functions.php` before publishing.

Before deploying to production, always validate the theme files with PHP linting and review any environment-level WordPress plugins and custom code.

## Deployment

Use this repository as the source for your theme deployment pipeline. For production, ensure the full WordPress install, database, uploads directory, and plugin configuration are handled separately from the theme source itself.

## License

This project is a storefront/theme implementation for Barustore and should be used according to the applicable licensing terms of the theme/framework and any bundled assets.
