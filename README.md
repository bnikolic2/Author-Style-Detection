# Author-Style-Detection

IDEJA:

1. Usporediti problem za ljude VS model
2. Provesti anotaciju tekstova izračunati IAA te evaluirati
3. Na trenirati model
   - najveći problem kako
   - PIPELINE: dovoditi dva po dva paragrafa na ulaz BERT-a, generirati embeddinge
   - dva po dva embeddinga klasificirati klasifikatorom
4. Evauluirati model (F1 score)
5. Usporediti rezultate i napisati izvještaj

**PAN dataset** is available at:
https://pan.webis.de/clef21/pan21-web/style-change-detection.html#data

Dataset change because of topics: https://zenodo.org/records/7729178
Dataset taken from **PAN2023**
Three levels: **easy** - paragraphs from different topics, **medium** - paragraphs from similar topics, **hard** - paragraphs from same topic

8 versions of form each consisting of 5 texts: 1 for example and 4 for annotating
The random sampling is done in form.ipynb notebook

Postotci zastupljenosti levela u anketama:

- easy +++++++++++++ = 13 (41%)
- medium ++++++++++ = 10 (31%)
- hard +++++++++ = 9 (28%)

Napomene za ankete:

- verzija 4
  - tekst 5: paragraf sa primanjem moderator prijava
