# Magento 2 Swatch Selector for Wishlist (Hyvä-Compatible)

## Overview

**Magento 2 Swatch Selector for Wishlist** enhances the default Magento wishlist by allowing customers to select configurable product options such as **color, size, and pattern directly from the wishlist page**.  
This improves user experience, reduces friction, and increases conversions.  
The module is **AJAX-powered, lightweight**, and **fully compatible with Hyvä Themes**, Magento Open Source, and Magento Commerce.

---

## Compatibility & Technology

<p align="left">
  <img src="assets/hyva.svg" alt="Hyvä Themes Compatible" height="36"/>
  <img src="assets/magento.svg" alt="Magento 2 Compatible" height="36"/>
  <img src="assets/aum-technolabs.svg" alt="Aum Technolabs" height="36"/>
</p>

---

## Features

- **Swatch Selection in Wishlist** – Customers can choose configurable product options without returning to the product page.
- **AJAX-Based Updates** – Smooth option selection without page reloads.
- **Improved User Experience** – Streamlined shopping flow reduces friction and boosts engagement.
- **Hyvä Themes Compatible** – Works seamlessly with Hyvä-based frontends.
- **Mobile-Friendly & Responsive** – Optimized for mobile and touch devices.
- **Performance Optimized** – Lightweight code ensures fast page loads.

---

## Benefits

- **Increase Conversions** – Quickly adjust product options and proceed to checkout from the wishlist.
- **Reduce Cart Abandonment** – No need to navigate back to the product page to update selections.
- **Enhance Customer Satisfaction** – Provides a fast, intuitive, and hassle-free shopping experience.

---

## Installation

### 1. Copy Module

Place the module in your Magento codebase:

```bash
app/code/AumTechnolabs/MyWishlistWithSwatches
````

### 2. Enable Module & Run Setup

```bash
php bin/magento module:enable AumTechnolabs_MyWishlistWithSwatches
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
```

### 3. Deploy Static Content (Production)

```bash
php bin/magento setup:static-content:deploy -f
```

---

## Compatibility

* Magento Open Source & Commerce: 2.3.x, 2.4.x
* Themes: Hyvä, Luma, custom Magento themes
* Compatible with third-party wishlist extensions

---

## Usage

1. Add configurable products to the wishlist.
2. Select desired options (color, size, pattern) directly on the wishlist page.
3. Update wishlist items or proceed to add to cart seamlessly.

---

## SEO & Keywords

Magento 2 wishlist swatch selector, configurable product wishlist, Hyvä Themes Magento extension, AJAX wishlist, wishlist to cart, Magento configurable options, wishlist UX, Magento 2 extension

---

## Support & Contribution

* Open issues or submit pull requests on the repository.
* For professional support or customizations, contact: **[contact.aumtechnolabs@gmail.com](mailto:contact.aumtechnolabs@gmail.com)**

---

## Changelog

* **1.0.0** – Initial release with wishlist swatch selector, AJAX updates, and Hyvä compatibility

---

## License

This module is open-source and distributed under the **GNU General Public License (GPL)**.
