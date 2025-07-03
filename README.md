
markdown
Copy
Edit
# 🧠 Linux Kernel Process Scheduler Visualizer

A Jupyter Notebook-based visual simulator for understanding **Linux process scheduling algorithms** such as **Round Robin (RR)** and **Completely Fair Scheduler (CFS)**. This project helps students, educators, and enthusiasts visualize how process scheduling works inside the Linux kernel.

---

## 📌 Features

- ✅ Simulates Round Robin (RR) scheduling
- ✅ Simulates Completely Fair Scheduler (CFS)
- ✅ Gantt chart visualizations of CPU execution
- ✅ Interactive process input with custom time slices and priorities
- ✅ Comparison of scheduling outcomes and metrics

---

## 📂 Project Structure

Linux_Kernel_Process_Scheduler_Visualizer/
│
├── Linux_Kernel_Process_Scheduler_Visualizer.ipynb # Main notebook
├── images/ # Output charts/screenshots
├── sample_inputs/ # Example process datasets
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## ⚙️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Matplotlib 📊
- NumPy 🔢
- Pandas 🐼

---

## ▶️ Getting Started

### 1. Clone the repository

git clone https://github.com/your-username/linux-scheduler-visualizer.git
cd linux-scheduler-visualizer
2. Create and activate virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
4. Launch the notebook
jupyter notebook Linux_Kernel_Process_Scheduler_Visualizer.ipynb

📈 Sample Output
RR Gantt Chart: Visual representation of time-sliced CPU execution.

CFS Gantt Chart: Weighted fair distribution based on priorities.

Metrics: Turnaround Time, Waiting Time, CPU Utilization.

🧠 Educational Value
This tool is perfect for:

Operating Systems coursework

CS Labs and demos

Understanding Linux internals

Debugging and comparing scheduling strategies

💡 Future Improvements
Add FCFS and Priority Scheduling

Real-time input with interactive widgets

Export simulation results (CSV/Excel)

Web-based interface (e.g., Streamlit or Flask)

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📄 License
This project is licensed under the MIT License.

