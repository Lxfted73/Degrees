## Summary: Degrees of Separation

The "Degrees of Separation" project is a Python script (`degrees.py`) designed to calculate the shortest path of movie connections between two actors. It leverages data from CSV files containing information about people, movies, and their associations.

### Key Features:

- **Data Loading:** The script loads data from CSV files (`people.csv`, `movies.csv`, `stars.csv`) into memory. This data includes details about people (actors), movies, and the actors' roles in various movies.

- **Input Handling:** Users are prompted to input the names of two actors for whom they want to find the degrees of separation. The program intelligently handles scenarios where actor names are ambiguous or not found in the dataset.

- **Path Finding:** Using a breadth-first search algorithm, the script efficiently finds the shortest path between the two specified actors based on their shared appearances in movies. This process involves traversing through the movie connections of each actor until a path is found.

- **Output Generation:** Upon finding the shortest path, the program displays the number of degrees of separation between the two actors. It also lists the movies in which the actors starred together along the path, providing insights into their connections.

### Technical Details:

- **Data Structures:** The script uses dictionaries to store information about people, movies, and their associations.

- **Algorithm:** The breadth-first search algorithm is employed to traverse through the movie connections of actors in a systematic manner, ensuring that the shortest path is found in an optimal way.

- **Error Handling:** The program incorporates error handling mechanisms to gracefully handle scenarios where actor names are not found or ambiguous. It provides informative messages to guide users through the input process.

### Potential Improvements:

- **Optimization:** While the current implementation efficiently finds the shortest path, further optimization (i.e., Alpha-Beta Pruning) could be explored to enhance performance, especially for large datasets.

### Conclusion:

The "Degrees of Separation" project demonstrates effective use of Python programming and data processing techniques to solve a classic problem in the field of network analysis. By leveraging movie connections between actors, the script provides valuable insights into the relationships within the entertainment industry. Its modular design and algorithmic approach make it a versatile tool for exploring actor connections and movie collaborations.
