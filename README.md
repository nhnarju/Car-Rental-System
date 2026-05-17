Car Rental Management System in C (CLI + GTK)
This project is a Car Rental Management System built entirely in C language.
It includes two versions:

Terminal-based version (CLI) – runs on console
GUI version (GTK) – built using GTK library for graphical interface
Project Overview
The project helps manage car rental operations such as car registration, customer management, and rental tracking.
It was created to practice C programming, file handling, and GUI development with GTK.

Features
Add, edit, delete, and view car records
Manage customer details
Record and track rental transactions
Check car availability
File-based data storage system (text/binary)
Two interfaces:
CLI Version → Simple terminal-based system
GTK GUI Version → User-friendly graphical window system
File Structure
car-rental-system/ ├── cli/ │ ├── main.c │ ├── car.c │ ├── car.h │ ├── customer.c │ ├── customer.h │ ├── rental.c │ ├── rental.h │ └── admin_car_management.c and all other files

├── gui/ │ ├── main_gui.c │ ├──admin_dashboard_gui.c │ ├── admin_dashboard_gui.h │ └── gui │ ├ │ │ ├── screenshots/ │ ├── cli-demo.png │ └── gui-demo.png └── README.md

🛠️ Tools & Technologies
Language: C
Framework: GTK (for GUI version)
Compiler: GCC
IDE: VS Code / Code::Blocks
OS: Windows / Linux
How to Run
CLI Version
Open the cli/ folder in terminal.
Compile:
gcc main.c car.c customer.c rental.c etc. -o car_rental
Run:

bash Copy code ./car_rental 🪟 GUI Version (GTK) Make sure GTK 3+ is installed.

Open the gui/ folder.

Compile:

bash Copy code gcc main_gui.c gui_helpers.c pkg-config --cflags --libs gtk+-3.0 -o car_rental_gui Run:

bash Copy code ./car_rental_gui Learning Goals Practice modular C programming using .h and .c files

Learn file handling for data persistence

Implement GUI programming using GTK

Strengthen portfolio with a real-world project

License This project is open source under the MIT License.

Author Naimun Hasan Narju - B.Sc. in Computer Science and Engineering (CSE)
