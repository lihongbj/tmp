## common
|ns|cpu usage(m)|rqst|limit|mem-usage(M)|rqst|limit|
|---|---|--|--| ---|---|--|
|nfs | 1| | |21 | | |
|ceph | | | | | | |
|openshift-gitops | 94|1875 |7500 | 963|2432 | 5376|


## sno 
note:
- fresh sno: some limit of cpu and mem are 0, so limit < request


|ns|cpu usage(m)|rqst|limit|mem-usage(M)|rqst|limit|
|---|---|--|--| ---|---|--|
|new sno | 1016|7200 |4800 | 12305| 15925|6080 |
|eventmanager | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|--remove cs locker -- |-- | | | | | |
|aimanager| 1439|14735 |95925 | 19086|39181 | 114520|
|ics | 245| 4510|22435 | 3452|8511 |17655 |
|all | | | | | | |



## QB
|ns|cpu usage(m)|rqst|limit|mem-usage(M)|rqst|limit|
|---|---|--|--| ---|---|--|
|new  | | | | | | |
|eventmanager | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- |-- | | | | | |
|aimanager| | | | | | |
|ics | | | | | | |
|-- -- |-- | | | | | |
|aimanager|   | | | | | |
|ics |   | | | | | |
|all | | | | | | |
