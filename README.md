# 🎥🍿 Movie Stat Plot 🎥🍿 

## Data

The data I propose to visualize for my project is the revenue, ratings, and more for the 1000 movies I pulled from the Internet Movie Database. 

## Prototypes

I’ve created a proof of concept visualization of this data. It's an interactive scatter plot and it shows the IMDB rating versus the Revenue accumulated by the 

![Screenshot 2023-02-20 at 3 52 50 PM](https://user-images.githubusercontent.com/74930526/220196828-f4ec6967-b955-44cb-99f0-6b7792936cf1.png)
(https://vizhub.com/KyleWynnM/c50f1f2a02654434a755eebc13077d1a?edit=files&file=scatterPlot.js)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * (insert your question or task here) How can I 
 * (insert your question or task here) Is there any correlation between X and Y?
 * (insert your question or task here) Are there interesting spatial patterns in X?
 * (insert your question or task here) How many X are there across different Y?
 * (insert your question or task here)
 * (insert your question or task here)
 * (insert your question or task here)

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

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)

## Milestones

(for each week, estimate what would be accomplised)
