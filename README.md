# TIES4450 Project

Dataset: https://www.kaggle.com/datasets/gpreda/russian-invasion-of-ukraine

Presis: https://jyu-my.sharepoint.com/:p:/g/personal/saniosru_jyu_fi/EUZhxjzAeJ9PlW7OQ3Qyoa8BtX2Q20jKeEbMyi7zQmIuUA?e=2jtbQC

**Jotta voi ajaa projektia**

- pip install -r requirements.txt
- ipython
- run notebook.ipynb

**TODO:**

- Datan klusterointia
- Keskustelun muuttuminen viikoittain / päivittäin
- Viestin määrä per / päivä
- Vertailua päivittäiseen uutisointiin - https://newsapi.org/ 
    - Esim. timeline
- Miten ja mitä emojeita datassa esiintyy
    - Wordcloud - emojeille
- Heat map - maiden nimien esiintymisestä datassa

**Preprocessing**

- Stemming --> sanat perusmuotoon

**Mietintää:**

- Liittyen TF-IDF
    - Onko yksi kommentti yksi "dokumentti"? Vaiko yhdistetäänkö esim. yhteen postaukseen
    liittyvät kommentit yhdeksi dokumentiksi
    - Luetaanko myös uutislinkkien sisältö dokumentiksi?
        - Miten saataisiin vaan uutisen sisältö eikä kaikkea sivulla olevaa tauhkaa
- Latent semantic analysis