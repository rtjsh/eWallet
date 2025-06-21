# eWallet Flutter App

## Overview
This is a Flutter-based mobile application that replicates the "eWallet" app UI. The app includes a splash screen, login screen, home screen with a balance feature, and a transaction history screen. It is designed for multi-platform support (Android, iOS, web, etc.) and follows the provided UI specifications.

## Features
- **Splash Screen**: Displays the "eWallet" logo and "Loading..." text for 3 seconds before navigating to the login screen.
- **Login Screen**: Allows users to enter an email and password (any valid combination works) with a green "LOGIN" button.
- **Home Screen**: Shows a welcome message, current balance (initially Rs. 480), a "+" button to increase balance by Rs. 5, and a "LOGOUT" button.
- **Transaction History Screen**: Displays a list of transactions (e.g., initial balance and increments) with the current balance.

## Design Specifications
- **Color**: Green (#40C64E)
- **Font Sizes**: Heading (36), Other text (15)
- **App Details**:
  1. Splash screen lasts 3 seconds.
  2. Login uses any email/password combination (no backend required).
  3. After login, users see the Home Page; they can logout, increase balance by Rs. 5, or view transaction history.
  4. Transaction history includes the initial balance and updates with each increment.

## Getting Started
### Prerequisites
- Flutter SDK installed (see [Flutter Installation Guide](https://flutter.dev/docs/get-started/install))
- An IDE like Android Studio or VS Code with Flutter plugin

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rtjsh/eWallet.git
