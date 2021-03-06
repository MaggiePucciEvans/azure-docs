
### Basic elastic pool limits

| Pool size (eDTUs)  | **50** | **100** | **200** | **300** | **400** | **800** | **1200** | **1600** |
|:---|---:|---:|---:| ---: | ---: | ---: | ---: | ---: |
| Max storage per pool* | 5 GB| 10 GB| 20 GB| 29 GB| 39 GB| 78 GB| 117 GB| 156 GB|
| Max number DBs per pool | 100 | 200 | 500 | 500 | 500 | 500 | 500 | 500 |
| Max concurrent workers per pool | 100 | 200 | 400 | 600 | 800 | 1600 | 2400 | 3200 |
| Max concurrent logins per pool | 100 | 200 | 400 | 600 | 800 | 1600 | 2400 | 3200 |
| Max concurrent sessions per pool | 30000 | 30000 | 30000 | 30000 |30000 | 30000 | 30000 | 30000 |
| Min eDTUs per database | {0, 5} | {0, 5} | {0, 5} | {0, 5} | {0, 5} | {0, 5} | {0, 5} | {0, 5} | {0, 5} |
| Max eDTUs per database | {5} | {5} | {5} | {5} | {5} | {5} | {5} | {5} | {5} |
||||||||

### Standard elastic pool limits

| Pool size (eDTUs)  | **50** | **100** | **200** | **300** | **400** | **800** | 
|:---|---:|---:|---:| ---: | ---: | ---: | ---: |---: |---: |---: |---: |
| Max storage per pool* | 50 GB| 100 GB| 200 GB | 300 GB| 400 GB | 800 GB | 
| Max number DBs per pool | 100 | 200 | 500 | 500 | 500 | 500 | 
| Max concurrent workers per pool | 100 | 200 | 400 | 600 |  800 | 1600 |
| Max concurrent logins per pool | 100 | 200 | 400 | 600 |  800 | 1600 |
| Max concurrent sessions per pool | 30000 | 30000 | 30000 | 30000 | 30000 | 30000 |
| Min eDTUs per database | {0,10} | {0,10,20} | {0,10,20,<br>50} | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} |
| Max eDTUs per database | {10} | {10,20} | {10,20,<br>50,100} | {10,20,<br>50,100} | {10,20,<br>50,100} | {10,20,<br>50,100} | 
||||||||

### Standard elastic pool limits (continued)

| Pool size (eDTUs)  |  **1200** | **1600** | **2000** | **2500** | 
|:---|---:|---:|---:| ---: | ---: | ---: | ---: |---: |---: |---: |
| Max storage per pool* | 1.2 TB | 1.6 TB | 2 TB | 2.4 TB | 
| Max number DBs per pool | 500 | 500 | 500 | 500 | 500 | 
| Max concurrent workers per pool |  2400 | 3200 | 4000 | 5000 |
| Max concurrent logins per pool |  2400 | 3200 | 4000 | 5000 | 
| Max concurrent sessions per pool | 30000 | 30000 | 30000 | 30000 |30000 | 
| Min eDTUs per database | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} | {0,10,20,<br>50,100} |
| Max eDTUs per database | {10,20,<br>50,100} | {10,20,<br>50,100} | {10,20,<br>50,100} | {10,20,<br>50,100} | {10,20,<br>50,100} | 
||||||||

### Premium elastic pool limits

| Pool size (eDTUs)  | **125** | **250** | **500** | **1000** | **1500** | 
|:---|---:|---:|---:| ---: | ---: | ---: | ---: |---: |---: |---: |
| Max storage per pool* | 250 GB| 500 GB| 750 GB| 750 GB| 750 GB| 
| Max number DBs per pool | 50 | 100 | 100 | 100 | 100 |  
| Max concurrent workers per pool | 200 | 400 | 800 | 1600 |  2400 | 
| Max concurrent logins per pool | 200 | 400 | 800 | 1600 |  2400 |
| Max concurrent sessions per pool | 30000 | 30000 | 30000 | 30000 | 30000 | 
| Min eDTUs per database | {0,25,50,<br>75,125} | {0,25,50,<br>75,125,<br>250} | {0,25,50,<br>75,125,<br>250,500} | {0,25,50,<br>75,125,<br>250,500,1000} | {0,25,50,<br>75,125,<br>250,500,1000} | 
| Max eDTUs per database | {125} | {125,250} | {125,250,<br>500} | {125,250,<br>500,1000} | {125,250,<br>500,1000} |  
||||||||

### Premium elastic pool limits (continued)

| Pool size (eDTUs)  |  **2000** | **2500** | **3000** | **3500** | 
|:---|---:|---:|---:| ---: | ---: | ---: | ---: |---: |---: |---: |
| Max storage per pool* | 750 GB| 750 GB| 750 GB| 750 GB| 
| Max number DBs per pool | 100 | 100 | 100 | 100 | 100 | 
| Max concurrent workers per pool |  3200 | 4000 | 4800 | 5600 | 
| Max concurrent logins per pool |  3200 | 4000 | 4800 | 5600 | 
| Max concurrent sessions per pool | 30000 | 30000 | 30000 | 30000 | 30000 | 
| Min eDTUs per database | {0,25,50,75,<br>125,250,500,<br>1000,1750} | {0,25,50,75,<br>125,250,500,<br>1000,1750} | {0,25,50,75,<br>125,250,500,<br>1000,1750} | {0,25,50,75,<br>125,250,500,<br>1000,1750} | 
| Max eDTUs per database | {125,250,500,<br>1000,1750} | {125,250,500,<br>1000,1750} | {125,250,500,<br>1000,1750} | {125,250,500,<br>1000,1750} | 
||||||||

\* Elastic database share pool storage, so database storage is limited to the smaller of the remaining pool storage or max storage per database
