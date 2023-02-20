# 🎥🍿 Movie Stat Plot 🎥🍿 

## Data

The data I propose to visualize for my project is the revenue, ratings, and more for the 1000 movies I pulled from the Internet Movie Database. 

## Prototypes

I began by making a scatter plot with an added layer of interactivity where you can choose which genres are displayed.
![Screenshot 2023-02-20 at 5 03 57 PM](https://user-images.githubusercontent.com/74930526/220204962-4e3258ac-35a5-4a8e-a834-f168ac2cb96e.png)
(https://vizhub.com/KyleWynnM/5b359846e6d048ef813ad35647795614?edit=files&file=viz.js)

Finally, (so far) I’ve created a proof of concept visualization of this data. It's an interactive scatter plot and it shows the IMDB rating versus the Revenue accumulated by the movie. I added axes, and axes titles.
![Screenshot 2023-02-20 at 3 52 50 PM](https://user-images.githubusercontent.com/74930526/220196828-f4ec6967-b955-44cb-99f0-6b7792936cf1.png)
(https://vizhub.com/KyleWynnM/c50f1f2a02654434a755eebc13077d1a?edit=files&file=scatterPlot.js)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which actors/directors perform the best critically?
 * Which actors/directors perform the best financially?
 * Which actor-director pairings are the most prominent?
 * Which actor-director pairings are the most successful?
 * Which genres perform the best critically?
 * Which genres perform the best financially?
 * Where are there clusters in the plots for every genre?
 * How does metacritic compare to IMDB for ratings?

## Sketches

The first sketch I had was for a simple scatter plot that would show how the revenue relates to the critical rating of various movies, and I felt I could employ color encoding to show how genres perform across this graph.
![IMDBGraph](https://user-images.githubusercontent.com/74930526/220202090-70406735-1f92-4146-a66b-c4040a5b6d87.jpeg)

After consideration and feedback, I felt it was too much to use color to show the genres with just colors, especially since many movies have multiple genres. Additionally, I just felt like the graph might get too crowded and ambiguous and become hard to differentiate clusters. With this in mind, I came up with an idea for a control panel where you can actively choose which genres are displayed, and thereby examine the movie data on your own.
<img width="1061" alt="Screenshot 2023-02-20 at 4 40 39 PM" src="https://user-images.githubusercontent.com/74930526/220202296-68617610-9b53-4b19-b3a3-a591f67fae94.png">

My thoughts expanded from here. Why would I at all limit what the user could see when all of that data is readily accessible? With this in mind I thought perhaps the user could have drop down menus for the axes and thereby choose what they want to compare regarding the available movies. For example, maybe you want to compare runtime to critical rating? Or Metacritic rating to IMDB rating? It would be a quick addition and would immensely increase the opportunities available.
![Scan 1](https://user-images.githubusercontent.com/74930526/220202649-608e7786-4943-4871-9729-93c6496190b2.jpeg)

Along those lines, why would I limit the user to just sort by genres? I thought I could also add in a search feature to allow them to display the movies by specific actors or directors for example.
![Scan 1](https://user-images.githubusercontent.com/74930526/220203493-3b515778-1463-4f8d-8761-a535dbd307e3.jpeg)

From there, Prof. Curran, pointed out that with this network of actors and directors I could make a network graph! I thought maybe there's someway I could do that and mix it with the scatter plot, still working on that thought, not quite sure yet.
<img width="700" alt="Screenshot 2023-02-20 at 4 37 32 PM" src="https://user-images.githubusercontent.com/74930526/220203472-87c75b76-fd30-4a06-9946-471d34761710.png">


## Open Questions

My main concern is the hover feature, and the network concept.
The hover feature (letting the user hover dots to see what movie is which dot) I feel is the most involved and I'm nervous there's too much going on for me to handle.
The network issue is a matter of imagination. I want to figure out some way to mix it with the scatter plot, but I've struggled to figure it out.

## Milestones
(Each bullet point represents a week(ish), maybe less maybe more)
* First, I'd like to make the scatter plot out of different symbols denoting different landmarks (e.g. a star for the highest rated movie in the plot)
* I'd like to add the drop down menu axes to let the user choose what they see
* I'd like to add the "and" and "or" radio buttons to allow you to choose whether you want the union or intersection of genres on the plot for example
* I'd like to add the actor/director feature to let you plot movies specific to various actors or directors
* I'd like to add a hover feature to let you see which dot represents which movie
* I'd like to start connecting the movies by actor or director as a graph
