# 🎥🍿 Movie Stat Plot 🎥🍿 

## Data

For my class project, I put together multiple visualizations for the data of over 1000 movies I pulled from the Internet Movie Database. 

This is a two pronged project both centralizing around the same CSV!

The CSV is data from ~1000 movies off of IMDB
The fields include actors, genres, runtime, revenue, release year, and more!

The first prong is a customized scatter plot.
You decide what you want to see. You can choose the X-Axis and the Y-Axis!
Then you can decide what genres you want plotted, or what actor you want plotted
You can hover over each dot to see what movie it is!

The second prong is an actor network.
It is a graph of actors linked by shared movies, you can also choose an actor as an origin for the graph!

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

## Prototypes/Iterations

I began by making a scatter plot with an added layer of interactivity where you can choose which genres are displayed.
![Screenshot 2023-02-20 at 5 03 57 PM](https://user-images.githubusercontent.com/74930526/220204962-4e3258ac-35a5-4a8e-a834-f168ac2cb96e.png)
(https://vizhub.com/KyleWynnM/5b359846e6d048ef813ad35647795614?edit=files&file=viz.js)

Then I created a proof of concept visualization of this data. It's an interactive scatter plot and it shows the IMDB rating versus the Revenue accumulated by the movie. I added axes, and axes titles.
![Screenshot 2023-02-20 at 3 52 50 PM](https://user-images.githubusercontent.com/74930526/220196828-f4ec6967-b955-44cb-99f0-6b7792936cf1.png)
(https://vizhub.com/KyleWynnM/c50f1f2a02654434a755eebc13077d1a?edit=files&file=scatterPlot.js)

I then added the ability to set what axes were used on the scatterplot 
![Screenshot 2023-04-28 at 6 37 28 PM](https://user-images.githubusercontent.com/74930526/235265046-6eeebb3e-d295-492a-9d91-f49ec97fa8eb.png)
(https://vizhub.com/KyleWynnM/13adef6291504bc18eee665ba18cced6)

Then came coloring the dots to differentiate the genres on the plot.
![Screenshot 2023-04-28 at 6 38 56 PM](https://user-images.githubusercontent.com/74930526/235265175-0588031f-45c6-44e9-a529-40e427140ad8.png)
(https://vizhub.com/KyleWynnM/e680e7dbc28c433db67da71df8485785)

Next came the ability to filter the plot by the actors that appeared in the movies. Additionally, I added a hover feature so you can see what dot is which movie.
![Screenshot 2023-04-28 at 6 39 55 PM](https://user-images.githubusercontent.com/74930526/235265266-26a8096a-b821-4542-9d1a-0a6bc059e7fc.png)
(https://vizhub.com/KyleWynnM/bb3d1d3de2a34fa885e96f7578d95b01)

I proceeded to clean up the code behind the scenes, and also clean up the look of the visualization to make it more aesthetically pleasing.
![Screenshot 2023-04-28 at 6 41 32 PM](https://user-images.githubusercontent.com/74930526/235265420-11af3219-59df-429a-a199-1f6bd4e2e1d1.png)

Along with that came a guide and "about" section for the site.
![Screenshot 2023-04-28 at 6 42 19 PM](https://user-images.githubusercontent.com/74930526/235265489-099be22c-08e5-4bcb-90ab-0c810a558e9a.png)

Next, I added a network graph, a different direction from my initial scatter plot. This allows you to see how actors link with each other based on the movies they are in.
![Screenshot 2023-04-28 at 6 42 59 PM](https://user-images.githubusercontent.com/74930526/235265564-455da48c-b510-4cc0-86e3-74c93a26035c.png)
(https://vizhub.com/KyleWynnM/662a58e6f0554b71bb8daa34b6b55b87)

Finally, I added an actor seach function for the network, allowing you to narrow down the network to an actor of your choosing.
![Screenshot 2023-04-28 at 6 46 50 PM](https://user-images.githubusercontent.com/74930526/235265952-50500fb9-3efc-40af-9666-b2467c59d86d.png)


## Milestones
(I'm keeping this from the original proposal, as I am satisfied with the number and scale of goals I fulfilled!)
(Each bullet point represents a week(ish), maybe less maybe more)
* First, I'd like to make the scatter plot out of different symbols denoting different landmarks (e.g. a star for the highest rated movie in the plot)
* I'd like to add the drop down menu axes to let the user choose what they see
* I'd like to add the "and" and "or" radio buttons to allow you to choose whether you want the union or intersection of genres on the plot for example
* I'd like to add the actor/director feature to let you plot movies specific to various actors or directors
* I'd like to add a hover feature to let you see which dot represents which movie
* I'd like to start connecting the movies by actor or director as a graph
