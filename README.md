# OData spike

A very quick attempt at implementing an OData endpoint for ScraperWiki datasets, using the cgi endpoint and a flask app.

## How to install:

1. SSH into a ScraperWiki box containing a scraperwiki.sqlite database file.

2. `mkdir -p ~/cgi-bin`

3. `cd ~/cgi-bin`

4. `git clone https://github.com/scraperwiki/odata-spike.git odata`

5. `pip install --user flask`

6. Your OData endpoint will be accessible at `https://<server>.scraperwiki.com/<box>/<token>/cgi-bin/odata`
