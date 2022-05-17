# Python-TrustpilotPredict

#### Project name:
    Automatiseret vurderings og karaktergivning af Trustpilots anmeldelser  
    
#### Short description
    I dette projekt har vi gjort det muligt, at forudsige en karakter fra 1-5 ud fra tekstindholdet i en
    anmeldelse på Trustpilot, og vise om sammenhængen af ((((én virksomheds samlede vurdering))) passer mellem
    karakter og anmeldelser. Vi har gjort dette ved at scrape en masse andmeldelser fra
    forskellige virksomheder på Truspilot og baseret vores model ud fra de
    indsamlede data.


    I vores projekt har vi:


	1. 	Webscrape data
		1a Rens & filtrer data med beautifulsoup.
		1b Træn sklearn & fasttext på samme dataset.

	2. 	Sammenlign fasttext med sklearn og se hvilken model der er mest præcis.
	
    3.  Evaluére og fastslå hvor brugbar modellen er ved at sammenligne træningsdata- og valideringsdata.
		3a. Efterjustér modellens definition efter behov.

    4.  Forudsige hvilken karakter en anmelder vil give ud fra den anmeldselse de har skrevet. (Regression)
		4a. Sammenlign med den aktuelle anmelder karakter.

    5.  Vis sansynligheden for predictions indenfor Trustpilots fem katagorier: Fremragende, God, Middel,
        Uder middel, Dårlig, for en specifik anmeldelse. (Classification)

    6.  Gruppere og plot ratings for én specifik virksomhed i et 3D feature space. (Clustering)

    7.  Brug WordCloud til og plotte de mest anvendte Negative og Positive ord.
        7.a Brug WordCloud til at plotte de mest anvendte ord for hver af rating.
    
#### List of used technologies
      Webscraping
      Request
      Pandas
      Numpy
      Neural network(NLTK)                                     
      BS4
      WordCloud
      Files
      Machine learning
      Fasttext
      Sklearn

#### Installation guide (if any libraries need to be installed)
    TBD
    
#### User guide (how to run the program)
    TBD
    
#### Status (What has been done (and if anything: what was not done))
    TBD
    
#### List of Challenges you have set up for your self (The things in your project you want to highlight)
    TBD
