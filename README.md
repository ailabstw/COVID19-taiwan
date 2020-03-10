# COVID19 Taiwan NHI Drug Data Repository by Taiwan AI Labs Intelligent Medical Genomics Team

## COVID19 基因組結構名稱，總共24個蛋白質體
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

:sparkles: 我們現階段已經完成 docking **3CL-protease**、**RdRp**、**Helicase** 及 **Spike protein**。

### 健保藥物結果

從健保藥物的清單中總共取得 2,832 個不同的藥物 ( 187,489 種商品 )，分成 3CL-Protease、RdRp、Helicase 及 Spike protein 進行 docking 50次，取2倍標準差外的數值結果。
* 3CL-Protease 篩選出 **13** 種最好的藥物 (176種商品)
* RdRp inhibitor 篩選出 **10** 種最好的藥物 (588種商品)
* Helicase inhibitor 篩選出 **11** 種最好的藥物 (47種商品)
* Spike protein 篩選出 **5** 種最好的藥物 (34種商品)

:pill: 如果您對台灣的健保藥物有興趣，我們提供完整的清單可以自行下載，[申請連結](https://forms.gle/62exURZBf2ZLDYuk9)
 
### FDA 藥物結果
從 [ZINC15](http://zinc15.docking.org/) 取得 1,615 個不同的藥物，其中有570藥物與台灣健保藥物重複，我們提供 3CL-Protease、RdRp、與 Helicase docking binding affinity 結果。

---
## Publication:

* Chang, Y.; Tung, Y.; Lee, K.; Chen, T.; Hsiao, Y.; Chang, H.; Hsieh, T.; Su, C.; Wang, S.; Yu, J.; Shih, S.; Lin, Y.; Lin, Y.; Tu, Y.E.; Hsu, C.; Juan, H.; Tung, C.; Chen, C. [Potential Therapeutic Agents for COVID-19 Based on the Analysis of Protease and RNA Polymerase Docking.](https://www.preprints.org/manuscript/202002.0242/v2) *Preprints* **2020**, 2020020242

---
## Tools:
* [TAIGenomics](https://www.taigenomics.com/console/wuhan/)
* V2L [variant2literature](https://v2l.taigenomics.com/)

---
## Data sources:

* [台灣衛生福利部中央健康保險署](https://www.nhi.gov.tw/QueryN/Query1.aspx)
* [台灣衛生福利部中央健康保險署 健保藥品品項查詢](https://www.nhi.gov.tw/Content_List.aspx?n=238507DCFE832EAE&topn=3FC7D09599D25979)
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

這個GitHub存儲庫及其內容，包括所有釋出數據、藥物資料分析結果版權為台灣人工智慧實驗室所有，保留所有權利，僅提供公眾教育與學術研究使用。我們所使用的藥物資訊來自多個公開可用資料庫，這些資料的內容並非一致。台灣人工智慧實驗室特此聲明，對結果不做任何聲明和保證，包括準確性，適用性和適銷性。本研究結果採創用CC授權條款[姓名標示─非商業性─相同方式分享 4.0 國際 \(CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.zh-Hant#languages)