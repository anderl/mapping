# mapping
Files for the DataJournalism.com MOOC 'Mapping for Journalists' 

Bombings.csv
Since the files from data.mil are no longer available, I have recreated them. This is based on the file https://data.world/datamil/world-war-ii-thor-data, which contains global WWII bombing data. I've used Python to: 
- Filter out just results for Europe and the Mediterranean (ETO and MTO theaters)
- convert the date in the 'MSNDATE' column from a string into a datetime format, in a column called 'missionDate'
- add separate columns of the mission year and mission month ('missionYear' and 'missionMonth', respectively
Also, I've removed most of the columns which are not needed for this MOOC. 
