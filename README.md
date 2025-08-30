# 🌳 Decision Tree Classifier Visualizer

This is a **Streamlit web app** that allows you to interactively train and visualize a **Decision Tree Classifier** on a synthetic dataset (`make_moons`).  
You can adjust hyperparameters (criterion, splitter, max depth, etc.) from the sidebar, visualize decision boundaries, and see model accuracy in real-time.

---

## 🚀 Features
- Adjustable Decision Tree parameters from the sidebar:
  - Criterion: `gini` / `entropy`
  - Splitter: `best` / `random`
  - Max Depth
  - Min Samples Split
  - Min Samples Leaf
  - Max Features
  - Max Leaf Nodes
  - Min Impurity Decrease
- Interactive plot of decision boundaries
- Displays test set accuracy
- Visualizes the Decision Tree structure using **Graphviz**

---

## 🛠️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/decision-tree-visualizer.git
cd decision-tree-visualizer
Create and activate a virtual environment (recommended):
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
Install dependencies:
pip install -r requirements.txt
▶️ Usage
Run the Streamlit app:
streamlit run app.py
Then open the local URL shown in your terminal (default: http://localhost:8501).
📂 Project Structure
decision-tree-visualizer/
│
├── app.py                 # Main Streamlit app
├── requirements.txt       # Dependencies
├── README.md              # Documentation
