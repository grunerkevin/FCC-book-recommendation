# Book Recommendation Engine using KNN

This project is part of the Machine Learning with Python curriculum of freeCodeCamp. It aims to create a book recommendation algorithm using K-Nearest Neighbors (KNN).
## Dataset
The dataset used for this project is the Book-Crossings dataset, which contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.
## Requirements
This project requires the following Python libraries:
- pandas
- numpy
- sklearn
This project also requires Google Colaboratory, a cloud-based platform that allows you to run Python code in a browser.
## Installation

To install this project, follow these steps:
- Clone this repository to your local machine or your Google Drive.
- Open the notebook file `book_recommendation_engine.ipynb` in Google Colaboratory.
- Run the code cells in the notebook to import and clean the data, create the model, and test the function.
## Usage

To use this project, you can call the function `get_recommends` with a book title (from the dataset) as an argument. The function will return a list of 5 similar books with their distances from the book argument. For example:

```python
get_recommends("The Queen of the Damned (Vampire Chronicles)")

Output:

["The Queen of the Damned (Vampire Chronicles)",
	 ['The Mummy or Ramses the Damned', 0.7279221],
	 ['The Tale of the Body Thief (Vampire Chronicles)', 0.7420294],
	 ['The Vampire Lestat (Vampire Chronicles)', 0.74906254],
	 ['Interview with the Vampire', 0.77224064],
	 ['Merrick (Vampire/Witches Chronicles)', 0.7802236]
]
