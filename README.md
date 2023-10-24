# Project1 - Shark attacks arround the World

![elgif](https://media1.giphy.com/media/PfHrNe1cSKAjC/giphy.gif?cid=ecf05e47hngmfxpo03mjabb7bml69pvkc15mzkrkicjgimtr&ep=v1_gifs_search&rid=giphy.gif&ct=g)

This project involves the analysis of a dataset containing information about shark attacks. The dataset was processed and visualized using Python, primarily using the Pandas, Matplotlib and Seaborn libraries.

## Libraries Used
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib**: Utilized for creating static data visualizations.
- **Seaborn**: Employed for creating more aesthetically pleasing and informative visualizations.
- **Numpy**: Imported for performing numerical operations and calculations, such as data filtering and transformations.

## Data Cleaning
1. Reading the Data:
   - The dataset was read from a CSV file.
   - Column names were converted to lowercase and spaces were replaced with underscores for consistency.

2. Creating a Subset:
   - A subset of relevant columns was selected for analysis, containing information such as date, year, type of attack, location, and more.

3. Handling Missing Data:
   - Rows with all NaN (blank) values were removed to ensure data quality.

4. Cleaning 'Date' Column:
   - The 'date' column was filtered to match the pattern DD-Mon-YYYY, and then converted to a datetime format.

5. Adding 'Weekday':
   - A new 'weekday' column was created to represent the day of the week corresponding to each date.

6. Cleaning 'Fatal (Y/N)' and 'Species':
   - The 'fatal_(y/n)' column was cleaned to extract 'Y' or 'N' values.
   - The 'species_' column was cleaned and a new 'species_clean' column was created to standardize species names.

## Visualizations and Analysis
- The following hypotheses were explored:
  1. People die more today by shark attacks than before?
     - A line plot was created to visualize the trend of fatal and non-fatal shark attacks over the years.
  2. In the city with the most attacks, was the majority of the attacks provoked by humans?
     - A bar plot was used to show the type of attacks in the top 10 countries with the most shark attacks.
  3. Is there a day of the week with the more attacks?
     - A line plot was created to visualize the number of shark attacks on different weekdays over the years.
  4. If you are attacked by a specific species, do you have a higher chance of a fatal outcome?
     - A pie chart and a contingency table were used to analyze the relationship between species and fatality.

## Conclusion
During the analysis of the shark attack dataset, several interesting observations were made:

1. **Increased Survival Rates**: The analysis of the data suggests that in recent years, there is a higher chance of surviving a shark attack. The percentage of fatal shark attacks appears to have decreased over time, indicating improved safety measures or changes in behavior that reduce the lethality of such incidents.

2. **Weekend Attack Patterns**: It was observed that there is an increase in the number of shark attacks on weekends. This interesting pattern may be attributed to higher recreational activities near the coast during weekends, which could lead to an elevated risk of shark encounters.

3. **Higher Fatality with Tiger Sharks**: The analysis reveals that shark attacks involving tiger sharks have a higher percentage of fatal outcomes compared to other shark species. This information may be valuable for those involved in ocean-related activities, emphasizing the importance of being cautious when encountering this species.

These observations provide valuable insights into the trends and patterns of shark attacks over time, which can be beneficial for public awareness and safety measures near coastal areas.

## **So, be thankful to be alive and I hope you don't find a shark**


# Link of apresentation 
https://www.canva.com/design/DAFyF2rRwWA/GqvPwcMWRvFzlu7_9v_C_Q/edit?utm_content=DAFyF2rRwWA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
