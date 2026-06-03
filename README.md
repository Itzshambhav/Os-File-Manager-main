# 💽 OS File Manager & Disk Defragmentation Simulator

A Python-based Operating System File Manager and Disk Defragmentation Simulator built using Flask. This project simulates disk block allocation, fragmentation, defragmentation, file compression, and storage utilization visualization through an interactive web interface.

---

# 🚀 Features

- 💽 Disk block allocation simulation
- 📂 File and folder management
- 🧩 Fragmentation detection and analysis
- ⚡ Disk defragmentation simulation
- 📊 Disk utilization monitoring
- 🗜️ File and folder compression support
- 📄 Defragmentation report generation
- 🌐 Interactive Flask web interface
- 🎯 Random file allocation simulation

---

# 🛠️ Tech Stack

## Backend
- Python
- Flask

## Frontend
- HTML
- CSS
- JavaScript

## Libraries & Tools
- ZipFile
- OS Module
- Random
- Shutil

---

# 📂 Project Structure

```bash
OS-File-Manager/
│── app.py
│── disk.py
│── defragmenter.py
│── file_manager.py
│── templates/
│── static/
│── uploads/
│── extracted/
│── compressed/
│── reports/
│── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/OS-File-Manager.git
cd OS-File-Manager
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install flask
```

---

# ▶️ Run the Application

```bash
python app.py
```

Application will start at:

```bash
http://127.0.0.1:5000
```

---

# 💽 Functionalities

## 📂 File Allocation

- Allocates files into disk blocks
- Simulates fragmented storage allocation
- Tracks allocated block indexes

---

## 🧩 Fragmentation Analysis

- Calculates fragmentation score
- Detects non-contiguous block allocations
- Displays storage utilization statistics

---

## ⚡ Disk Defragmentation

- Rearranges fragmented blocks contiguously
- Optimizes disk allocation
- Generates defragmentation reports

---

## 🗜️ Compression Support

- Compress files and folders into ZIP format
- Download compressed archives directly
- Supports directory extraction

---

# 🔐 How It Works

1. Upload ZIP files or allocate file paths
2. Files are assigned random disk blocks
3. Fragmentation score is calculated
4. Disk utilization is visualized
5. Defragmentation reorganizes storage blocks
6. Reports are generated automatically

---

# 📊 Core Concepts Used

- Operating System Memory Management
- File Allocation Techniques
- Disk Scheduling Concepts
- Fragmentation & Defragmentation
- Storage Simulation
- File Compression

---

# 📸 Applications

- Operating System learning projects
- Disk scheduling visualization
- Storage allocation simulation
- Educational OS demonstrations
- File system management concepts

---

# 📈 Future Improvements

- Animated disk visualization
- Drag-and-drop file management
- Real-time fragmentation graphs
- Multi-user support
- Database integration
- Cloud storage simulation

---

# 🤝 Contributing

Contributions are welcome.

```bash
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request
```



---

# 👨‍💻 Author

**Shambhav Kumar**

- GitHub: https://github.com/Itzshambhav
- LinkedIn: https://linkedin.com/in/shambhav-kumar-2aaa30212
