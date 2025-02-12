In this project, we:

● Utilized Python with Pandas, NumPy, Matplotlib, and Seaborn to acquire, preprocess, and visualize electrocardiogram (ECG) data from the MIT-BIH dataset. 

● Developed and trained machine learning models, including Random Forest and Support Vector Machine, to classify ECG signals into five distinct heartbeat types. 

● Built, optimized, and evaluated deep learning models, comprising CNN, CNN_BiLSTM, and attention-based CNN_BiLSTM, using Keras and Keras Tuner to achieve higher classification accuracy. 

● Leveraged Scikit-learn for model evaluation, employing metrics like accuracy, F1-score, precision, and recall, along with confusion matrices for detailed performance analysis. 

● Applied resampling techniques to address data imbalance and enhance model robustness.

● Downloaded data from Kaggle using the Kaggle API for project dataset acquisition. 

● Visualized model architectures and performance comparisons using Matplotlib and Seaborn to present findings effectively.

● Demonstrated proficiency in data science and machine learning principles through the complete project lifecycle, from data collection to model deployment.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
