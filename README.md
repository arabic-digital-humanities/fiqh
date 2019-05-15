# Fiqh Corpus

This corpus of texts is a selection of works of Islamic jurisprudence (furūʿ al-fiqh) written in Arabic, from ca. 800 to 1950. The corpus, which includes ca. 49,330,000 tokens, is subdivided into five subcorpora, each of them belonging to a legal school in Islamic law:

1. Ḥanafīs (modern-day Turkey, Central Asia, South East Asia): 13,006,501 tokens;
2. Shāfiʿīs (Egypt and the Levant, South East Asia): 10,495,516 tokens; 3. Mālikīs (North Africa and the Maghreb): 9,224,967 tokens;
4. Ḥanbalīs (modern-day Saudi-Arabia): 5,051,702 tokens; and
5. Jaʿfarīs (modern-day Iran and Iraq): 11,450,826 tokens.

The criteria for selection of the texts in the corpus were:

1. availability in digitized format;
2. comprehensiveness (i.e., texts have to cover the major three areas of Islamic jurisprudence, namely ritual law, private law, and public law);
3. length (i.e., the longer the better); and
4. popularity (measured by the relative fame of a work or author).

The `BookSource` field in the metadata specifies the source the book was taken from.
Most of the books were collected from [al-Maktaba al-Shamila website](http://shamela.ws). The books in the website are generated using the [al-Maktaba al-Shamila software program](http://www.arrawdah.com) developed by al-Makab al-Taʿāwnī lil-Daʿwā bil-Rawdā. In the program itself the developers state that the books are free and they encourage others to distribute them. They also stress that the books are not to be used to distribute what is deviant to the Sunni doctrine. The Jaʿfarī books were collected from [Maktabat Yuʿsūb](http://www.yasoob.com) and they say nothing regarding their license.

The corpus was created for the [Bridging the Gap project](https://www.esciencecenter.nl/project/bridging-the-gap).

The text files are in [OpenITI markup](https://alraqmiyyat.github.io/mARkdown/).

## Preprocessing

* We replaced all instances of `\u2028` with `\n` (using notebook [`split-on-headers.ipynb`](https://github.com/arabic-digital-humanities/adhtools/blob/master/notebooks/split-on-headers.ipynb))
