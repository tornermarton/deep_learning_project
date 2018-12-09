# Authorship identification using deep learning
**Füleki Fábián,	Jani Balázs Gábor,	Torner Márton**  
*Project work for BME Deep Learning course (VITMAV45),  
Team: LoremIpsum*

**Goal:**  
We are aiming to indentify the most likely author of an article, from group of authors, whose previous works are known and processed.

**Dataset:**  
Our primary dataset is the Reuters_50_50 (C50), which is a subset of Reuters Corpus Volume I(RCVI). The RCV1 is archive of categorized newswire stories, made public for research purposes by Reuters, Ltd. The C50 collection consist of 50 texts for each of the 50 top author, for training and separately the same amount for testing purpose (5000 texts in total).  This dataset has been previous used by previous studies of authorship recognition and can be found here: *https://archive.ics.uci.edu/ml/machine-learning-databases/00217/C50.zip*   
The dataset preparation script used for testing can be found in dl_project_dataprep.ipynb.

**Test environment:**  
We used a Google Cloud Compute Engine with the following specifications:  
- Intel(R) Xeon(R) core 8 CPU @ 2.30 GHz  
- Tesla P100 GPU (GPU Driver Version: 410.72; CUDA Version: 10.0)
- Debian 4.9.110
- Python 3.5.5
- Keras 2.2.4 with tensorflow backend.

**Tests:**  
The tests shown in the documentation can be reproduced with the scripts in dl_project_nn_tests.ipynb.
<HR>
  
# Deep Learning alapú szerzőazonosítás
**Füleki Fábián,	Jani Balázs Gábor,	Torner Márton**  
*Projekt munka a BME Deep Learning kurzusára (VITMAV45),  
Csapat: LoremIpsum*

**Cél:**  
A célunk azonosítani a legvalószínűbb szerzőt, lehetséges szerzők egy olyan csoportjából, kiknek a korábbi munkája ismert és általunk feldolgozott.

**Dataset:**  
Az általunk használt adatbázis az alábbi linken érhető el: *https://archive.ics.uci.edu/ml/machine-learning-databases/00217/C50.zip*. Ez a Reuters Corpus Volume I(RCVI) egy része, amely 5000 cikket tartalmaz, 100-100 cikket írónként, összesen 50 kiválasztott írótól.  
Az adatbázist feldolgozó/előkészítő script megtalálható a dl_project_dataprep.ipynb nevű jupyter notebookban.

**Teszt környezet:**  
A teszteléshez egy Google Cloud Compute Engine-t használtunk a következő specifikációkkal:  
- Intel(R) Xeon(R) core 8 CPU @ 2.30 GHz  
- Tesla P100 GPU (GPU Driver Version: 410.72; CUDA Version: 10.0)
- Debian 4.9.110
- Python 3.5.5
- Keras 2.2.4 with tensorflow backend.

**Tests:**  
A tesztek reprodukálhatóak a dl_project_nn_tests.ipynb nevű jupyter notebookban található scriptekkel.
