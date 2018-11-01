# NDN-IFA-FeatureSelection
### IFAAll.zip contains code, data files, results, and weka classifier (.kf) files.
### Code files are present in: IFAAll/IFACode
- Here topology files are: DFN.txt and tree.txt
- Here code files are: ndn-dfn.cc  and ndn-tree.cc 
- Information for the execution is given in README
Data files are present in: IFAAll/IFADataFiles which contains three folders: AttackEffect, DetectionData, and wekaNetwork
- AttackEffect folder contains two folder: DFN and Tree
  - DFN folder contains data related to DFN topology which is used for plotting the graph of the feature, satisfaction ratio, and PIT size.
  - Similarly, Tree folder contains data related to Tree topology.
- DetectionData folder contains two folder: DFN and Tree
  - DFN folder contains three folders: Compagno, Afanasyev, and My.
    - Compagno: It contains data and result related to Compagno et al. approach
    - Afanasyev: It contains data and result related to Afanasyev et al. approach
    - My: It contains data and results related to our approach
  - Similarly, Tree folder contains data and result related to Tree topology.
- wekaNetwork folder contains .kf file which can be imported in weka.
