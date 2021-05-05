# Using Folium

## Preparing the environment

For this project I'm using Python version `3.8.2`, and the module `venv` to create the environment:

```console
$ python3 -m venv .env
$ source .env/bin/activate
```

## Installing required packages

```console
(.env) $ cd folium-101/
(.env) $ pip install -r requirements.txt
```

## Files

- `folium-101.ipynb`: A notebook containing all the code for reproducibility and study;
- `maps_htmls/`: Directory of saved maps in the HTML format;
- `cities.csv`: Data file in the CSV format containing cities data.

### Data

The data here presented was created using a spreadsheets software and exported to CSV format.

|   Column  | Descriptions |
|:---------:|:------------:|
|    city   | City name |
|  latitude | City coordinate: Latitude |
| longitude | City coordinate: Longitude |
|   lived   | Whether or not I lived in that city |
|  visited  | Whether or not I visited in that city |
