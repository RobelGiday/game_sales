# Video Game Sales

## Objective
This project analyse global video game sales datas for 64,016 titles released between 1971 and 2024 across North America, Japan, the EU, Africa, and the rest of the world. The analysis aims is to uncover trends in worldwide and regional sales, identify top-selling titles and peak sales years to evaluate industry groweth,and explore dominant genre across gaming consoles. 

### Project Scope
This project aims to answer these questions.
- Which titles achieved the highest worldwide sales?
- Which years recorded peak sales, and how has the industry grown or fluctuated over time?
- Do certain consoles specialised in specific genres?
- which titles succeed in one region but underperform in others?

### Dataset overview 
The raw dataset used in this analysis is available from [Maven Analytics](https://mavenanalytics.io/data-playground/video-game-sales). It contains 64,016 records and fields consisting of:
|Column Name | Description              |
|------------|--------------------------|
| img | URL to link the image
| title | Game title |
| console | Console the game was released for |
| genre | Genre of the game|
| developer | Developer of the game | 
| critic score | MetaCritic score (out of 10) |
| total_sales | Global sales of copies in millions |
| na_sales | North American sales of copies in millions |
| jp_sales | Japanese sales of copies in millions |
| pal_sales | European & African sales of copies in millions |
| other_sales | Rest of world sales of copies in millions |
| release_date | Date the game was released on |
| last_update | Date the data was last update |

 After cleaning dataset to filtered the unneccessary data there was only 17,505 records that were deemed useable for the analyses. Additional to optimised the dataset for analytical purposes I have applied Kimball Star Schema referred to Figure 1 to see the database structure. 

