# Job Application Tracker

## Overview
**Job Application Tracker** is a mobile application built with **React Native** and **Expo Router** to help job seekers manage their job applications efficiently. The app features a user-friendly home screen with a **Welcome** section for searching jobs and a **Popularjobs** section displaying recent job listings. With custom fonts, a responsive layout, and intuitive navigation, the app streamlines the job search process by allowing users to track applications and explore opportunities.

## Features
- **Welcome Section**:
  - Personalized greeting (e.g., "Hi Shruthi !!") and a motivational message.
  - Search bar to filter jobs by keywords.
  - Tabbed interface for selecting job types (**Full-time**, **Part-time**, **Internships**).
- **Recent Jobs**:
  - Displays a list of recent job listings with job titles and company names.
  - Includes a "Show all" button for expanded viewing (to be implemented).
- **Custom Header**:
  - Features a menu button (left) and profile button (right) for navigation.
  - Styled with a clean, shadowless design and a **light white background**.
- **Custom Fonts**:
  - Uses **DM Sans** fonts (Bold, Medium, Regular) for consistent, modern typography.
- **Responsive Design**:
  - Built with **SafeAreaView** and **ScrollView** for smooth scrolling and device compatibility.
- **Navigation**:
  - Powered by **Expo Router** with the home screen as the initial route.

## Technologies Used
- **React Native**: For cross-platform mobile development.
- **Expo Router**: For navigation and routing.
- **Expo Fonts**: For loading **DM Sans** fonts (Bold, Medium, Regular).
- **Custom Components**:
  - `Welcome`: Searchable interface with job type tabs.
  - `Popularjobs`: Displays recent job listings in a card-based layout.
  - `ScreenHeaderBtn`: Reusable button component for header navigation.
- **Constants**:
  - Predefined **COLORS**, **FONT**, **SIZES**, and **icons** for consistent styling.

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shruthic06/Job-Application-Tracker.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Job-Application-Tracker
   ```
3. **Install Dependencies**:
   ```bash
   npm install
   ```
4. **Run the Application**:
   - Start the Expo development server:
     ```bash
     npm start
     ```
   - Use the Expo Go app to scan the QR code or run on an emulator:
     ```bash
     npx expo run:android
     ```
     or
     ```bash
     npx expo run:ios
     ```
   - Alternatively, open `index.html` (if web support is enabled) with a local server:
     ```bash
     python -m http.server 8000
     ```
     and access at `http://localhost:8000`.

## Usage
- **Search Jobs**: Use the search bar in the **Welcome** section to find jobs by keyword.
- **Filter by Job Type**: Select **Full-time**, **Part-time**, or **Internships** to filter job listings.
- **View Recent Jobs**: Scroll through the **Popularjobs** section to see recent job listings with titles and companies.
- **Navigate**: Use the menu (left) or profile (right) buttons in the header for additional functionality (to be implemented).

## Future Improvements
- **Job Tracking Features**:
  - Add functionality to save and track job applications (e.g., job title, company, status, deadlines).
  - Include notes and reminders for follow-ups.
- **API Integration**:
  - Connect to job boards like LinkedIn or Indeed to fetch and save job listings.
- **Enhanced Interactivity**:
  - Implement the "Show all" button to display more jobs.
  - Add sorting and filtering options for job listings.
- **User Profiles**:
  - Enable profile management for personalized settings and saved applications.
- **Mobile Optimization**:
  - Improve performance and responsiveness across devices.
- **Accessibility**:
  - Add screen reader support and high-contrast modes.
