# Learn Language With Pony

**Learn vocabulary every day by uploading photos of your surroundings with our object detection solution.**

<br></br>
<p align="center">
  <video src="https://user-images.githubusercontent.com/35249776/209759695-a5b84563-f94e-45f0-8a5d-7551371e7c7c.mp4" width=250/>
<p/>
<br></br>





## Method
<p align="center">
<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Flowchart1.png" alt="drawing" width="700" align='center'/>
</p>

Problems | Proposed solutions
:-- | :-- 
Lack of linkages between the environment and learning language. | Learn the vocabulary around you.
Learning a language is known to be a boring process. | Interactivity + gaming.
Points 1 and 2 often lead to the dissatisfying achievement after years of learning language. |Increase learning efficiency through game.





<p align="center">
<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony1.png" alt="drawing" width="500" align='center'/>&nbsp;&nbsp;<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony6.png" alt="drawing" width="500" align='center'/>
<br></br>
<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony2.png" alt="drawing" width="500" align='center'/>&nbsp;&nbsp;<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony3.png" alt="drawing" width="500" align='center'/>
<br></br>
<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony4.png" alt="drawing" width="500" align='center'/>&nbsp;&nbsp;<img src="https://github.com/Jerry-Tse/Learn_Language_With_Pony/blob/main/Images/Pony5.png" alt="drawing" width="500" align='center'/>
</p>



## Download Word2vec weights

from gensim.models import KeyedVectors

import gensim.downloader as api

model = api.load("")

model.save("word2vec.model")

It's should be save the word2vec.model and word2vec.model.vecors.npy

## Download YOLO weights.

https://ppt.cc/fLvgmy


## Weights location

Put the word2vec.model, word2vec.model.vecors.npy and yolov4.h5 in the root dictionary (same path with Main.py)
