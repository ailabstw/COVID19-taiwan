# COVID19-taiwan NHI Drug Data Repository by Tawian AI Labs Intellgent Medical Genomics Team

![image](https://github.com/ailabstw/COVID19-taiwan/blob/master/pic/protease.gif)

## COVID19 genome structure, a total of 24 protein.

- [x] 3CL-protease inhibitor (3CL-Pro)
- [x] RNA-dependent RNA polymerase (RdRp) inhibitor
- [x] Helicase inhibitor (Hel)
- [x] Spike protein
- [ ] Papain-like protease
- [ ] nsp1
- [ ] Non-structureal protein 2 (nsp2)
- [ ] Non-structureal protein 4 (nsp4)
- [ ] Non-structureal protein 6 (nsp6)
- [ ] Non-structureal protein 7 (nsp7)
- [ ] Non-structureal protein 8 (nsp8)
- [ ] Non-structureal protein 9 (nsp9)
- [ ] Guanine-N7 methyltransferase (ExoN)
- [ ] Uridylate-specific endoribonuclease (NendoU)
- [ ] 2'-O-methyltransferase (2'-O-MT)
- [ ] Surface glycoprotein (S)
- [ ] ORF3a
- [ ] E. protein
- [ ] M. protein
- [ ] ORF6.
- [ ] ORF7a.
- [ ] ORF8.
- [ ] N. protein
- [ ] ORF10.
- [ ] ACE2 protein (for Human)

:sparkles: We have completed docking for **3CL-protease**, **RdRp**, **Helicase** and **Spike protein**.

### NHI Drug Docking Results

A total of 2,832 different drugs (187,489 products) were obtained from the list of NHI durgs, divided into 3CL-Protease, RdRp, Helicase, and Spike protein for docking 50 times, and the numerical results outside two standard deviations were taken.

* 3CL-Protease screened out **13** best drugs (176 products)
* RdRp inhibitor screened **10** best drugs (588 products)
* Helicase inhibitor screened out **11** best drugs (47 products)
* Spike protein screened out **5** best drugs (34 products)

:pill: If you are interested in NHI drugs in Taiwan, we provide a complete list to download on your own. [Please apply.](https://forms.gle/62exURZBf2ZLDYuk9)

### FDA Drug Docking Results

Obtained 1,615 different FDA drugs from [ZINC15](http://zinc15.docking.org/), of which 570 drugs were overlap with NHI drugs. We provide 3CL-protease, RdRp, and binding affinity results for docking with helicase.

:mega: Add [ZINC compound structure](https://github.com/ailabstw/COVID19-taiwan/blob/master/release/TW_AI_Labs_FDA_1615_ZINC15_50_times_docking_with_compound_structure_release.xlsx).
* We appreciate [@hsiaoyi0504](https://github.com/hsiaoyi0504/COVID19-taiwan/tree/jupyter_notebook) use [RDKit](https://www.rdkit.org/) to assist in generating the compound structure and provide [jupyter notebook view](https://github.com/hsiaoyi0504/COVID19-taiwan/blob/jupyter_notebook/Untitled.ipynb).

---
## Publication:

* Chang, Y.; Tung, Y.; Lee, K.; Chen, T.; Hsiao, Y.; Chang, H.; Hsieh, T.; Su, C.; Wang, S.; Yu, J.; Shih, S.; Lin, Y.; Lin, Y.; Tu, Y.E.; Hsu, C.; Juan, H.; Tung, C.; Chen, C. [Potential Therapeutic Agents for COVID-19 Based on the Analysis of Protease and RNA Polymerase Docking.](https://www.preprints.org/manuscript/202002.0242/v2) *Preprints* **2020**, 2020020242

---
## Tools:

* [TAIGenomics](https://www.taigenomics.com/console/wuhan/)
* V2L [variant2literature](https://v2l.taigenomics.com/)

---
## Data sources:

* [National Health Insurance Administration, Ministry of Health and Welfare](https://www.nhi.gov.tw/QueryN/Query1.aspx)
* [National Health Insurance Administration, Ministry of Health and Welfare, Health Insurance Drug Item Search](https://www.nhi.gov.tw/Content_List.aspx?n=238507DCFE832EAE&topn=3FC7D09599D25979)
* [Drug Bank](https://www.drugbank.ca/) 
* [RCSB Protein Data Bank](https://www.rcsb.org/)
* [ZINC15](http://zinc15.docking.org/)
* [Structure models of all mature peptides in COVID19 genome by C-I-TASSER](https://zhanglab.ccmb.med.umich.edu/C-I-TASSER/2019-nCov/)

---
## Contributors:

* Taiwan AI Labs Intelligent Medcial Genomics Team
    * AI Labs Founder
        * **Ethan Tu** 
    * Professor
        * **Dr. Chien-Yu Chen** (Department of Biomechatronics Engineering, National Taiwan University) 
    * Project Manager
        * **Dr. Yin-Hung Lin**
    * Business Development Manager
        * **Philippe, Yu-Hsiang Lin**
    * Algorithm Engineer
        * **Dr. Chester, Yu-Chuan Chang**
        * **Yi-An Tung**
        * **MD. Ko-Han Lee**
        * **Ting-Fu Chen**
        * **Yu-Chun Hsiao**
        * **Hung-Ching Chang**
        * **Tsung-Ting Hsieh**
        * **Shang-Shung Shih**
    * System Engineer
        *  **Rey, Chan-Hung Su**
        *  **Amber, Su-Shia Wang**
        *  **Jerry, Jheng-Ying Yu**

* Graduate Institute of Data Science, College of Management, Taipei Medical University
    * Professor
        * **Dr. Chun-Wei Tung**

* Department of Life Science, National Taiwan University
    * Professor
        * **Dr. Hsueh-Fen Juan and J&H Systems Bio Lab**

* Department of Agricultural Chemistry, National Taiwan University
    * Professor
        * **Dr. Chun-Hua Hsu**

* Institute of Biotechnology and Pharmaceutical, National Health Research Institute
    * Investigator
      * **Dr. Chiung-Tong Chen**
      * **Dr. Ming-Shir Hung**
      * **Dr. Hsing-Pang Hsieh**

* Institute of Biomedical Sciences, Academia Sinica
    * Professor
        * **Dr. Ming-Jing Hwang**

---
## Contace Us:

* Email: [Philippe Lin](philippe.lin@ailabs.tw)

---
## Terms of Use:
This GitHub repo and its contents herein, including all data and analysis, copyright 2020 Taiwan AI Labs, all rights reserved, is provided to the public strictly for educational and academic research purposes. The drug information we use comes from multiple publicly available databases, and the content of these materials is not consistent. Taiwan AI Labs now declares that it makes no representations or warranties regarding the results, including accuracy, applicability, and marketability. This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License \(CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).