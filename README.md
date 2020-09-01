# HiEve_Dataset
This repo is a cleaned version of HiEve Dataset.<br>
You can find 100 documents in <a href="https://github.com/why2011btv/HiEve_Dataset/tree/master/hievents_v2/processed">hievents_v2/processed</a>. Each document contains multiple lines, e.g., Text, Event, and Relation (each followed by "\t" and contents).<br>
Illustration for line Event / Relation:<br>
Event	1	 competing	Occurrence	98<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id,mention,   type,       char_ID<br>  
Relation	1   2	  Coref	    true	    competing	race<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id1, id2, relation, uncertain,mention1, mention2<br>
Transitive closure has been applied to generate labels for relations not annotated in the dataset (as shown in <a href="https://github.com/why2011btv/HiEve_Dataset/blob/master/HiEve_Preprocess.ipynb">HiEve_Preprocess.ipynb</a>).<br>
You might downsample NoRel by a certain ratio (e.g., 40%) following previous work.
