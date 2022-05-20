# Python-TrustpilotPredict

#### Project name:
    Automatiseret vurderings og karaktergivning af Trustpilots anmeldelser  
    
#### Short description
    I dette projekt har vi gjort det muligt, at forudsige en karakter fra 1-5 ud fra tekstindholdet i en
    anmeldelse fra Trustpilot, og vise om sammenhængen passer mellem karakter og den givne anmeldelse.
    Ved hjælp af webscraping har vi indsamlet en masse andmeldelser fra forskellige virksomheder på Truspilot og
    baseret vores model på denne data.

    I vores projekt har vi:

		1. Webscrapeet, renset & filtreret data.
		
		2. Trænet & sammenlignet fastText med Sklearn på samme dataset for at se hvilken model der er mest præcis.
	
		3. Evaluéret og fastslået hvor brugbar den valgte model er ved at sammenligne træningsdata- med valideringsdata.

		4. Forudset og sammenlignet Trustpilot's aktuelle ratings af reviews med vores trænede model.

		5. Visualiseret sammenhængen mellem karakter og review i et 3D feature space.

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


#### Installation guide (if any libraries need to be installed)
    TBD
    
#### User guide (how to run the program)
    TBD
    
#### Status (What has been done (and if anything: what was not done))
    TBD
    
#### List of Challenges you have set up for your self (The things in your project you want to highlight)
    TBD
