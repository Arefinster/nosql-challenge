# NoSQL-challenge

This is a comprehensive exercise on NoSQL database query using PyMongo and the MongoDB server.
In the beginning, the mongodb server is launched from the windows command prompt. Once the connection was extablished,
another command prompt window was opened from the resources folder where the json format database was saved. The json
database was then imported using the command: mongoimport --type json -d uk_food -c establishments --drop --jsonArray 
establishments.json

39779 documents were imported.

The exercise contains two main parts. In the first part, namely NoSQL_setup, basic queries and operations were done 
that included, find, insert, update, count, and pretty printing.

In the second part, advanced queries were constructed using various operators, and the results were converted to pandas
data frames. Lastly, aggregated queries were constructed to form a pipeline query, convert to pandas data frame and print.






NOTE: I have worked on this assignment alone. However, I closely followed the code in the class activities.