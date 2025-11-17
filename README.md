🚇 Delhi Metro Route & Fare Finder

A Python-based project built using Jupyter Notebook

📌 Overview

This project is an interactive Delhi Metro Route & Fare Finder built using Python.
It helps users:

Find the shortest route between any two Delhi Metro stations

Calculate the estimated fare

Display the total distance

Visualize the route with clear, step-by-step station navigation

The project uses graph-based algorithms and metro datasets to deliver accurate and useful travel information.

🚀 Features
🔹 Shortest Path Calculation

Uses graph traversal algorithms to find the most efficient route between stations.

🔹 Fare Estimation

Automatically calculates fare based on Delhi Metro pricing slabs.

🔹 Distance Calculation

Displays the total travel distance between starting and ending stations.

🔹 User-Friendly Output

Shows clean, readable results including the route, number of stations, interchange points, and total cost.

🔹 Modular & Scalable Code

All functions are organized in a modular structure so new stations or fare rules can be added easily.

🧠 Technologies Used

Python

Jupyter Notebook

NetworkX (if used) – for graph creation and shortest path algorithms

Pandas – for dataset handling

Matplotlib / Plotting Libraries (optional)

📂 Project Structure
📁 Delhi-Metro-Route-Finder
│
├── 📘 Delhi_Metro.ipynb        # Main Jupyter Notebook
├── 📄 stations.csv             # Dataset of metro stations (if used)
├── 📄 metro_graph.json         # Graph data (optional)
├── 📄 README.md                # Project documentation
└── 📁 assets/                  # Images or visuals (optional)

🔧 How to Run the Project
1. Clone the repository
git clone https://github.com/ugadityaa45/Delhi_Metro_Analysis.git 

2. Install required libraries
pip install pandas networkx matplotlib

3. Open the Jupyter Notebook
jupyter notebook

4. Run all cells

Follow the notebook instructions to input source and destination stations.

📝 Example Output
Starting Station: Rajiv Chowk
Destination Station: Huda City Centre

Shortest Route:
Rajiv Chowk → Patel Chowk → Central Secretariat → ... → Huda City Centre

Total Distance: 28.6 km
Estimated Fare: ₹40
No. of Interchanges: 1

📈 Future Enhancements

Live metro timing integration

Map-based route visualization

Real-time crowd density indicator

Mobile-friendly UI using Streamlit/Flask

🤝 Contributing

Contributions are always welcome!
Feel free to open issues or submit pull requests.

📞 Contact : ugadityaa@gmail.com

If you have any questions or suggestions, feel free to reach out.
