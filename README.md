# rn-assignment5-11290194
Overview
This is a React Native application featuring a user-friendly interface for managing financial transactions, viewing card details, and accessing various settings. The app includes a theme toggle for switching between light and dark modes and employs a bottom tab navigation structure.

Features
Home Screen: Displays user profile, card details, quick actions, and transaction history.
My Cards Screen: Placeholder screen for displaying user's cards.
Statistics Screen: Placeholder screen for displaying financial statistics.
Settings Screen: Allows users to change app settings, including language, profile, contact information, password, privacy policy, and theme.

Code Structure
The main components and their functions are as follows:

App.js
Sets up the theme context and provides the theme to the entire application.
Contains the main navigation container with a stack navigator and bottom tab navigator.

HomeScreen.js
Displays user information, card details, quick actions, and a list of transactions.
Uses SafeAreaView, View, Text, Image, ScrollView, IconButton, and custom styles.

SettingsScreen.js
Provides options to change language, profile, contact information, password, privacy policy, and theme.
Uses View, Text, Icon, Switch, and custom styles.

MyCardsScreen.js and StatisticsScreen.js
Placeholder screens displaying static text.
Uses View, Text, and custom styles.

MyTabs.js
Defines the bottom tab navigator with icons for each tab (Home, My Cards, Statistics, Settings).
Uses createBottomTabNavigator and MaterialCommunityIcons.

ThemeProvider.js
Manages the theme state and provides a toggle function.
Combines themes from react-native-paper and @react-navigation/native for both light and dark modes.

Theming
The application supports both light and dark themes, which can be toggled from the settings screen. Themes are defined by combining the default themes from react-native-paper and @react-navigation/native.

Light Theme
Background: #ffffff
Text: #333333
Dark Theme
Background: #333333
Text: #ffffff
![WhatsApp Image 2024-06-26 at 23 07 02_18497c44](https://github.com/Quaci-Perry/rn-assignment5-11290194/assets/170188245/becbaca0-f9df-4ef0-85ac-99ac580bb4b4)
![WhatsApp Image 2024-06-26 at 23 07 02_2232caa5](https://github.com/Quaci-Perry/rn-assignment5-11290194/assets/170188245/9fee8c2d-8da4-42be-a741-c9398a7b27c4)
![WhatsApp Image 2024-06-26 at 23 07 03_bc6b1c40](https://github.com/Quaci-Perry/rn-assignment5-11290194/assets/170188245/5adc3c61-bf31-4b4e-86d6-3b5aa07c1cd6)
![WhatsApp Image 2024-06-26 at 23 07 03_872b0cba](https://github.com/Quaci-Perry/rn-assignment5-11290194/assets/170188245/0a463386-af92-4107-977e-8ebeaa1beb74)



