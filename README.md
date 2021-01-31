# Restaurants market research
Investors are interested in the current market conditions. We've been asked to prepare some market research. We have open-source data on restaurants in LA.

# We'll go through the following steps:

- Load the data and prepare it for analysis
- Data analysis

  - Investigate the proportions of the various types of establishments. Plot a graph.
  - Investigate the proportions of chain and nonchain establishments. Plot a graph.
  - Which type of establishment is typically a chain?
  - What characterizes chains: many establishments with a small number of seats or a few establishments with a lot of seats?
  - Determine the average number of seats for each type of restaurant. On average, which type of restaurant has the greatest number of seats? Plot graphs.
  - Put the data on street names from the address column in a separate column.
  - Plot a graph of the top ten streets by number of restaurants.
  - Find the number of streets that only have one restaurant.
  - For streets with a lot of restaurants, look at the distribution of the number of seats. 
  
# Data description

_rest_data_ table:

- object_name — establishment name
- chain — chain establishment (TRUE/FALSE)
- object_type — establishment type
- address — address
- number — number of seats
