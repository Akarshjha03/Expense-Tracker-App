# Expense Tracker App

The **Expense Tracker App** is a mobile application developed using **React Native** and **Google Firebase**. It allows users to easily manage and track their daily expenses, categorize them, and analyze their spending patterns over time. The app provides a user-friendly interface, ensuring that budgeting and financial management are simplified and accessible.

<div align="center">
  <img src="https://play-lh.googleusercontent.com/Xc2VEo_ReCQxoDXc-sKOVXkE5ttsT9Ot-aKbuAZOjjbhTIUGhNlJrnnTrSUReum0S1Yw=w600-h300-pc0xffffff-pd" alt="Expense Tracker Logo" width="200"/>
</div>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,firebase,js,css,html,nodejs,git,redux,github,materialui,docker,jest,graphql,rest" />
  </a>
</p>


## Features

- **User Authentication:** Secure login and registration using Firebase Authentication.
- **Expense Tracking:** Add, edit, and delete expenses with details like amount, category, date, and description.
- **Categorization:** Organize expenses into categories such as Food, Travel, Entertainment, etc.
- **Dashboard:** Visual representation of expenses through charts and graphs.
- **Search & Filter:** Easily search and filter expenses by date, category, or keywords.
- **Real-Time Data:** Synchronize data across devices using Firebase Firestore.
- **Notifications:** Set reminders for recurring expenses or budgeting goals.

  <div style="display: flex; align-items: center;">
    <img src="https://via.placeholder.com/150" alt="Placeholder Image" style="margin-right: 20px;">
    <p>This is some text next to the image.</p>
</div>


## Tech Stack

- **Frontend:** React Native
- **Backend:** Google Firebase (Firestore, Authentication)
- **Charts & Graphs:** Recharts or any suitable charting library
- **State Management:** React Context API / Redux

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Akarshjha03/expense-tracker-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd expense-tracker-app
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Set up Firebase:

    - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
    - Add your app to Firebase and configure Firebase Firestore and Authentication.
    - Add the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files to your project.

5. Run the app:

    ```bash
    npm run android # for Android
    npm run ios # for iOS
    ```

## Usage

- **Sign Up/Sign In:** Create an account or log in with your credentials.
- **Add Expenses:** Click on the "Add Expense" button to input details of your expenditure.
- **View Dashboard:** Analyze your spending with interactive charts.
- **Manage Expenses:** Edit or delete entries as needed.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards.

## Acknowledgments

- [React Native](https://reactnative.dev/)
- [Firebase](https://firebase.google.com/)
- [Recharts](https://recharts.org/)
