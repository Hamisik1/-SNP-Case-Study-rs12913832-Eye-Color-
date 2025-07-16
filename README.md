# 👁️ SNP rs12913832 — Eye Color Frequency Across Populations

This project analyzes the **allele frequency** of SNP `rs12913832`, which is associated with **eye color (brown vs blue)**, across global populations using:

- 🔬 [1000 Genomes Project](https://www.internationalgenome.org/)
- 💻 Amazon Athena + PyAthena
- 📊 Jupyter Notebook + Matplotlib

---

## 📁 Files

- `snp_analysis_rs12913832.ipynb` — Full code, SQL, and visualizations  
- `rs12913832_eye_color_snp.png` — Bar chart: allele frequency across populations  
- `requirements.txt` — List of Python dependencies

---

## 🔍 Key Insight

This SNP is **far more common in European populations (63.62%)**  
than in East Asians (0.2%) or Africans (2.8%), explaining regional differences in eye color.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/Hamisik1/SNP-Case-Study-rs12913832-Eye-Color.git
cd SNP-Case-Study-rs12913832-Eye-Color

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook snp_analysis_rs12913832.ipynb

💡 Make sure your AWS credentials are set up and you have access to Athena + S3 if you're querying live data.

📬 Contact
Created by Kelly Hamisi-McGuya
📧 Email: kellyhamisi0@gmail.com
