# TickTask - Habits & Goals
TickTask is a minimalist and first offline habit tracking application designed to run entirely in your web browser.
Built with a focus on privacy and simplicity, it allows users to track daily habits, visualize progress through analytics, and manage data without the need for accounts, servers, or internet connectivity.

## 🌟 Features
1. Interactive Daily Grid
  * Visual Tracking: A clean, calendar-based grid view to mark daily habit completion.
  * Habit Management: Easily add, edit, or delete habits.
  * Monthly Navigation: Navigate between past and future months.
  * Month Locking: "Save & Finalize" feature to archive past months, making them read-only to preserve history.

2. Smart Analytics Dashboard
Visualize your consistency with three distinct view modes:
  * Current Month:
    * Line Chart: View daily consistency trends.
    * Bar Chart: Weekly volume breakdown.
    * Pie Chart: Overall monthly completion percentage.
    * Top Habits: A leaderboard of your strongest habits for the month.
  * All Time: View total ticks, active months, and your most consistent habit over time.
  * Compare Mode: Select any two months side-by-side to compare performance statistics and see which month had better consistency.

3. Data Privacy & Portability
  * Local Storage: All data is stored locally in your browser (using localStorage). No data is ever sent to a server.
  * Backup & Restore: Export your entire history to a JSON file and import it on other devices.
  * Offline Capable: The application is a single HTML file that works without an internet connection.

4. UI/UX Design
  * Responsive Interface: Built with Tailwind CSS, the layout adapts seamlessly to desktop and mobile screens.
  * Minimalist Aesthetic: Clean typography (Inter font), intuitive iconography (Google Material Symbols), and a calming color palette.
  * Motivational Elements: An auto-rotating carousel of inspirational quotes to keep you motivated.

## 🛠️ Technology Stack
  * Core: HTML5, JavaScript (Vanilla ES6+)
  * Styling: Tailwind CSS (via CDN)
  * Icons: Google Material Symbols
  * Fonts: Inter & Google Fonts
  * Storage: Browser LocalStorage API

## 🚀 How to Run
Since TickTask is a client-side application contained within a single file, "installation" is instant.
  * Download: Download the index.html file.
  * Open: Double-click the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
  * Use: Start adding habits immediately. Your data will persist automatically.

## 📂 Data Structure
The application saves data under the LocalStorage key ticktask_data_v3. The data object includes:
  * habits: Array of active habit objects (ID, name, icon, color).
  * records: Object mapping habit IDs and dates to completion status.
  * archivedMonths: Snapshot of habits and records for months that have been locked.

## 💾 Backup & Transfer
To move your data to a new device:
  * Go to the Download/Backup tab.
  * Click Export Backup to download a .json file.
  * On the new device, open TickTask, go to the Download/Backup tab.
  * Upload the file using the Restore Data section.

## 👥 Credits
  * Development Assistance: Google Gemini 2.0 Flash.
  * Design Inspiration: Instagram Reels.
  * Date: December 2025.

## 📷 Screenshots

#### Home Page
<img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/5c253b4c-83b9-48af-8e46-d9ff6eb3b53d" />


Edit or Delete options for existing habits:
<img width="238" height="123" alt="image" src="https://github.com/user-attachments/assets/c9c51cf5-f6d2-41d4-a952-cc3f65764487" />


Please ensure you press this button at the conclusion of the current month, prior to proceeding to the next month:
<img width="427" height="115" alt="image" src="https://github.com/user-attachments/assets/5f0ac5f2-4685-4104-93ff-10fa73f00be2" />

#### Dashboard
<img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/415f875a-181e-403b-93ed-e29df5f0fcfc" />
<img width="1920" height="929" alt="image" src="https://github.com/user-attachments/assets/7fcd7706-4525-4aad-a9e0-1b5ea7b0f6c5" />
<img width="1920" height="927" alt="image" src="https://github.com/user-attachments/assets/62683630-40ad-46d2-8824-92d3b2a74379" />

All Time: 
<img width="1547" height="279" alt="image" src="https://github.com/user-attachments/assets/01e4d7e9-ebea-45d3-8c8e-daa4f4e272c0" />

Compare:
<img width="1920" height="930" alt="image" src="https://github.com/user-attachments/assets/ee8575de-66e4-4f39-bed0-c3eea1a17bfd" />
<img width="1920" height="930" alt="image" src="https://github.com/user-attachments/assets/23584d5e-c96e-46c7-9497-fad5655ecd2e" />

#### Download/Backup Page:
<img width="1920" height="922" alt="image" src="https://github.com/user-attachments/assets/68517e4a-20af-498d-b719-e949fda300cb" />

#### About Page:
<img width="1920" height="925" alt="image" src="https://github.com/user-attachments/assets/9478825b-0676-4c87-8d07-2d3c52098ec0" />
<img width="1920" height="926" alt="image" src="https://github.com/user-attachments/assets/8f0bfd26-bac0-40e3-a047-cb50870d3589" />

### 📄 License
This project is licensed under the MIT License - see the [License](https://github.com/om-prakash-varma/TickTask?tab=MIT-1-ov-file#) file for details.

---
**_Consistency Made Simple._**
