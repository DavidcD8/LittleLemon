# Restaurant Booking & Menu Application

This Django web application is part of the **Meta Back-End Developer Professional Certificate** program. It showcases essential backend development skills including working with models, views, forms, and templates to build a dynamic restaurant application.

## Features

- **Homepage:** Showcases special offers, new menu highlights, and links to other pages.
- **About Page:** Provides information about the restaurant.
- **Menu Display:**
  - Lists all menu items.
  - Displays details for individual menu items.
- **Booking System:**
  - A form for booking a table.
  - Saves booking information such as first name, last name, number of guests, and comments.

## Models

### Booking
- **first_name:** The first name of the person booking.
- **last_name:** The last name of the person booking.
- **guest_number:** The number of guests.
- **comment:** Additional comments or special requests.

### Menu
- **name:** The name of the menu item.
- **price:** The price of the item.
- **description:** A short description of the menu item.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
