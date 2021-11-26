# Football transfers dataset

This dataset includes transfers of the major European football leagues from 2009 to 2021:

- ENGLISH PREMIER LEAGUE
- LA LIGA
- SERIE A
- BUNDESLIGA
- FRENCH LIGUE 1
- LIGA PORTUGAL BWIN
- DUTCH EREDIVISIE

Dataset can be found in `dataset\transfers.csv` file.

## Variables

`league` - codename of the football league. Takes the following values:
- `GB1` ENGLISH PREMIER LEAGUE
- `ES1` LA LIGA
- `IT1` SERIE A
- `L1` BUNDESLIGA
- `FR1` FRENCH LIGUE 1
- `PO1` LIGA PORTUGAL BWIN
- `NL1` DUTCH EREDIVISIE
 
`season` - season  
`window` - transfer window (`s` summer or `w` winter)  
`team_id` - team's ID as used by Transfermarkt  
`team_name` - team's name  
`team_country` - team's country  
`dir` - transfer direction (`in` or `left`)  
`player_id` - player's ID as used by Transfermarkt  
`player_name` - player's name  
`player_age` - player's age when transfer occurred  
`player_nation` - player's nationality  
`player_nation2` - player's 2nd nationality  
`player_pos` - player's field position  
`counter_team_id` - counter team's ID as used by Transfermarkt  
`counter_team_name` - counter team's name  
`counter_team_country` - counter team's country  
`transfer_fee_amnt` - transfer fee amount (EUR)  
`market_val_amnt` - player's market value (EUR) when transfer occurred estimated by Transfermarkt  
`is_free` - free transfer (`True` or `False`)  
`is_loan` - loan transfer (`True` or `False`)  
`is_loan_end` - end of loan transfer (`True` or `False`)  
`is_retired` - player retired (`True` or `False`)  
`transfer_id` - transfer's ID as used by Transfermarkt  

## Data source and code
- Data was scraped from [Transfermarkt.com](https://www.transfermarkt.com). Raw data files can be found in `data` folder.
- Scraper and preprocessing Jupyther notebooks with code can be found in `src` folder.