# Stack-Overflow-Recommendation-System
This repository has the entire code for the thesis "Stack-Overflow-Recommendation-System". This is written entirely in Python and Jupyter notebooks. This contains two .ipynb files. The first file is called "Thesis data collection" and the second one is called "SOQRS".

Thesis data collection:
In the data collection process, this file is used. This entirely uses the stack exchange api to fetch data from Stack Overflow. To fetch the data it takes a lot of time. To run this file, we need an access token from the Stack Exchange API. This is because users are allowed to hit Stack Overflow only 300 times per day. Since we need more hits, access tokens provide us with 10000 hits per day. We can get this access token through the API. We need to replace this with the new token in the code and run the entire code. This process may take a few days to fetch the data.
SOQRS:
This is the actual code for the model. We just need to load the data files which are in the data tab. Once the file has been loaded, we can run this entire code. Follow the commands in the notebook to run the code. 
