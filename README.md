Dynamic Memory Management Visualizer
📌 Description
This project implements a Dynamic Memory Management Visualizer using Python, Tkinter, and Matplotlib. It simulates and visualizes different memory management techniques like Paging, Segmentation, and Virtual Memory. The tool provides a graphical user interface (GUI) for users to input their data and visualize memory allocation and page replacement processes.

✨ Features
Paging Simulation: Demonstrates FIFO and LRU page replacement algorithms.
Segmentation Simulation: Visualizes memory allocation for segments.
Virtual Memory Simulation: Simulates memory allocation and page faults using a simple replacement algorithm.
Real-Time Visualization: Displays memory state changes dynamically for better understanding.
User-Friendly GUI: Built with Tkinter for easy user interaction.
🔧 Requirements
Python 3.x
matplotlib (pip install matplotlib)
tkinter (included with Python standard library)
📂 Usage
Clone the repository and navigate to the project directory.
Install the required packages using:
bash
Copy code
pip install matplotlib
Run the program using:
bash
Copy code
python your_script_name.py
Input your values for Pages, Frame Count, Memory Size, and Segment Sizes in the GUI.
Choose the desired simulation type (FIFO & LRU, Segmentation, Virtual Memory).
📊 Visualization
The program generates graphical representations of memory states using Matplotlib, with Gantt chart-like visuals for page allocation and segmentation.

📌 Example Inputs
Pages (comma-separated): 1,2,3,4,1,2,5,1,2,3,4,5
Frame Count: 3
Memory Size (for Segmentation): 100
Segment Sizes (comma-separated): 30,20,40
