# daily-task-planner-python-ui
🗓️ Daily Task Planner
A desktop task manager app built using Python 3.13 and PyQt5, designed to help users add, save, and delete tasks for specific dates using a calendar interface.

🧠 About the Project
This application allows users to:
   - View a monthly calendar
   - Select a specific date
   - Add new tasks to that date
   - Delete tasks
   - Save changes persistently (locally)
The intuitive interface makes it easy to manage daily to-do items in an organized manner.


🔧 How I Made It – Step-by-Step
1. Installed Python
    - Downloaded and installed Python 3.13 from the official website: https://www.python.org
    - Added Python to the system PATH

2. Installed and Set Up PyCharm
    - Downloaded and installed PyCharm IDE
    - Created a new Python project called DailyTaskPlanner

3. Installed Qt Designer
 - Opened Command Prompt and ran:
pip install pyqt5designer

 - Launched Qt Designer using:
pyqt5designer


🖌️ Designing the UI (Step-by-Step in Qt Designer)
1. Created a new Main Window in Qt Designer.

2. Added the following widgets to the UI:
     - QCalendarWidget (for calendar selection)
     - QLineEdit (to type new tasks)
     - QPushButton named btnAdd ("Add New")
     - QListWidget (to show the list of tasks)
     - Two QPushButtons below the task list:
               - btnSave ("Save Changes")
               - btnDelete ("Delete Changes")

3. Customized fonts, button colors, and layout for clarity and ease of use.

4.Saved the UI file as task.ui


💻 Core Functionalities
Feature        - 	Description
Add Task     -	Write in the text field and click "Add New"
Save Task    -	Tasks are saved for the selected calendar date
Delete Task  -	Select from the list and click "Delete Changes"
Calendar UI  -	Switch between months and select any date

🧑‍💻 Technologies Used
Python 3.13

PyQt5 (for UI)

Qt Designer (for UI design)

JSON / SQLite (for saving tasks) – depends on your storage logic


🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/daily-task-planner.git
cd daily-task-planner

2. Install required libraries
pip install PyQt5 pyqt5-tools

3. Run the app
python main.py

📂 File Structure

daily-task-planner/
├── main.py               # Main app file
├── task.ui               # UI file created using Qt Designer
├── task_manager.py       # Handles add/save/delete logic
├── README.md             # Project documentation

📌 Future Improvements
	- Task editing feature
	- Completed task marking
	- Notification/reminder system
	- Dark theme toggle

📝 License
This project is open-source under the MIT License.

🙋‍♀️ Author
Created by Khushi Singh.


