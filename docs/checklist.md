# Notebook Execution Checklist

1. Activate the project environment

   ```powershell
   cd "C:\Users\percy\Documents\studies\visual_studio_code\PhD-chapter4-SUHII-vegetation"
   .\.venv\Scripts\Activate.ps1
   ```

2. Install dependencies if not already installed

   ```powershell
   python -m pip install -r requirements.txt
   ```

3. Open the notebook

   - `notebook/01_suhii_vegetation_analysis.ipynb`

4. Review the notebook sections

   - Data loading and inspection
   - Vegetation metric calculations
   - SUHII analysis and visualization
   - Export results to `output/`

5. Save generated output to `output/`

6. Commit your work to Git

   ```powershell
   git add .
   git commit -m "Add Chapter 4 vegetation analysis notebook and docs"
   ```
