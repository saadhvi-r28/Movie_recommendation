This project explores building a movie recommendation system that suggests movies similar to a user's choice. The system leverages movie information such as genres, keywords, cast, crew, and overviews to identify content-based relationships.

Movie data is obtained from CSV files and stored in a database for easy access. Textual data undergoes cleaning and preprocessing.

The pre-processed textual data is combined into a single feature that represents a movie's overall content. This feature is then converted into a numerical format suitable for comparison.

The system calculates the similarity between movies using cosine similarity, a measure of content resemblance based on the numerical representations. Based on this similarity score, the system recommends movies with content similar to a user's chosen title.
