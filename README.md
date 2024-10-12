# WooCommerce Price Calculator

## Description

The **WooCommerce Price Calculator** plugin allows you to dynamically calculate product prices based on size, quantity, and discounts within your WooCommerce store. This plugin enhances your e-commerce experience by providing customers with a transparent pricing structure based on their selections.

## Features

- Dynamic price calculation based on user-selected sizes.
- Discount options that can be configured in ranges.
- Easy integration with WooCommerce products.
- Simple settings page for managing sizes and discounts.

## Installation

1. Upload the `woo-price-calculator` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to **WooCommerce > Price Calculator Settings** to configure the plugin.

## Settings

### Size Options

- Enter the sizes separated by commas (e.g., `2x2, 3x3, 4x4`).
  
### Discount Options

- Enter discount ranges in the following format:
  

This configuration means:
##Enter discount ranges (e.g., 1-14:0, 15-49:0.35, 50-99:0.45, 100-249:0.55, 250+:0.65)
- **1-14 items:** No discount (0%)
- **15-49 items:** 35% discount
- **50-99 items:** 45% discount
- **100-249 items:** 55% discount
- **250 or more items:** 65% discount

## Usage

1. After installation and activation, navigate to **WooCommerce > Price Calculator Settings**.
2. Input your desired sizes and discount ranges.
3. Save changes to apply your settings.
4. The price calculator will automatically appear on product pages, allowing customers to see dynamic pricing based on their selections.

## Contributing

If you'd like to contribute to the development of this plugin, please fork the repository and submit a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Md Mahfuz Reham**
- [GitHub Profile](https://github.com/mahfuzreham)
