# 🌳 Decision Tree Classifier Visualizer  

A **Streamlit web app** to interactively train and visualize a **Decision Tree Classifier** on a synthetic dataset (`make_moons`).  
Adjust hyperparameters from the sidebar, see real-time accuracy, and explore decision boundaries with ease.  

👉 **Live Demo:** [Decision Tree Classifier App](https://decision-tree-classifier-app-k4qfnhukt6jwfltvxk49uu.streamlit.app/)  

---

## ✨ Features
- 🎛️ **Interactive Controls** for Decision Tree parameters:
  - Criterion: `gini` / `entropy`  
  - Splitter: `best` / `random`  
  - Max Depth  
  - Min Samples Split  
  - Min Samples Leaf  
  - Max Features  
  - Max Leaf Nodes  
  - Min Impurity Decrease  
- 📊 Real-time **decision boundary visualization**  
- ✅ Display of **test set accuracy**  
- 🌲 Tree structure visualization with **Graphviz**  

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/decision-tree-visualizer.git
cd decision-tree-visualizer
Create and activate a virtual environment (recommended):
python -m venv venv
# On Mac/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
▶️ Usage
Run the Streamlit app:
streamlit run app.py
Then open the local URL shown in your terminal:
👉 Default: http://localhost:8501
📂 Project Structure
decision-tree-visualizer/
│
├── app.py              # Main Streamlit app
├── requirements.txt    # Dependencies
├── README.md           # Documentation
🌐 Live Project
Check out the deployed app here:
👉 Decision Tree Classifier Visualizer
✨ Built with Python, Streamlit, scikit-learn, and Graphviz

Would you like me to also create a **badges section** (e.g., Python version, Streamlit Cloud status, License) at the top to make it look even more professional for GitHub?