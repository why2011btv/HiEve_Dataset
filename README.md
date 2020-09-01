# HiEve_Dataset
This repo is a cleaned version of HiEve Dataset.<br>
You can find 100 documents in <a href="https://github.com/why2011btv/HiEve_Dataset/tree/master/hievents_v2/processed">hievents_v2/processed</a>. Each document contains multiple lines, e.g., Text, Event, and Relation (each followed by "\t" and contents).<br>
Illustration for line Event / Relation:<br>
Event&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;competing&nbsp;	&nbsp;&nbsp;&nbsp;occurrence&nbsp;&nbsp;&nbsp;&nbsp;98<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id&nbsp;&nbsp;&nbsp;&nbsp;mention&nbsp;&nbsp;&nbsp;&nbsp;type&nbsp;&nbsp;&nbsp;&nbsp;char_ID<br>  
Relation&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;Coref&nbsp;&nbsp;&nbsp;&nbsp;true&nbsp;&nbsp;&nbsp;&nbsp;competing&nbsp;&nbsp;&nbsp;&nbsp;race<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id1&nbsp;&nbsp;&nbsp;&nbsp;id2&nbsp;&nbsp;&nbsp;&nbsp;relation&nbsp;&nbsp;&nbsp;&nbsp;uncertain&nbsp;&nbsp;&nbsp;&nbsp;mention1&nbsp;&nbsp;&nbsp;&nbsp;mention2<br>
Transitive closure has been applied to generate labels for relations not annotated in the dataset (as shown in <a href="https://github.com/why2011btv/HiEve_Dataset/blob/master/HiEve_Preprocess.ipynb">HiEve_Preprocess.ipynb</a>).<br>
You might downsample NoRel by a certain ratio (e.g., 40%) following previous work.
