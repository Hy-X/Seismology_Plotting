# Seismology_Plotting

Author: Hongyu Xiao

Repository of small examples and notebooks used to produce seismology plots
and short tutorials. The materials are primarily Jupyter notebooks and a
single example script demonstrating station plotting (PyGMT) and simple
catalog annotation tasks.

Repository contents
- CSV station lists:
	- `appalachian_BH_HH_stations_2yr_plus.csv`
	- `appalachian_BH_stations_1.5yr_plus.csv`
	- `appalachian_BH_stations_2yr_plus.csv`
- Notebooks and examples:
	- `eqt-annotate-example.ipynb` — earthquake catalog annotation workflow
	- `find_appalachian_longterm_BH_stations.ipynb` — find long-term BH stations
	- `find_appalachian_longterm_HH&BH_stations.ipynb` — HH & BH station search
	- `station-example-pygmt.ipynb` — station plotting example using PyGMT
	- `station-example-oklahoma-pygmt.ipynb` — Oklahoma station plotting example
- Scripts:
	- `station-example-pygmt.py` — Python script version of the PyGMT example
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
