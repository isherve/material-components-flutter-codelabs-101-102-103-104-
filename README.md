# Shrine Flutter App

## Overview

The Shrine Flutter app is a demonstration of how to build a beautiful, responsive e-commerce app using Flutter. It showcases advanced UI components, such as the backdrop menu, asymmetric product grids, and custom animations. The app is designed to help developers improve their Flutter design skills and learn how to implement complex UI patterns.

## Features

- *Backdrop Menu*: A custom menu that slides in and out, providing a seamless user experience.
- *Asymmetric Product Grid*: A unique layout for displaying products in a visually appealing way.
- *Custom Animations*: Smooth transitions and animations to enhance the user experience.
- *Responsive Design*: The app is designed to work well on both mobile and tablet devices.
- *Custom Fonts and Themes*: Uses the Rubik font and a custom theme to create a cohesive look and feel.

## Getting Started

### Prerequisites

- Flutter SDK installed on your machine.
- Dart SDK installed on your machine.
- An IDE (e.g., Android Studio, VS Code) with Flutter and Dart plugins installed.

### Installation

   

1. *Install dependencies*:
   bash
   flutter pub get
   

2. *Run the app*:
   bash
   flutter run
   

### Project Structure

- *lib/*: Contains the main Dart code for the app.
  - *app.dart*: The main app widget that sets up the routes and theme.
  - *backdrop.dart*: Implements the backdrop menu.
  - *category_menu_page.dart*: Displays the category menu.
  - *colors.dart*: Defines the color scheme for the app.
  - *home.dart*: The home page that displays the product grid.
  - *login.dart*: The login page.
  - *model/*: Contains the product model and repository.
  - *supplemental/*: Contains additional widgets like the asymmetric view and custom borders.
- *pubspec.yaml*: Defines the project dependencies and assets.

### Dependencies

- *flutter*: The core Flutter framework.
- *intl*: Provides internationalization and localization support.
- *cupertino_icons*: Provides the Cupertino icons for the app.
- *shrine_images*: A package containing the product images used in the app.

### Assets

- *fonts/*: Contains the Rubik font files.
- *assets/*: Contains images like the diamond and slanted menu icons.
- *packages/shrine_images/*: Contains the product images.

## Customization

### Adding New Products

To add new products, update the ProductsRepository class in lib/model/products_repository.dart. You can add new products to the _allProducts list.

### Changing the Theme

The app's theme is defined in lib/app.dart within the _buildShrineTheme function. You can customize the colors, text styles, and other theme properties here.

### Adding New Categories

To add new categories, update the Category enum in lib/model/product.dart. Then, update the CategoryMenuPage in lib/category_menu_page.dart to include the new categories.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the Apache License 2.0. 

