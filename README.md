# SEO Keyword Clustering Script with Topic Names

This repository contains a Python script (in a Google Colab notebook) that helps you group keywords into relevant topic clusters and adds meaningful topic names to those clusters. This enhancement builds upon the concepts of automated SEO tasks using Python.

## How it Works

The script takes a list of keywords as input (from a `keywords.txt` file) and performs the following steps:

1.  **TF-IDF Vectorization:** Converts the keywords into a numerical representation, filtering out common English stop words to focus on more meaningful terms.
2.  **Affinity Propagation Clustering:** Groups similar keywords together based on their TF-IDF vectors, automatically determining the optimal number of clusters.
3.  **NMF Topic Modeling:** Extracts representative and meaningful topic names for each cluster using Non-negative Matrix Factorization. This helps in understanding the main themes within each group of keywords.
4.  **Output to CSV:** Saves the clustered keywords and their corresponding topic names to a `clusters_with_topics.csv` file.

## How to Use

1.  **Open the Colab Notebook:** Click on the notebook file (it will likely end in `.ipynb`) in this repository. This will open it in Google Colab.
2.  **Upload Your Keywords:** In Colab, you'll need to upload your `keywords.txt` file (a plain text file with one keyword per line). You can do this by dragging and dropping the file into the Colab window or using the file explorer on the left.
3.  **Run the Code:** Execute the cells in the Colab notebook by clicking the "play" button next to each cell, or by using the "Runtime" menu and selecting "Run all".
4.  **Download Results:** After the script finishes, a `clusters_with_topics.csv` file will be created in your Colab environment. You can download this file to your computer by going to the file explorer in Colab, finding the file, clicking the three dots next to it, and selecting "Download".

## Repository Contents

-   `your_notebook_name.ipynb`: (Replace with the actual name of your Colab notebook file, e.g., `seo_keyword_clustering.ipynb`) This is the Python script containing the keyword clustering and topic naming logic.
-   `keywords.txt`: (Example) A sample file where you would put your list of keywords. You'll need to upload your own version of this file to Colab to run the script with your data.

## Credits

This script was inspired by the Python SEO scripts discussed in the Search Engine Land article: [Python scripts for automating SEO tasks](https://searchengineland.com/python-scripts-automating-seo-tasks-395527). The addition of topic names to the clusters is a modification made to enhance the original concept.

## License

MIT License or the Apache License 2.0. 
