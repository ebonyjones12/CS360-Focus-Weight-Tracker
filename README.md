# Focus - Weight Tracking App
## CS 360 Mobile Architecture & Programming - Project Two

### Project Overview
Focus is an Android mobile application designed to help users track their weight over time. The app provides a simple, intuitive interface for logging daily weight entries and monitoring progress toward fitness goals.

### App Features

#### 1. User Authentication
- Secure login screen with username and password fields
- Password input is obscured for security
- New user account creation functionality
- Simple and clean user interface

#### 2. Weight Data Management
- **Data Grid Display**: View all weight entries in an organized table format
- **Add Entries**: Input date and weight measurements
- **Delete Entries**: Remove individual weight records with dedicated delete buttons
- **Scrollable Interface**: View historical data with smooth scrolling

#### 3. SMS Notifications
- Goal notification system via SMS
- Permission request handling for SMS access
- User control over notification preferences
- Notifications trigger when users reach their goal weight

### Technical Implementation

<img width="773" height="698" alt="Screenshot 2026-02-07 at 7 28 57 PM" src="https://github.com/user-attachments/assets/d6852866-1207-45dc-b66f-bcb255f30df1" />

1. **Login Screen** (`activity_login.xml`)
   - Username input field
   - Password input field (text obscured)
   - Login button
   - Create Account button

<img width="715" height="624" alt="Screenshot 2026-02-07 at 7 29 03 PM" src="https://github.com/user-attachments/assets/2e94effb-456c-4e0d-8ad8-154fed547f78" />

2. **Weight Data Grid** (`activity_weight_data.xml`)
   - Date and weight input fields
   - Add button for new entries
   - Data grid with headers (Date, Weight, Action)
   - Delete buttons for each row
   - SMS notification permission button

#### Permissions & Manifest
- **SMS Permission**: `SEND_SMS` for goal notifications
- **Telephony Feature**: Declared in AndroidManifest.xml
- Permission handling with user consent

### Design Principles
- **User-Centered Design**: Clean, intuitive interface focused on ease of use
- **Visual Hierarchy**: Logical flow from input to data display
- **Consistent Theme**: Blue and white color scheme throughout
- **Responsive Layout**: Works across different screen sizes

### Project Requirements Met
✓ Login screen with authentication elements  
✓ Database display as a grid with logical headers  
✓ Add and delete functionality for data entries  
✓ SMS notification permissions properly configured  
✓ Visual hierarchy with focus order and grouping  
✓ Consistent theme and creative layout  

### Development Environment
- **IDE**: Android Studio Otter 2 Feature Drop (2025.1.1)
- **Language**: Java
- **Minimum SDK**: API 24 (Android 7.0 Nougat)
- **Target SDK**: Latest
- **Build System**: Gradle

### Installation & Setup
1. Clone this repository
2. Open project in Android Studio
3. Sync Gradle files
4. Run on Android emulator or physical device (API 24+)

### Future Enhancements (Project Three)
- Database integration with SQLite
- Functional login authentication
- Dynamic data grid population
- SMS notification implementation
- Goal weight setting and tracking
- Data visualization (charts/graphs)

### Author
**Ebony Jones**  
Southern New Hampshire University  
CS 360 - Mobile Architecture & Programming  
February 2026

### Project Status
**Project Two**: UI Design - ✅ Complete  
**Project Three**: Full Implementation - 🔄 In Progress
