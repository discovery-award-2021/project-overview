# Characterizing documents differentially and psychometrically

The fundamental goal of this 1-year research project is to develop a simple recipe for the situation where a scholar has a collection of documents grouped according to a dimension like time, geography, or theme (the "differential" part) and would like to explore what they reveal about those who produced them (the "psychometric" part).  Often there is already some expectation or focus on what will be revealed: for example, the scholars may suspect that documents from sunny climates will reflect a happier population.

# Data summaries

The notion of a "document" varies greatly between studies: some focus on social media, where a document may be a tweet, while others consider novels or volumes of historical records.  The larger documents will be split into shorter elements, ideally paragraphs, or just evenly-spaced intervals, for the purposes of topic modeling.

## Early Colonial American Publications (56k documents, 1.4b words)
**Sharon Achinstein, Daniel McClurkin (English)**

Combination of Early English Books Online and Eighteenth Century Collection Online.  Includes authorship and publication date, hopefully we can also infer sufficient geographic information to consider that axis as well.

## Cuneiform Correspondence from El Amarna (330k documents, 6.4m words)
**Jacob Lauinger, Michael Chapin (Near East Studies)**

Entire CDLI catalog including available English translations.  Sam has also pulled about 7000 images, evenly split between photos and line diagrams.  Lots of metadata.

## Smoking and Vaping (109k documents, 4.3m words)
**Johannes Thrul (BSPH)**

Reddit posts and comments from forums devoted to quitting various nicotine products.  Include creation timestamps.

## Med Student Professional Awareness (715k documents, 25m words)
**Meg Chisolm, Kaitlin Stouffer (JHMI)**

Reddit posts and comments from forums devoted to users enrolled in premed, med school, and residency programs.  Will need to consider how to reflect this data onto the course surveys/essays/annotations provided by JHMI.

## COVID Misinformation on Social Media (319k documents, 8.3m words)
**Tara Sell (BSPH)**

Twitter data matching COVID-related keywords and (partially) annotated by BSPH researchers, plus Reddit comments/posts from forums devoted to the pandemic.  I;; include creation timestamps.

## Mental Health in Hispanic Populations (7.9m documents, 125m words)
**Michelle Kaufman, Maithily Diaz (BSPH)**

Twitter data matching mental health keywords in English and Spanish *and* including the word "california" (directly or in the user profile, excluding "baja california").  Reddit posts and comments from the "California" and "hispanic" forums.

## Narratives from Medical Professionals (13 documents, 977k words)
**Jacek Mostwin (JHMI)**

OCR output from scanned 13 monographs (roughly, "medical memoirs").  OCR is particularly noisy, may require some additional effort to post-process.

## Early Methodist Minutes (32 documents, 8.3m words)
**Francois Furstenberg, Michael Johnson (History)**

OCR output from 32 volumes of minutes from mid-19th-century Methodist national meetings.  Includes dates of each document, and perhaps worth trying to auto-extract geographic information, though it wouldn't serve the same purpose as in other studies (doesn't indicate the location of composition).
