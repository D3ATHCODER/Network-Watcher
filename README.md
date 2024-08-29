# Network-Watcher
Network Watcher is a Python-based GUI app for real-time monitoring of your computer’s network and system performance. It features a secure login, displays IP address, port number, device name, available Wi-Fi networks, CPU/memory usage, and upload/download speeds, all built using PyQt5, psutil, socket, and pywifi.



What This Application Does
Login Screen: When you start the application, you’ll see a login screen where you need to enter a username and password. Only if you enter the correct details (username: "user", password: "password"), you’ll be allowed to access the main features of the app. This is handled by the LoginWindow class in the code.
Network and System Info: After logging in, you’ll see information about your computer’s network and system. This includes:
Port Number and IP Address: The app shows which port your computer is using and its IP address. This is done using the socket library, which helps fetch this network information.
Device Name: The app displays the name of the device you’re using, which is fetched from your computer’s settings.
Available Wi-Fi Networks: It lists all the Wi-Fi networks around you using the pywifi library. This is like what you see when you click on the Wi-Fi icon on your computer.
CPU and Memory Usage: The app shows how much of your computer’s processing power (CPU) and memory (RAM) is currently being used. The psutil library in Python helps in gathering this data.
Upload and Download Speeds: It also tells you how fast data is being uploaded and downloaded over your network.
Refresh Button: There’s a "Refresh" button that you can click to update all the information in real-time.
Logout: If you want to go back to the login screen, there’s a "Logout" button that hides the network info and takes you back to where you started.

How This Was Built
PyQt5: This is the toolkit that was used to create the visual parts of the app, like buttons, text boxes, and labels. It’s what makes the app look and feel user-friendly.
psutil: A tool that provides details about your computer’s hardware, like how much of the CPU and memory is being used.
socket: This helps the app figure out the IP address and port number of your computer.
pywifi: This tool scans the area around your computer to find Wi-Fi networks, just like how your phone shows available networks.
Python: The programming language used to write all the code that makes this app work.
sys: Used for handling some system-specific tasks, like making sure the app closes properly when you exit.
