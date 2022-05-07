# Neural Network
Neural networks, also known as artificial neural networks (ANNs) or simulated neural networks (SNNs), are a subset of machine learning that provide the foundation of deep learning techniques. Their name and form are inspired by the human brain, and they replicate the way real neurons communicate with one another. Training data is used by neural networks to learn and increase their accuracy over time. However, once these learning algorithms have been fine-tuned for accuracy, they become formidable tools in computer science field, allowing scientists to categorize and cluster data at rapid speeds. When compared to manual identification by human specialists, tasks in speech recognition or picture recognition can be completed in minutes rather than hours. Google's search algorithm is one of the most well-known neural networks.

## Dataset
In this project, I will use Flight Price Prediction from kaggle.
 - 1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
 - 2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.
 - 3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.
 - 4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
 - 5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
 - 6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
 - 7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.
 - 8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
 - 9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
 - 10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
 - 11) Price: Target variable stores information of the ticket price.

## Task
In this project I will try to predict the log flight price using neural network algorithm.
