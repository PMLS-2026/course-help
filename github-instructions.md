# Computational Biophysics: Assignment Workflow

## Getting Your Assignment

1. Click the GitHub Classroom assignment link (posted on Canvas)
2. GitHub creates your personal repository automatically
3. You'll see a link to your new repo—bookmark it

## Working on Assignments

### Option A: Google Colab (Recommended for Beginners)

1. Go to your assignment repo on GitHub
2. Click on the `.ipynb` notebook file
3. Click "Open in Colab" at the top
4. Work in Colab (data loads automatically when you run the starter cell)
5. **To save:** File → Save a copy in GitHub
   - Select your assignment repo
   - Write a brief commit message ("Completed problem 2" or "Final submission")
   - Click OK

### Option B: Local Development

1. Clone your repo: `git clone [your-repo-url]`
2. Work however you prefer (Jupyter, VS Code, Spyder, scripts)
3. **Submit as a Jupyter notebook** with your code, figures, and narrative
4. Commit and push:
   ```
   git add .
   git commit -m "Your message"
   git push
   ```

**For local developers creating submission notebooks:**
```python
# Load code from your script into a cell
%load my_script.py

# Or import and use results
from my_script import data, results

# Display saved figures
![](my_figure.png)
```

## What to Submit

**A single Jupyter notebook for each problem** containing:

- Your code (or key excerpts if you developed in scripts)
- Embedded figures and results
- Markdown cells with explanations and reflections

Think of the notebook as your scientific communication—not just code dump, but a readable presentation of your computational work. This is standard practice in computational science.

For problems that do not require Python code, you can submit a Jupyter notebook or you can add your work to your repository as a PDF.

## Getting Help

- Git issues? Ask in office hours, class, or on our class discussion forum.
- Can't find your repo? Check the Classroom assignment link again.
- Colab save not working? Make sure you're signed into GitHub in your browser.

For the fastest response, post your issues in our `course-help` repo:

<https://github.com/PMLS-2026/course-help>


