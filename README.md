# Repository structure
```bash
.
├── nbr // NBR library
│   ├── common // subpackage with recommendation metrics definition and common constants
│   ├── dataset // subpackage with NBR dataset definition
│   ├── model // subpackage with NBR models definition
│   ├── preparation // subpackage with dataset preprocessing classes
│   ├── trainer // subpackage with NBR trainer definition
│   └── __init__.py
└── notebooks // folder with tests of different NBR models on provided datasets
    ├── data // folder with unprocessed datasets
    │   ├── dunnhumby.txt // Dunnhumby dataset
    │   ├── ta_feng.txt // Ta Feng dataset
    │   └── taobao.txt // TaoBao dataset (purchase interactions only)
    ├── testing_dnntsp // folder with testing DNNTSP model
    │   ├── DNNTSP // DNNTSP library (author's version with minor modifications)
    │   └── testing_dnntsp.ipynb // notebook with testing DNNTSP model
    ├── testing_baselines.ipynb // notebook with testing TopPopular and TopPersonal models
    ├── testing_slrc.ipynb // notebook with testing SLRC model
    ├── testing_slrcknn.ipynb // notebook with testing SLRCKNN model
    ├── testing_tifuknn.ipynb // notebook with testing TIFUKNN model
    └── testing_tifuknntd.ipynb // notebook with testing TIFUKNN-TimeDays model
```
