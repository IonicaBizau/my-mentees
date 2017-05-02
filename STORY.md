## My Mentees Map

It's so nice to talk with people from different countries, with different beliefs and phylosophies, coming from different classes and cultures but wanting having one goal: to learn coding (or fixing their existing app).
I do this on [Codementor.io](https://codementor.io).

Few months ago I came up with an idea: since I know these folk are from different parts of the world, it would be interesting **to visualize where they are from**.

I asked the Codementor staff to provide me the data I needed: a table containing the anonymoused user ids and the country of origin, one row for each session I had.

The main reason for making the user ids anonymous is mainly to preserve the mentee privacy (I'm not interested to visualize their identity on the map). However, I do want to know how many sessions I had with a specific mentee. Hence, the *anonymoused user ids*.

The data they provided is a boring CSV file, looking like this:

```csv
id,country
223102,United States
21232,United States
45481,United States
28186,Australia
32239,United States
223510,Denmark
215425,Canada
...
```

The first column is the id which is unique for one user (not associated with their identity in any way) and the second column is the country they had the session from (detected by the ip).

When we put this data on the map it doesn't look that boring anymore:


