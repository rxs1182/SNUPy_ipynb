# covid-19-polls

This repository contains the data behind [How Concerned Are Americans About The Coronavirus?](http://projects.fivethirtyeight.com/coronavirus-polls/)



## Polls

`covid_approval_polls.csv` contains polls that ask Americans whether or not they approve of the way Trump is handling covid-19.

`covid_concern_polls.csv` contain the polls ask Ameicans how concerned they feel about aspects of the outbreak such as infection and economic impact.

Column | Description
---------|-------------
`subject`| For approval polls, this column marks whose handling of covid-19 the approval poll is about (e.g. `Trump`). For concern polls, this column identifies which subject the poll is asking Americans about (for example, `concern-infected` vs `concern-economy`)
`party`| Party of respondents
`startdate` | Start date of poll
`enddate`| End date of poll
`pollster` | Organization that conducted the poll
`sponsor` | Organization that sponsored the poll
`samplesize` | Size of polling sample
`population` | `A` for adults, `RV` for registered voters, `LV` for likely voters
`tracking` | `TRUE` if the poll is a tracking poll, meaning that the pollster is releasing data with overlapping samples
`text` | Text of the question the pollster asked
`url` | Link to the poll

