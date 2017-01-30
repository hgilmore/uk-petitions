# uk-petitions

*Last data extract - 9pm 30th January 2017*

### Find out the percentage of people from your constituency that have signed a petition.

This Jupyer notebook take the data from a UK petition and calculates what percentage of all UK constituencies votes for it.

Open **`vote_percentage.csv`** to view data for your constituency.

### Which petition?

The notebook is currently taking data from [this petition](https://petition.parliament.uk/petitions/171928). You can edit the URL which pulls the JSON to take a look at any petition.

(_Prevent Donald Trump from making a State Visit to the United Kingdom_)

### Notes on method

- Assumes signature figures from petition.parliament.uk are valid. No cleaning of the data possible for erroneous entries.
- Takes electorate size figures from [Wikipedia](https://en.wikipedia.org/wiki/List_of_United_Kingdom_Parliament_constituencies). Using 2015 data.
- Percentage share of constituency which voted for the petition is the number of signatures from the petition site divided by the size of the Electorate from the Wikipedia article.

### Files

`vote_percentage.csv` - CSV file with the percentage of each UK constituency which signed the 'Prevent Donald Trump from making a State Visit to the United Kingdom' petition.

`Constituencies Signing UK Petitions.ipynb` - Jupyter notebook with calculations.

`uk_constituency_data.csv` - Data extract from Wikipedia
