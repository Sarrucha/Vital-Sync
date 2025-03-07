# Vital-Sync
Vital-Sync Fitness App is a Kotlin-based Android application designed for workout tracking, diet monitoring, and fitness goal management. It features biometric login, workout notifications, offline mode, and multi-language support (including Zulu). Built using Android Studio with Retrofit API for real-time progress tracking and SSO authentication.
## Vital-Sync Fitness App

## Overview
This Fitness App is designed to help users track workouts, stay motivated, and manage notifications about their fitness journey. Built as a robust and user-friendly application, it provides workout completion alerts, a notification channel for important reminders, and includes biometric login, offline mode, and support for multiple languages, including Zulu.

##App Demo
https://youtu.be/0ePKuhByubE?t=8&si=GCOm0GZm3l6TkHYN

## Features
•	Workout Notifications: Sends alerts when users complete workouts or need reminders.
•	Notification Channel: A dedicated channel for fitness-related notifications.
•	Biometric Authentication: Secure login using fingerprint biometrics.
•	Offline Mode: Access essential features even without internet connectivity.
•	Multi-language Support: Includes language support for Zulu as well as English to enhance accessibility.
Feture 4 - Is the sleeping mode 
Feature 5 - Single sign in element

## Technologies Used
•	Android SDK: Core application framework.
•	Kotlin: Backend logic and functionality implementation.
•	Android Jetpack Components: Used for lifecycle management and UI components.
•	Data Structures: Implemented lists and dictionaries for managing workouts, reminders, and notifications.

## Installation and Setup Requirements
•	Operating System: Android 12 or higher
•	Minimum SDK: API Level 24
•	Permissions: Required permissions for notifications and biometric authentication.

## Setup Instructions
1.	Clone the repository to your local machine.
2.	Open the project in Android Studio.
3.	Build the project by pressing Ctrl+F9 or navigating to Build > Make Project to ensure there are no errors.
4.	Run the app on an Android emulator or device with Android 12 or higher.

## Using the new App features 
## Main Dashboard
•	The landing page shows the workout tracker which includes the steps, the water consumed, the users height, weight, age and the heart rate. 
•	A notification pops up based on the number of steps the user has taken. 
## Notification Channel
•	The app includes a notification channel for workout reminders and other alerts.
•	The user receives notifications for workout completion and can schedule reminders for their next session.
## Biometric Authentication
•	A fingerprint biometric option is available for secure login.
## Offline Mode
•	Essential features are accessible offline, allowing users to check workouts and goals without internet access.
## Multi-language Support
•	Users can switch the app’s language to Zulu, enhancing accessibility for a wider audience.
## Troubleshooting
•	Build Errors: Ensure all Android SDK components are up to date. Restart Android Studio if issues persist.
•	Notification Issues: Check that notification permissions are enabled in the device settings.
## Contributing
1.	Fork the repository.
2.	Create your feature branch (git checkout -b feature-branch-name).
3.	Commit your changes (git commit -m 'Add new feature').
4.	Push to the branch (git push origin feature-branch-name).
5.	Open a pull request.

