🗺️ Shortest Path Finder
A simple web application that helps users find the shortest path between two locations on the IIT Guwahati campus. Designed to assist students and visitors in navigating the campus easily!

✨ Features
🔢 Displays the shortest distance between selected source and destination.

🧭 Shows the exact path (in terms of numbered nodes) to follow for the minimum distance.

📡 API Reference
🔍 Get shortest distance and path between two nodes
http
Copy
Edit
GET /shortd/<int:A>/<int:B>
Parameter	Type	Description
A (source)	integer	Required — starting point
B (destination)	integer	Required — end point

🧰 Tech Stack
Frontend: React
Backend: Python, Flask

🎓 Used By
This project can be used by:

👨‍🎓 Students of IIT Guwahati

❓ FAQ
🔹 How do I get the shortest path?
Every location on campus is mapped to a number from 1 to 64.
To find a path:

Select the source and destination nodes.

The app will display the shortest path using those node numbers in order.

