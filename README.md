# truely-ML
truely-ML first ever foundations of Machine learning and Ai


# Dog vs Cat Classifier 🐶🐱

A simple demo using a random linear classifier to separate dog and cat data based on whisker length and flappiness index.






# Clone the repo
git clone your-repo-url

# Go into the project directory
cd your-project

# Create virtual env
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

# Install dependencies
```bash
pip install -r requirements.txt

```





Thanks for sharing the screenshot — this confirms that VS Code is currently **not detecting your virtual environment** in the interpreter list. It's only showing **global interpreters** (Python 3.13 and 3.12).

---

### ✅ Here's how to make your `venv` appear in the list (and in kernel options):

#### ✅ Step 1: Activate your virtual environment manually

If your virtual environment is named `venv` and lives inside your project directory:

Open terminal in VS Code, then run:

```bash
# Windows CMD or PowerShell:
venv\Scripts\activate
```

If you don't have one yet, create it:

```bash
python -m venv venv
venv\Scripts\activate
```

---

#### ✅ Step 2: Install `ipykernel` inside the venv

Once it's activated, run:

```bash
pip install ipykernel
```

---

#### ✅ Step 3: Register your venv as a Jupyter kernel

```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

---

#### ✅ Step 4: Restart VS Code

Close and reopen VS Code completely (not just the notebook tab).

---

#### ✅ Step 5: Open your `.ipynb` and select the kernel

Click the **kernel name in the top-right** of the notebook (next to ⚙️), and you should now see:

```
Python (venv)
```

---

Let me know if you want help navigating to the exact path of your `venv\Scripts\activate` or if you're unsure where your environment was created.





