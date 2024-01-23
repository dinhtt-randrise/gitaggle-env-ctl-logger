```
          _ _                    _      
         (_) |                  | |     
     __ _ _| |_ __ _  __ _  __ _| | ___ 
    / _` | | __/ _` |/ _` |/ _` | |/ _ \
   | (_| | | || (_| | (_| | (_| | |  __/
    \__, |_|\__\__,_|\__, |\__, |_|\___|
     __/ |            __/ | __/ |       
    |___/            |___/ |___/        
--------------------------------------------
        Environment Control Logger
--------------------------------------------


============================================
           1. /crontab.json
  ---------------------------------------

This file contains scheduler for running notebooks.

Following is example of crontab.json:

----------
[
  {
    "pseudo": "no",
    "h": "*",
    "m": 0,
    "nb_user": "dinhttrandrise",
    "nb_code": "gg-environment-controller-c"
  },
  {
    "pseudo": "no",
    "h": 8,
    "m": "*",
    "nb_user": "dinhttrandrise",
    "nb_code": "gg-environment-controller-c"
  }
]
----------

```
