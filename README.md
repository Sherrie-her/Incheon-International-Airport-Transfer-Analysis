<img width="811" alt="Screenshot 2024-12-25 at 8 14 25 PM" src="https://github.com/user-attachments/assets/05526de2-cb4d-49a5-9de4-6ce0083a83da" /># Incheon-International-Airport-Transfer-Analysis

# Analysis of Incheon International Airport Transfers

Analysis of transfer passenger patterns at Incheon International Airport using R, focusing on route optimization and seasonal trends.

## Team Members (Group 1)
- Nam Hee Yeon
- Son Chae Ri
- Kyung Dong Heon

## Project Overview
Analyzed Incheon International Airport transfer passenger data from January to June 2023 to:
- Understand seasonal transfer patterns
- Identify key routes and regional trends
- Propose new potential flight paths

## Data
- Source: Incheon International Airport Corporation's Open Data Platform
- Period: January 2023 - June 2023
- Content: Arrival and departure transfer passenger information
- Size: ~61,000 rows per dataset

## Hypothesis
<img width="796" alt="Screenshot 2024-12-25 at 8 12 33 PM" src="https://github.com/user-attachments/assets/e3b44092-9ae5-4540-b806-2ce3f1fc5e70" />

## Key Findings
1. Seasonal Patterns:
   - Contrary to expectations, Southeast Asian transfers decreased in summer (monsoon impact)
   - Overall passenger numbers showed increasing trend towards summer
   - South Asia contributed significantly to January peaks
<img width="808" alt="Screenshot 2024-12-25 at 8 13 51 PM" src="https://github.com/user-attachments/assets/b334752c-b035-4ab0-908d-a90305cf20e8" />
<img width="798" alt="Screenshot 2024-12-25 at 8 14 00 PM" src="https://github.com/user-attachments/assets/0740987b-73e6-418f-bf10-91aa104ddf0d" />
<img width="796" alt="Screenshot 2024-12-25 at 8 14 08 PM" src="https://github.com/user-attachments/assets/cc7438e1-ac1e-48d0-9eb6-c60cb4f718f0" />
<img width="797" alt="Screenshot 2024-12-25 at 8 14 15 PM" src="https://github.com/user-attachments/assets/d8b5d1cc-8506-4181-942d-47cf9afcf089" />

2. Regional Analysis:
   - Top 3 regions account for ~90% of transfers:
     - Southeast Asia
     - North America
     - East Asia
   - Busan emerged as significant transit point

3. Route Analysis:
   - Distance not a primary factor in transfer numbers
   - Regional factors more influential than distance
   - Strong connections between Western and Southeast Asian routes
   
<img width="801" alt="Screenshot 2024-12-25 at 8 14 39 PM" src="https://github.com/user-attachments/assets/8a5c3f55-7081-4bf9-be1f-d7be23fd8a1f" />
<img width="792" alt="Screenshot 2024-12-25 at 8 14 49 PM" src="https://github.com/user-attachments/assets/b36f0c2e-9902-437a-ad2e-857f1dc6ea7e" />

## Route Recommendations
<img width="798" alt="Screenshot 2024-12-25 at 8 15 05 PM" src="https://github.com/user-attachments/assets/4477cd3b-f11d-4767-950e-5b0c090224f8" />
<img width="801" alt="Screenshot 2024-12-25 at 8 15 14 PM" src="https://github.com/user-attachments/assets/aeecdc10-62f6-48b4-9287-10aa08649832" />
<img width="797" alt="Screenshot 2024-12-25 at 8 15 45 PM" src="https://github.com/user-attachments/assets/4fbc3e22-5b49-499b-ba13-af5a163dfbf4" />
<img width="813" alt="Screenshot 2024-12-25 at 8 15 35 PM" src="https://github.com/user-attachments/assets/f5833d1b-ca56-4740-a704-d640e5c8645b" />

1. Direct Routes to/from Busan:
   - Tokyo
   - Osaka
   - Shanghai
   - Taipei
   - Hong Kong

2. New Transfer Routes:
   - Bangkok - Amsterdam
   - Vancouver - New Ulaanbaatar
   - Western-Southeast Asian connections

## Project Structure
```
.
├── DSR-Group1-PPT.pdf          # Presentation slides
├── DSR-Group1-Report.pdf       # Project report
├── DSR-Group1-Rmd.Rmd         # R analysis code
└── data/
    ├── 환승승객현황_정보_2023년_도착.csv    # Arrival dataset
    └── 환승승객현황_정보_2023년_출발.csv    # Departure dataset
```

## Tools Used
- R Programming
- Libraries:
  - tidyverse
  - dplyr
  - ggplot2
  - airportr
  - geosphere
  - maps/ggmap

## Setup
1. Clone repository
2. Install R and required packages:
```R
install.packages(c("tidyverse", "dplyr", "ggplot2", "airportr", 
                  "geosphere", "maps", "ggmap"))
```
3. Open DSR-Group1-Rmd.Rmd in RStudio
4. Run analysis
