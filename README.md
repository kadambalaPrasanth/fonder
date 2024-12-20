Fonder - Social Dining Application
Fonder is a mobile application designed to connect individuals based on their dining preferences, enhancing the overall social dining experience. Whether you're looking for a dining companion or want to share your meal preferences, Fonder simplifies the process of connecting people with similar tastes for a more enjoyable dining experience.

Technologies Used
Flutter: For building a cross-platform mobile application.
Firebase: For data storage and retrieval, ensuring seamless user experience.
Android Studio: For development and debugging of the mobile application.
RazorPay: For secure payment processing during the checkout process.
Features
Connect Based on Dining Preferences:
The application matches individuals based on their meal preferences, facilitating social dining experiences.
Shared Cart/Order Management:
Users can create and manage shared carts and orders, making it easier to coordinate dining plans with others.
Cost Splitting:
Fonder allows users to split the cost of meals among group members for seamless payments.
Efficient Data Management:
Firebase is utilized to store and retrieve user data and order details, ensuring quick access and smooth interactions.
Secure Payment Integration:
RazorPay integration ensures secure payment processing, allowing users to make payments with confidence during checkout.
Installation and Setup
1. Clone the Repository
First, clone the repository to your local machine:

```git clone https://github.com/your-username/fonder.git```

2. Install Dependencies
Navigate to the project directory and install the required dependencies:

``` cd fonder```
``` flutter pub get```

3. Set Up Firebase
Create a Firebase project from the Firebase Console.
Add Firebase to your Flutter project by following the setup instructions for FlutterFire.
Replace the google-services.json and GoogleService-Info.plist files in your project with the ones from your Firebase console.
4. Set Up Razorpay
Create a RazorPay account and get the API key from the RazorPay dashboard.
Add the API key to your Flutter project to enable secure payment processing during checkout.
5. Run the App
After setting up Firebase and RazorPay, run the application on your emulator or device:

``` flutter run ```

Contributing
We welcome contributions to Fonder! If you have any suggestions or improvements, please feel free to fork the repository and submit a pull request.

Steps to Contribute:
Fork the repository.
Create a new branch for your feature (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request to the main repository.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Flutter: For providing a powerful framework to build cross-platform applications.
Firebase: For providing real-time data storage and management.
RazorPay: For offering seamless and secure payment integration.
