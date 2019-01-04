# Final Coursework

*A web tool to  enable  users to specify  and download  raster images of DEM, hillshade, slope and aspect*

## Usage

To deploy on your machine, ensure that you have `gdal`, `node`, `python` and `git` installed.

### Get the code

Clone the repository in Terminal:

```bash
git clone https://github.com/robisoniv/dem-web-app.git && cd dem-web-app
```

### Get the data

Execute the `dl-zips.sh`, `unzip.py`, `aggregate.py`, `merge.py` and `place-data.py` scripts.


### Prep the node app

Install the node modules with `npm install`.

Fire up the webserver with `nodemon start`.

Load `localhost:8000` in your browser - let's hope it works! 🤞🏼
