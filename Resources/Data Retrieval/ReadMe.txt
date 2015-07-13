Govtrack.us has a REST API call to get information in csv format.

For example:
https://www.govtrack.us/api/v2/vote_voter/?person=400222&limit=2000&order_by=created&format=csv&fields=vote__id,created,option__value,vote__category,vote__chamber,vote__question,vote__number

person is the ID for the person we want, we can find this from .csv files found here https://www.govtrack.us/data/congress-legislators/

limit is there to make sure we aren't requesting to many things. I'll go figure out how to do this with the bulk data (which is the entire dataset)

Check out that link.