# Enhancement One: Software Design and Engineering

## Inventory Tracker Android Application

This project is an Android inventory management application I originally developed for CS 360 Mobile Architecture and Programming. For my CS 499 capstone, I returned to the application to improve its usability, inventory management features, and account security.

### Improvements Made

- Added validation for inventory quantities.
- Added IN STOCK, LOW STOCK, and OUT OF STOCK indicators.
- Updated SMS alerts for inventory quantities of five or fewer.
- Added inventory searching by item name or item number.
- Replaced plain-text password storage with salted PBKDF2 hashing.

### Testing

I tested inventory quantities of zero, five, and six to verify the stock-status thresholds. I also tested searches with no results and multiple matching results, along with an incorrect-password login attempt.

The enhancement narrative includes screenshots of these tests and explains the changes in more detail.

### Project Files

- **Original CS 360 Project:** The original Android application before enhancement.
- **Enhanced CS 499 Project:** The updated Android application containing the improvements.
- **Enhancement One Narrative:** A Word document explaining the changes, testing, course outcomes, and reflection.
