CRED-like Profile & Rewards App

**Introduction**
This project is a learning exercise to build an Android app similar to CRED, 
focusing on the profile activity with various financial and rewards features. 
The app provides a user-friendly interface for managing user profiles, credit scores, 
cashback rewards, bank balances, and transactions, inspired by the CRED app's design and functionality.


**Features:**
User Profile Display: Shows username (e.g., "andaz kumar") and membership date (e.g., "member since Dec, 2020") with an edit option.
Credit Score Monitoring: Displays the current credit score (e.g., "757") with a refresh option.
Cashback Tracking: Shows lifetime cashback (e.g., "₹3") and current cashback balance (e.g., "₹0").
Bank Balance Checking: Provides a button to check bank balance.
Rewards System: Includes cashback balance, coins (e.g., "26,46,583"), a "win up to Rs 1000" promotion, and a "refer and earn" program.
Transactions Section: Allows users to view all transactions.


**Technologies Used:**
Android: Developed using Kotlin.
AndroidX Libraries: Utilizes components like CardView for UI design.
Custom Resources: Includes custom drawables (e.g., ic_back_arrow, ic_support) and string resources for internationalization.
Fonts and Themes: Uses the Poppins font and custom color themes (e.g., @color/white).

**Setup and Installation**
Clone the Repository:
git clone https://github.com/dkdilipkumar/Cred-Profile-Assignment.git

**Open in Android Studio:**
Launch Android Studio and open the cloned project.

Install Android SDKs:
Ensure the necessary Android SDKs are installed via the SDK Manager in Android Studio.

Running the App
Set Up a Device:
Connect a physical Android device or configure an emulator in Android Studio.

Run the App:
Click the "Run" button in Android Studio.

Screenshots:
![image](https://github.com/user-attachments/assets/bbf38298-d172-4ced-8e56-35099cdb948d)

Contributing

Contributions are welcome! To contribute:
Fork the repository.
Create a new branch for your feature or bug fix (git checkout -b feature/your-feature).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Submit a pull request with a clear description of your changes.

Contact:
For any questions or issues, please open an issue on GitHub.

Notes
The provided XML layout (profile_activity.xml) defines the structure of the profile activity, using components 
like ScrollView, LinearLayout, RelativeLayout, and CardView.
The screenshot provided (Assignment_Submission_Screenshot.jpeg) was analyzed to understand the app's interface and features.
It displays a profile page with sections for user details, 
credit score, cashback, bank balance, rewards, and transactions. Specific values (e.g., credit score of 757, 
lifetime cashback of ₹3) are sample data and not part of the project's core functionality.
The app may require backend integration for features like credit score fetching or bank balance checking, 
but this project assumes mock data or external APIs (not included).













