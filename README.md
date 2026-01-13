# Seismology_Plotting

Author: Hongyu Xiao

Repository of small examples and notebooks used to produce seismology plots
and short tutorials. The materials are primarily Jupyter notebooks and a
single example script demonstrating station plotting (PyGMT) and simple
catalog annotation tasks.

Repository contents
- CSV station lists:
	- `appalachian_bh_hh_stations_2yr_plus.csv`
	- `appalachian_bh_stations_1_5yr_plus.csv`
	- `appalachian_bh_stations_2yr_plus.csv`
- Notebooks and examples:
	- `eqt_annotate_example.ipynb` — earthquake catalog annotation workflow
	- `find_appalachian_longterm_bh_stations.ipynb` — find long-term BH stations
	- `find_appalachian_longterm_hh_and_bh_stations.ipynb` — HH and BH station search
	- `station_example_pygmt.ipynb` — station plotting example using PyGMT
	- `station_example_oklahoma_pygmt.ipynb` — Oklahoma station plotting example
- Scripts:
	- `station_example_pygmt.py` — Python script version of the PyGMT example
- Other:
	- `LICENSE` — project license

Quick usage
- Open the notebooks with Jupyter Lab or Jupyter Notebook and run cells in order.
- The CSV files are station lists used by the notebooks/scripts for plotting
	and analysis.
- To run the script example:

```bash
python station-example-pygmt.py
```

Notes
- Notebooks may require scientific Python packages (e.g., PyGMT, pandas,
	numpy, matplotlib). Install packages used in the notebooks as needed.
- The notebooks are intended as examples and teaching material — modify
	them for your datasets and plotting preferences.

Contact
- Open an issue in this repository or contact the author for questions.
