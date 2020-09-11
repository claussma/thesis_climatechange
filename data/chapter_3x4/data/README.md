# Chapter 3.4: Principal Strains

## meta.csv

Contains the input data for the Finite-Element Analysis.

| Column Name | Description                                   | Unit |
| ----------- | --------------------------------------------- | ---- |
| varid       | ID of the variants                            |      |
| d_ads       | thickness of the asphalt surface course       | m    |
| d_abs       | thickness of the asphalt binder course        | m    |
| d_ats       | thickness of the asphalt base course          | m    |
| d_fss       | thickness of the granular base course         | m    |
| E_ads       | Young's modulus of the asphalt surface course | MPa  |
| E_abs       | Young's modulus of the asphalt binder course  | MPa  |
| E_ats       | Young's modulus of the asphalt base course    | MPa  |

## results_fem_100.csv

Data from Abaqus

| Column Name | Description                             | Unit |
| ----------- | --------------------------------------- | ---- |
| x,yz        | Coordinates of the elements             | m    |
| E           | strains                                 |      |
| S           | stresses                                |      |
| U           | displacements                           |      |
| instance    | Name of the asphalt layer               |      |
| d_ads       | thickness of the asphalt surface course       | m    |
| d_abs       | thickness of the asphalt binder course        | m    |
| d_ats       | thickness of the asphalt base course          | m    |
| d_fss       | thickness of the granular base course         | m    |
| E_ads       | Young's modulus of the asphalt surface course | MPa  |
| E_abs       | Young's modulus of the asphalt binder course  | MPa  |
| E_ats       | Young's modulus of the asphalt base course    | MPa  |


## miner.csv

Results of the analysis of the FE-calculations of **variant 100**. Only mesh points with strains were evaluated.



| Column Name    | Description                             | Unit |
| -------------- | --------------------------------------- | ---- |
| x              | Coordinate X                            | m    |
| y              | Coordinate Y                            | M    |
| instance       | Name of the asphalt layer               |      |
| maxP           | principal stains                        | MPa  |
| winkel_{x,y,z} | angle between the coordinates x,y and z | °    |
| zulN           | Permissible number of load changes      |      |

