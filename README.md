# IMDBProject
https://public.tableau.com/views/IMDBProject_17249719688350/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

When I first started the project, I initially had one goal: to see the most popular genres in foreign countries. Since the last complete year in the IMDB file was 2021, I chose to look at 20 years of data. 2001-2021. The data itself came in .TSV format, yet had escape characters saved in the rows. Due to this, I had to convert the files from TSV to CSV and rid it of the escape characters so I could load it into DBeaver for SQL analaysis. 

Next I looked at the genre category, but unfortunately, movies can choose up to three genres, yet IMDB doesn't rank which genre is most fitting. This means that multiple genres can fall under the umbrella of drama. Crimes, thrillers, fantasy, and more can all also be drama. This created a map with very little variance.


![ImdbDrama](https://github.com/user-attachments/assets/2328b3d3-1aba-4ff7-a257-53477595c392)


To overcome this setback,I chose the 2nd highest rated genre for every country, and this showed a more complete picture.


![ImdbGenre](https://github.com/user-attachments/assets/6b0a4af2-13fe-4349-ab24-a1df08b566c6)

Here you can see how countries like Ireland have grown their animation productions and how crime has become a popular genre.

Since I still did have the data, I decided to add a few more categories that can be found in the full Tableau page.
