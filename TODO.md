TAR stvari za napravit

1. Izračunati Fleiss Kappu za svaku verziju ankete

   - računati kappu za svaki par anotatara koji su ispunjavali istu verziju ankete.

2. Evaluacija Humans Vs Models = Borna i Hana

   - usporedba s BERT-om, llama 3 i flan-t5-xxl (ovaj drugi je osposobljen na colabu) i eventualno još neki model
   - llamu treba osposobiti (ili preko ollama paketa ili huggingface-a: za huggingface poslo mi je neki lik svoju bilježnicu s kagglea ali je reko da mu nije jasno kako i zašto je proradilo tak da ću ja probat preko ollame osposobit llama 3)
   - napraviti modificiranu verziju Self-consistency samplinga iz https://arxiv.org/pdf/2403.00418 (page 4)

     - umjesto majority class votes koristiti postotke (problem je šta ne možemo ići na majority class jer nemamo konzistentan broj anotatora za svaku verziju ankete, tj. svaki tekst)
     - ili neka druga ideja za modifikaciju ovo gore nije provjereno s Anom jer mi je palo na pamet dok sam se tusirao, ali nekak mi to ima smisla

   - ako se stigne može se također iz gornjeg rada napraviti distirbution prompting
   - izračunati cjelokupni F1 score koji su anotatori postigli na skupu
   - izračunati cjelokupni F1 score koji se postiže na sa pojedinim modelom na cijelom skupu

3. Napisati rad
   - predložak za LateX je stavljen na Git
   - poglavlja:
     -Introduction
     - Related Work (konkretno opisati šta se radilo u dva rada ima neke koje je Ana linkala u thredu)
     - Methodology (objasniti anketiranje, objasniti Fleiss cappu i zašt se koristi, SCS, DP)
     - Results: prikazati F1 scores, rezultate SCS, DP-a
     - Conclusion
     - References
