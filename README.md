# Book Bazaar Hub

## Description
Book Bazaar Hub is an online book marketplace where users can buy and sell books. It provides a platform for book enthusiasts to browse available books, search for specific titles, and list their own books for sale.

## Features
- Browse available books
- Search for books by title
- Buy books using PayPal
- Sell books by submitting a listing with book details and an image

## Setup Instructions

### 1. Get Your PayPal Client ID
1. Go to [PayPal Developer](https://developer.paypal.com/)
2. Log in with your PayPal account
3. Navigate to **"My Apps & Credentials"**
4. Under **"REST API apps"**, click **Create App**
5. Copy your **Client ID**

### 2. Add PayPal Client ID to Your Code
- Open the `index.html` file.
- Find the following line:
  ```html
  <script src="https://www.paypal.com/sdk/js?client-id=YOUR_PAYPAL_CLIENT_ID&currency=USD"></script>
  ```
- Replace `YOUR_PAYPAL_CLIENT_ID` with your actual PayPal Client ID.

### 3. Upload and Deploy
- If using **Google Sites**, embed the HTML code using the custom embed option.
- If hosting on another platform, upload the files to your web server.

## Future Enhancements
- User authentication for better security
- Advanced book categories and filters
- More payment options

## Contributing
If you'd like to contribute to this project, feel free to suggest improvements or report issues.

## License
This project is open-source. Feel free to modify and enhance it as needed.

