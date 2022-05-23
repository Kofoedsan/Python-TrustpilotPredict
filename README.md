# Python-TrustpilotPredict

#### Project name:
    Automatiseret vurderings og karaktergivning af Trustpilots anmeldelser  
    
#### Short description
    I dette projekt har vi gjort det muligt, at forudsige en karakter fra 1-5 ud fra tekstindholdet i en
    anmeldelse fra Trustpilot, og vise om sammenhængen passer mellem karakter og den givne anmeldelse.
    Ved hjælp af webscraping har vi indsamlet en masse andmeldelser fra forskellige virksomheder på Truspilot og
    baseret vores model på denne data.

    I vores projekt har vi:

		1. Webscrapet, renset & filtreret data.
		
		2. Trænet & sammenlignet fastText med Sklearn på samme dataset for at se hvilken model der er mest præcis.
	
		3. Evaluéret og fastslået hvor brugbar den valgte model er ved at sammenligne træningsdata- med valideringsdata.

		4. Forudset og sammenlignet Trustpilot's aktuelle ratings af reviews med vores trænede model.

		5. Visualiseret sammenhængen mellem karakter og review i et feature space.

		6. Anvendt WordCloud for at konkludere, hvilke ord der fremtræder oftes for hver rating.
    
#### List of used technologies

	Common
	 - Regular Expressions (RE)
	 - Tabulate
	 - ThreadPoolExecutor
	 - Time
	 - tqdm (ProgressBar)
	
	Data Analysis
	 - Pandas

	Files
	 - Glob
	 - Pickle
	
	Math
	 - Random
	 - Numpy

	Plot
	 - matplotlib
	
	Webscraping
	 - BeautifulSoup (BS4)
	 - Request
	
	Machine learning
	 - FastText
	 - Natural Language Toolkit (NLTK)
	 - Scikit-learn (Sklearn)
	 - WordCloud


#### Installation guide
    Projektet er sat op til at afvikles i Jypyter Notebook.
    Kør 00_install for at installere manglende packages.
    
#### User guide
    Projektet skal køres i kronologisk orden, dvs. oppe fra og ned:
    00_install
    01_webscraping_request
    01a_webscraping_clean
    02_models
    03_evaluate_fasttext
    04_predict_rating
    05_feature_space
    06_wordcloud
    
#### Status
    Alle opgaver er besvaret.
    
#### List of Challenges
    At gøre statiske funktion skalérbar.
    Model skal kunne predict korrekt med minimum 70%
    
    
