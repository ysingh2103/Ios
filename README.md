# Bakery Shop Product Picker

This iOS app is designed for a bakery shop, allowing customers to select products (donuts), view prices, and make purchases. It also includes an admin feature to manage inventory, update product availability, and modify stock. Developed using Swift, UIKit, and Xcode, the app includes a secure login for bakery staff to perform management operations.

## Features

- **Product Selection**: Customers can select donuts from a product list and specify the quantity they want to purchase.
- **Price Calculation**: The app calculates the total price dynamically based on the selected quantity.
- **Admin Login**: Bakery staff can log in to:
  - Remove donuts from the list (e.g., mark as out of stock)
  - Add new donuts to the product list
  - Update donut quantities
- **Real-time Feedback**: Real-time updates for selections and inventory management.
- **Secure Access**: Inventory updates and purchase views are restricted to authorized users.

## Technologies Used

- Swift
- UIKit
- Xcode
- GitHub Actions (for CI/CD)
- Test Automation Tools

## Installation

Follow these steps to install and run the app locally on your machine:

### Prerequisites

- Xcode (Version 12.5 or later)
- macOS (Big Sur or later)
- Git

### Steps to Install

1. **Clone the repository**:

   Open your terminal and run the following command:

   git clone https://github.com/ysingh2103/Ios.git

2. **Navigate to the project folder**:
    cd bakery-product-picker

    Open the project in Xcode:

    open BakeryProductPicker.xcodeproj
      Install dependencies (if any using Swift Package Manager, Cocoapods, etc.):

    If there are no dependencies, skip this step.

3. **Run the app**:

In Xcode, choose the appropriate simulator or connected device and hit the Run button (or press Cmd + R).

## How to Use the App

**Customer Mode**:

Open the app.
Select the donut product and specify the quantity.
The total price will be displayed automatically.
Proceed with the purchase (mock flow).

**Admin Mode**:

Log in using the admin credentials.
Modify the product list: add new donuts, update existing quantities, or remove out-of-stock items.

**Testing**
The app includes unit and UI tests to verify the product picker functionality and secure admin access.

## To run the tests:
Go to Product > Test in Xcode or press Cmd + U.

## Contribution
Feel free to contribute to this project by submitting issues or pull requests.


