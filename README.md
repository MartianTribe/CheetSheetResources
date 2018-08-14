# CheetSheetResources

## Overivew

CheetSheet is a tech aggregator app I built in 2017 and have been continuously updating. The basic idea of the app was to have a note taking app a little more robust than Apple's Notes and less robust than some others on the market. The app enables you to enter a topic, subtopic, content and up to five images. It was made to be a study buddy of sorts. 

As users (read that as my kids) started using it they made request for additional features - like access to Khan Academy and Quizlet flashcards. And just like that the app went from a study buddy to a study resource. As of now there are six resources for study material: 

* Khan Academy 
* Quizlet
* PBS Learning Media
* Merriam Webster Dictionary
* Newton
* Congress of Library Prints

For the most part the app calls their open API, passes search data through a query string and post the returns to a tableview. In the case of the Merriam Webster and Newton I just display the results. For the rest, selecting a table cell opens the page associated with that content in a webview from the originators site. 

For example, clicking a Khan Academy lesson would then open that lesson on Khan Academy. 

This project is a spinoff of that project. CheetSheetResouces is a SDK that will make those API calls and return the data, allowing the user to then display it as they see fit. 