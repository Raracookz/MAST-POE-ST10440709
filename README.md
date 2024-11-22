# Culinary Brigade App

## **Version 1.2.0**

**Date:** 22 November 2024

### **Description**
Culinary Brigade is an app designed for chefs to manage menu items dynamically. This update includes several key features such as menu item management, average price calculations, filtering options for guests, and a complete menu view.

---
### **Feedback from part 2**
App ws not completely functional - some errors still not properly dealt with | did not code the Picker correctly - could not select the course | accumulation of the price was incorrect - total ws supposed to be the total number of menu items listed. 

## **Features**

### **1. Average Price Display on Home Screen**
- The home screen now displays the average price of menu items, broken down by courses such as starters, mains, and desserts.
- Added a new averages container with clear visual separation.
- Prices are automatically calculated and updated when items are added or removed.

### **2. Menu Management (New Screen)**
- Added a new screen for managing menu items:
  - Chefs can add new menu items.
  - Chefs can remove items from the menu using a new delete button.
  - Confirmation dialog added for item deletion to prevent accidents.
  - The home page no longer includes the option to add items.
  - Menu items are saved in an array for consistent access across screens.

### **3. Home Page Menu Display**
- The home page now shows the complete list of menu items, including those that the chef has added and removed.
- Added total items counter.
- Enhanced visual styling for menu items.

### **4. Complete Menu Screen (New)**
- Added a new screen to display the complete menu.
- Navigation button added to access the complete menu from the course screen.
- Back button included for easy navigation.

### **5. Advanced Filtering System**
- Implemented a comprehensive filtering system using Picker component.
- Guests can now filter the menu to show only items from a specific course.
- "All Courses" option available to view the complete menu.
- Empty state handling when no items are found for a selected course.

---

## **Bug Fixes**

### **Picker Function Issue**
- Fixed the picker function by installing the proper dependencies.
- Resolved styling issues with the picker component.

### **Style Definitions**
- Fixed missing style definitions for inputContainer.
- Added proper TypeScript types for all style properties.

---

## **Code Changes Overview**

### **Home Screen**
- Displayed the average price of menu items by course.
- Removed the feature for adding menu items directly from the home screen.
- Added delete functionality for each menu item.

### **Menu Management Screen**
- Created a separate screen for menu management where chefs can:
  - Add new menu items to an array.
  - Remove menu items from the list.
- Menu updates are reflected on the home page.
- Added confirmation dialogs for delete actions.

### **Complete Menu Screen**
- New screen implementation with:
  - Course filtering functionality
  - Responsive menu display
  - Back navigation
  - Empty state handling

### **Array Management**
- All menu items are now stored in a centralized array, ensuring consistent data across screens.
- Real-time updates across all screens when items are added or removed.

### **Styling Updates**
- Added new styles for:
  - Delete buttons
  - Average price display
  - Menu list container
  - Picker component
  - Empty state messages

---

## **Installation**

To install the necessary dependencies and run the project locally:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate into the project directory:
   ```bash
   cd <project_directory>
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Install additional required dependencies:
   ```bash
   npm install @react-native-picker/picker
   ```

5. Run the app:
   ```bash
   npm start
   ```

---
### **The app in action !**
Youtube link:


---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
