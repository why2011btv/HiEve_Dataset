# HiEve_Dataset
This repo is a cleaned version of HiEve Dataset.<br>
You can find 100 documents in <a href="https://github.com/why2011btv/HiEve_Dataset/tree/master/hievents_v2/processed">hievents_v2/processed</a>. Each document contains multiple lines, e.g., Text, Event, and Relation (each followed by "\t" and contents).<br>
Transitive closure has been applied to generate labels for relations not annotated in the dataset (as shown in <a href="https://github.com/why2011btv/HiEve_Dataset/blob/master/HiEve_Preprocess.ipynb">HiEve_Preprocess.ipynb</a>).<br>
You might downsample NoRel by a certain ratio (e.g., 40%) following previous work.
