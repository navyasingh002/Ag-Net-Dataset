
# Ag-Net-Dataset

Example datasets for training and testing ag-net for crop recognition

This is related to ESIP Google Summer of Code project idea - [AgNet](https://github.com/ESIPFed/gsoc/issues/13)

The input folder contains the seven bands of Landsat 8. Each file name is constructed in this pattern: 

` lc8_{observation_date}_{row number}_{column number}_{band number}.tif `

The target folder contains the corresponding tiles. The file name is composed of:

` cdl_{landsat observation date}_{row number}_{column number}.tif `

The value of CDL ranges from 0 to 255. Each value represents a crop type or non-crop land cover. The CDL value explanation table is [here](cdlvalue.csv).

Please cite this dataset by: 

Ziheng Sun. (2019). Ag-Net Sample Training Dataset [data files and tutorial notebook]. https://github.com/ZihengSun/Ag-Net-Dataset.
