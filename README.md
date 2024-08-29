#Network-Watcher
Network Watcher is a Python-based GUI application designed to monitor your computer's network and system performance in real-time. It features a secure login, and displays IP address, port number, device name, available Wi-Fi networks, CPU/memory usage, and upload/download speeds. The app is built using Tkinter, psutil, socket, and pywifi.

What This Application Does
Login Screen:When you start the application, a login screen prompts you to enter a username and password. If you enter the correct credentials (username: "user") password: ("password"), you'll gain access to the main features of the app. This is managed by the LoginWindow class.
Network and System Info:After logging in, the app provides detailed information about your computer’s network and system performance
Port Number and IP Address: Displays the active port number and IP address using the socket library.
Device Name: Shows the name of the device you’re using, fetched from your computer’s settings.
Available Wi-Fi Networks: Lists all nearby Wi-Fi networks using the pywifi library.
CPU and Memory Usage: Displays the current CPU and memory (RAM) usage, gathered using the psutil library.
Upload and Download Speeds: Shows real-time data upload and download speeds.
Refresh Button:A "Refresh" button allows you to update all the displayed information in real-time. While the data refreshes, a loading indicator informs you that the process is ongoing.
Logout:The "Logout" button lets you return to the login screen, hiding the network information.

How This Was Built
Tkinter: The graphical user interface (GUI) toolkit used to create the app's visual components, like buttons, text boxes, and labels.
psutil: A library that retrieves details about your computer's CPU and memory usage.
socket: Used to determine the IP address and port number of your computer.
pywifi: A library that scans for nearby Wi-Fi networks, similar to how your computer shows available networks.
Python: The programming language used to write all the code that powers this app.
sys: Helps handle system-specific tasks, like properly closing the app when you exit.
