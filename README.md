# Baratie – PHP Header & Footer Site

A two-page restaurant website for my One Piece themed restaurant, "Baratie". 
Every page shares one header and one footer using PHP `include`.

## Files
| header.php | Top of every page: page setup, site name, nav bar |
| footer.php | Bottom of every page: copyright, location, closes body and html |
| index.php | Home page: welcome message and today's special |
| menu.php | Menu page: starters, mains, desserts, drinks with prices |
| style.css | One stylesheet for every page (navy, gold, and cream theme) |

## How to run
1. Install XAMPP and start **Apache** in the XAMPP Control Panel.
2. Put all files in a folder called `restaurant` inside `C:\xampp\htdocs`.
3. Open `http://localhost/restaurant/index.php` in a browser.

## Features
- Shared header and footer pulled into each page with `include`
- Nav links between Home and Our Menu, with a hover effect
- Menu prices lined up in a column using CSS flexbox
- Today's special shown as a centered card with a gold border
- Prices in Berries (฿), the One Piece currency
