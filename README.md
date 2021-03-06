#### ingredients
├ phenotype.hpoa (downloaded from HPO)  
├ CTD_diseases.tsv.gz (downloaded from CTD)  
├ desc2021.xml (downloaded from MeSH)  
├ folder Pubmed_original (downloaded from Pubmed)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ pubmed21n0001.xml.gz  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ ...  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ pubmed21n1062.xml.gz  
├ folder UMLS2021AB(downloaded UMLS data)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ MRFILES.RRF.gz  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ MRSTY.RRF.gz  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ MRCONSO.RRF.aa.gz  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ MRCONSO.RRF.ab.gz  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ SRFIL  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ SRDEF  
├ folder_01 (for output code 01)  
├ folder_02 (for output code 02)  
├ folder_03 (for output code 03)  
├ folder_04 (for output code 04, 05, 07)  
├ folder_05  (for output code 08, 09, 10, 11, 12)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├ category.csv 
#### previous versions
-> ./old/{previous version file}
 - 00_MeSH_xml.ipynb  
-> 00_mesh_xml_読込.ipynb  
&nbsp;
 - 01_XMLをメッシュ単位に分割（Descriptor１個Qualifier１個）.ipynb  
-> 01_cxv_From_xml.ipynb  
&nbsp;
 - 02_2021疾患タームに該当するものを取り出しさらにこの中からMajorTopicがYもしくはNYのものを取り出してcsv保存.ipynb  
   03_2021症状タームに該当するものを取り出してcsv保存.ipynb  
   04_2021疾患csvを一つにまとめる.ipynb  
   05_2021症状csvを一つにまとめる.ipynb  
   06_全文献の文献数と出版日.ipynb  
   07_update_ver作成_基礎統計.ipynb  
-> 02_疾患MeSH症状MeSHの共起ペア作成_基礎統計.ipynb  
&nbsp;
 - 08_共起ペア作成からχ二乗検定を用いたペアカットまで.ipynb  
-> 03_χ二乗検定を用いたペアカット.ipynb  
&nbsp;
 - 09_TFIDF_コサイン類似度計算_ネットワーク.ipynb  
   10_ベンチマークネットワークHPO作成.ipynb  
   13_TFIDF_コサイン類似度計算_ネットワーク_all(uncut) pairs.ipynb   
-> 04_ネットワーク作成.ipynb  
&nbsp;
 - 11_２つのネットワークを比較.ipynb  
-> 05_ベンチマークネットワーク作成と比較.ipynb  
&nbsp;
 - 12_リンクがある疾患を臓器別に分類.ipynb  
-> 07_20210915依頼_カットして残ったペアからHSDN作成_1966-最新_MeSH2021.ipynb  
&nbsp;
 - 14_semantic_mapping.ipynb  
-> 06_2021AB.ipynb  