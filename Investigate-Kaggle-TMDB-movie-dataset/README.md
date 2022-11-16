# Investigate TMDB-movie Dataset

## Introduction 

What can we say about the success of a movie before it is released? Are there certain companies that have found a consistent formula? Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?

This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.

In this project i choose to work with TMDb movie dataset .It This contains information about 5000 movies collected from The Movie Database (TMDb), including user profit and revenue. Before jumping into analysing the data, i did some data wrangling and data cleaning .

## Conclusion

As a conclusion, It's safe to say that movie making has increased over the past year, thow the industry is having drops because of quaratine and covid19 since 2020 . I noticed that for a movie to be successful , by this a movie which made high profit during it's release , an excellent director have to be choosen and a big budget needed for it. Also , audience are interested to watch Drama and Comedy movie, while the most profitable movie genres are action and adventure.

## Limitations

Limitations that i encountered during my analysis ;

* Some columns in both csv files of datatype json. In order to get the data that i want, i developed a function to extract that information. For example the column genres .The solution was to handle it the same way as a dictionary and extract values in the key 'name'.I proceeded by parsing all columns the same way except for the column director in which i need to check first if a certain dictionary has the value 'director' to the key 'job'.

* While checking movie genres i encountered an empty string that i decided to change it with the value 'other' inorder to get better results when investigating movie genres.



