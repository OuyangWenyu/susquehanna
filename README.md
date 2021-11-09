# susquehanna

LSTM and SAC-SMA+Snow17 results for basins in Susquehanna region

To run scripts here, please install and use conda env:

```Shell
conda env create -f environment.yml
# activate the conda env
conda activate susquehanna
# open jupyter
jupyter lab
```

The data used here can be downloaded from: https://www.kaggle.com/hydroowen/susquehanna-data

After downloading, please unzip the files, and put them in the "data" directory:

```File system
data/
└── basin_timeseries_v1p2_modelOutput_daymet
└── boundaries-shapefiles-by-aggeco
└── camels_attributes_v2.0
└── lstm_output
└── usgs_streamflow
└── HCDN_nhru_final_671.dbf
└── HCDN_nhru_final_671.prj
└── HCDN_nhru_final_671.qpj
└── HCDN_nhru_final_671.shp
└── HCDN_nhru_final_671.shx
└── ....... (other files)
```