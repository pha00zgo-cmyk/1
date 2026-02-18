
# Monique Cafe - QR Menu & Takeout Order System

## Overview

This project is a comprehensive QR-based menu and takeout ordering system for a cafe named "Monique" located in Seogwipo, Jungmun, Jeju. It is designed to be embedded into a WordPress site, but it can also function as a standalone web application. The system allows customers to view the menu, add items to a cart, and generate a takeout order that can be sent to the cafe via KakaoTalk or SMS.

## Implemented Features

### Core Functionality

*   **QR Code Menu:** Customers can scan a QR code to access the digital menu.
*   **Dynamic Menu Display:** The menu is dynamically rendered from a JavaScript object, making it easy to update.
*   **Shopping Cart:** Customers can add items to a shopping cart, adjust quantities, and see a running total.
*   **Takeout Order Generation:** The system generates a formatted text-based order summary that includes the customer's name, phone number, pickup time, and any special requests.
*   **Order Sharing:** Customers can easily share the generated order via KakaoTalk, SMS, or by copying it to the clipboard.

### Advanced Features

*   **Automatic Image Association:** The system can automatically fetch and display menu item images from a WordPress media library by searching for filenames that match the menu item IDs.
*   **Google Maps Integration:** An embedded Google Map shows the cafe's location, and customers can get directions using Naver Maps, Kakao Maps, or Google Maps.
*   **Schema.org Integration:** The application generates structured data (JSON-LD) for the cafe, including its name, address, phone number, and opening hours. This improves the cafe's visibility in search engine results.
*   **Customizable Settings:** The cafe owner can easily update the store name, address, phone number, Google Maps embed URL, and KakaoTalk chat link.
*   **Opening Hours:** The opening hours are configurable and are displayed to customers. They are also included in the Schema.org data.

### Technical Details

*   **Framework-less:** The application is built with plain HTML, CSS, and JavaScript, with no external frameworks.
*   **QR Code Generation:** The `qrcode.js` library is used to generate QR codes.
*   **Responsive Design:** The layout is responsive and works well on both mobile and desktop devices.
*   **REST API for Images:** The system uses the WordPress REST API to search for and retrieve menu item images.
*   **LocalStorage:** The shopping cart and opening hours settings are persisted in the browser's `localStorage`.

## Current Change: Initial Setup

This is the initial setup of the project. The `index.html` file has been populated with the complete HTML, CSS, and JavaScript code for the application.