### App Layout
![IMG-20241104-WA0020](https://github.com/user-attachments/assets/cc5eb4d7-c359-45ad-9d21-2a244227714d)

## Welcome Page
Background: Vibrant ocean or beach-themed background that creates a refreshing and motivating atmosphere.
Title and Tagline:
App Title: "Vital-Sync" with the tagline, “Sync our Fitness, Elevate Your Life.”
Welcome Message: A friendly and encouraging message welcoming users to their fitness journey, highlighting features like personalized workouts and meal plans.
Call-to-Action Button:
Button Text: “Click Here” in a large, bold, blue button.
Positioned at the bottom to direct users to the registration or login page.

## Registration Page
![Screenshot_20241201_200009_HealthGuide_](https://github.com/user-attachments/assets/895cac3b-6cbd-45ef-97f9-e64820db1734)

App Logo and Background:
Logo: "Vital-Sync" logo at the top.
Background with a subtle beach theme, consistent with the welcome page for branding consistency.
Form Fields:
Username: Text field for the user’s chosen username.
Email: Field to enter an email address.
Password: Password field with an eye icon for visibility toggle.
Terms and Conditions:
Small note for T&C at the bottom of the form, indicating agreement by signing up.
Create Account Button:
Large blue button labeled “Create An Account” to submit the registration form.
Sign-In Link:
Small link beneath the button, allowing existing users to navigate to the login page.

## Login Page
![Screenshot_20241201_200019_HealthGuide_](https://github.com/user-attachments/assets/e28ac412-6af5-457a-861c-aae0ca6441da)

App Logo and Background:
Logo: "Vital-Sync" logo at the top, matching the registration page.
Same background as the previous pages to maintain branding.
Form Fields:
Username: Field to enter the registered username.
Password: Password entry field with an eye icon to toggle visibility.
Login Button:
Large blue button labeled “Login” for users to submit their credentials.
Create Account Link:
Small link below the button for new users to go to the registration page.

## Health Profile Page
![Screenshot_20241201_200552_HealthGuide_](https://github.com/user-attachments/assets/d6fbbc1e-af66-4da7-aa2e-07dfe9dd9267)

Background:
Consistent blue background, providing a calming feel and visual uniformity with previous screens.
Form Fields:
Age: Label and dropdown or date picker for the user’s birthdate.
Height: Field to enter height in centimeters.
Weight: Field to enter weight in kilograms.
Sex: Field to select gender (e.g., M/F dropdown).
Submit Button:
Blue button labeled “Click Here” at the bottom to save profile information.

## Diet Tracker Layout
![IMG-20241104-WA0016](https://github.com/user-attachments/assets/10016798-3234-40c6-af2b-342bc483745d)

Page Title: “MY Diet Tracker” with a notification bell for diet-related notifications.
Caloric Breakdown: Eaten vs. Burned Calories: Shows daily caloric intake and calories burned.
Macronutrient Breakdown: Displays remaining counts for Carbs, Protein, and Fats, with progress bars.
Meal Tracking: Breakfast, Lunch, Dinner Sections: Each meal has its own section showing calorie count and an “Add” (+) button for adding food items.
Navigation Bar: Same as the main dashboard, with options for Home, Diet Tracker, Health Guide, and Settings.

## Health Guide Layout
![Screenshot_20241201_200709_HealthGuide_](https://github.com/user-attachments/assets/951fd05d-645e-49bb-a52f-540172021ad9)

Page Title: “Health Guide” with a notification icon.
Recipes Section: Contains healthy recipes.
Workout Section: Displays workout routines or guides.
Food Section: Provides food or dietary guidance.
Navigation Bar: Same as the other pages, allowing easy access to Home, Diet Tracker, Health Guide, and Settings.

## Recipes Page
Back Arrow: Positioned on the left to navigate back to the previous page.
Page Title: “Recipes” at the top centre.
Notification Icon: Top-right corner, allowing users to view recipe-related notifications.
Recipe Categories:
Smoothies, Dinner, Lunch, Breakfast, Desserts: Listed as individual rows with simple, recognizable icons (like a blender for smoothies, a pizza slice for lunch, etc.).
Each row is bordered, providing a clean, separated look.

## Workout Page
Back Arrow: Positioned on the left to navigate back to the previous page.
Page Title: “Workouts” centered at the top.
Notification Icon: Positioned in the top-right corner for workout reminders or related updates.
Workout Categories:
Upper Body, Cardiovascular, Lower Body, Full Body: Listed as individual rows with relevant icons (e.g., a dumbbell for upper body, a bike for cardio).
Clean, bordered sections for each workout type, making it easy for users to select specific workout categories.


## Food Section Page
Back Arrow: Positioned on the left to navigate back.
Page Title: “Food Section” centered at the top.
Notification Icon: Top-right corner for notifications related to food or diet.
Food Categories:
Healthy Food, Power Bites, Body Building: Three sections with visually engaging background images for each category.
Each section spans horizontally with soft, slightly transparent overlays for text, making the food categories visually distinct.

## Settings Page
Back Arrow: Positioned on the left to return to the previous page.
Page Title: “Settings” centered at the top.
Notification Icon: Positioned in the top-right corner for any setting-related updates.
Settings Options:
Search Bar: Positioned at the top, allowing users to quickly find specific settings.
Sleeping Mode: Toggle switch for enabling/disabling a “Sleeping Mode” feature.
Customization Options: Arrow icon indicating further customization settings.
Privacy & Security: Arrow icon for navigating to privacy settings.
Help & Support: Arrow icon for accessing support resources.
Rating: Option for users to rate the app.
Navigation Bar: Same bottom navigation as other pages, with options for Home, Diet Tracker, Health Guide, and Settings.

## Cardiovascular Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Cardio Vascular" centered at the top.
Exercise Levels:
Beginner: Displays an image of a person on a stationary bike.
Intermediate: Shows a pair of people jogging outdoors.
Advanced: Shows an individual swimming.
Each exercise level has a distinct image, making it easy for users to visually distinguish different intensities of cardio.

## Customization Page
Back Arrow: Positioned on the left to return to the previous page.
Page Title: "Customization" centered at the top.
Customization Options:
Language: Button for selecting language options, set to "English" by default.
Height and Weight: Options for inputting height and weight values (e.g., 80 kg, 187 cm).
Fitness Goal: Dropdown for choosing fitness objectives like "Lose weight."
Difficulty Level: Options to select between Beginner, Intermediate, and Advanced levels, with Intermediate selected by default.
Save Button: A green "SAVE" button to confirm customization settings.

## Food Section Page
![IMG-20241104-WA0018](https://github.com/user-attachments/assets/839698a6-441a-4a05-aa59-fb66ff11148e)

Back Arrow: Positioned on the left to navigate back.
Page Title: "Food Section" centered at the top.
Food Categories:
Beginner: Shows an image of a simple full-body meal or snack.
Intermediate: Displays a more balanced or elaborate meal.
Advanced: Shows a high-protein meal or something focused on intensive diet requirements.
Each category features an image related to food for different levels of diet complexity.

## Privacy & Security Page
![IMG-20241104-WA0023](https://github.com/user-attachments/assets/32609f6b-22b3-4af6-947c-751ba5a16696)

Back Arrow: Positioned on the left to return to the previous page.
![IMG-20241104-WA0022](https://github.com/user-attachments/assets/82ddeda5-8a76-4a90-824b-140b275b87b6)

Page Title: "Privacy & Security" centered at the top.
Privacy Options:
Biometrics: Option for enabling biometric access.
Privacy Consent: Option to set privacy consent, with a lock icon for security.
Security Consent: Another lock icon for configuring security-related consents.
Consent and Permissions: Option to manage permissions, also with a lock icon to denote security. 
Each privacy option has a distinct icon, helping users quickly identify each setting.

### The one with the images
## Smoothies Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Smoothies" centered at the top.
Smoothie Options:
Banana Smoothie: Displays an image of a banana smoothie.
Spinach Smoothie: Shows an image of a green spinach smoothie.
Each smoothie option has a distinct image to visually distinguish between types.

## Dinner Page
Back Arrow: Positioned on the left to return to the previous page.
Page Title: "Dinner" centered at the top.
Dinner Options:
Spaghetti Bolognese: Shows an image of spaghetti with Bolognese sauce.
Chicken & Rice: Displays an image of a chicken and rice dish.
Each dinner option has a unique image to represent the meal choice.

## Upper Body Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Upper Body" centered at the top.
Exercise Levels:
Beginner: Shows an image of a person doing a basic upper body exercise.
Intermediate: Displays an image of a person doing a moderate upper body workout.
Advanced: Shows an individual engaged in a more intense upper body workout.
Each level has an associated image to indicate exercise difficulty.

## Breakfast Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Breakfast" centered at the top.
Breakfast Options:
English Breakfast: Shows an image of a traditional English breakfast.
Pancakes: Displays an image of pancakes with berries.
Each breakfast option has a distinct image to illustrate the meal type.

## Lunch Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Lunch" centered at the top.
Lunch Options:
Avocado & Bacon Sandwich: Shows an image of a sandwich with avocado and bacon.
Kota / Bunny Chow: Displays an image of a South African street food dish.
Each lunch option has a specific image for easy meal selection.

## Lower Body Page
Back Arrow: Positioned on the left to navigate back.
Page Title: "Lower Body" centered at the top.
Exercise Levels:
Beginner: Shows an image of a basic lower body exercise.
Intermediate: Displays an image of a person doing a moderate lower body workout.
Advanced: Shows an individual performing an advanced lower body exercise.
Each level is represented by an image that corresponds to workout intensity.

### GitHub Actions 
 On 15 Aug 2024, there was a push of the documentation for part 2 of the application. The 13 Aug 2024, a commit of tasked file as an introduction. 
 The 1 Aug 2024, the creation of the GitHub repository.On 05 Sept 2024, an updated build gradle file, along with changing the file name was committed. The 20 Aug 2024, there was a final push of the application. The 19 Aug 2024, there was an update made on the application. On 29 Sept 2024, there was a final product of the part 2, a merge to the main branch, and an ic rounded background xml file were committed. The 17 Sept 2024, initializing the part 2 of the app. The 05 Sept 2024, an updated build gradle file, along with changing the file name was committed.On 25 Oct 2024, a README.md file was created and updated. The 30 Sept 2024, there was a fix for the part 2 version of the application and a video showing the functionality of part 2 was committed.
