# Museum-GitHub API Scraper

To set up and run:

	virtual env
	. env/bin/activate
	pip install -r requirements.txt
	python create_db.py  # initialize database
	python muse/scraper.py  # scrape github api to populate database
	datafreeze freezefile.yaml  # query database to generate org level connections
	python muse/networks.py  # generate gephi network files of org connections

