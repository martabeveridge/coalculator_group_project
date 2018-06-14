# coalculator - javascript webapp

This was the JavaScript group project for the CodeClan programming course. We decided to make a calculator to find out your carbon footprint. The website should take in some input, and display the breakdown of the data in a graph.

## See it in action
See it on my website at <a href="http://coalculator.martabeveridge.uk" target="_blank" rel="noopener">http://coalculator.martabeveridge.uk</a>

## Specification
As this was a CodeClan project, I had to create a project using core Javascript - no front-end frameworks or jQuery were allowed. 

This project was to be completed in 4 days. I outlined my MVP and extensions in my trello board for this project at <a href="https://trello.com/b/nlc0RaCJ/the-coalculator" rel="noopener">https://trello.com/b/nlc0RaCJ/the-coalculator</a>

## Development
We adopted an Agile methodology with 1-1.5 hour sprints focusing on particular features and functionality, as well as doing daily stand-ups and retrospectives. We took turns in being Scrum Master each day and regularly took turns to drive. After writing our MVP we created a few wireframes and user journeys so as to provide a decent UX. We drew UML diagrams in order to design and keep track of developments in our programme.

We built this programme from the back end to the front end, starting with our server and routers, using two models (co2.js and calculator.js) and finishing with three front-end views (form_view.js, results_view.js and graph_view.js). We used the PubSub method to send data around our app. The form view holds the form for user input, the results view holds the users results (i.e. their calculated carbon footprint), and the graph view is nested within the form view. The graph is generated using HighCharts.

## Learning points
We were able to consolidate our learning of vanilla JavaScript and Node.js as well as using API's and data persistence. We worked extremely well as a team, particularly in terms of breaking down our programme into small and manageable chunks and working through these together. We learned the importance of UML diagrams as we became confused at one point after making a change, in terms of where our data was being sent and where it was being received. In future we will make sure to keep a diagrammatic record of any changes to programme structure. The code can certainly be refactored and improved and the CSS needs to be made responsive, but all in all it was an extremely positive experience and we are pleased with the result.
