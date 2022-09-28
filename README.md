# About

This is a movie recommender system that uses Cosine Similarity algorithm to predict the potential movie ratings of the unwatched movies.

## Running Instructions

- Open the colab environment (https://colab.research.google.com/)
- Upload the code file(final_project.ipynb) and dataset.txt to google drive any folder you would like to
- At line below rename "folder name" to you create before 
	dataset_path = '/content/drive/My Drive/Colab Notebooks/folder name/dataset.txt'
- First, run the below code to mount google drive. it will connect colab to drive
	from google.colab import drive
	drive.mount('/content/drive')
- Continue running the code blocks
- To get the result in the same folder you need to change the folder name again at the last line as described below
	np.savetxt(r'/content/drive/My Drive/Colab Notebooks/folder name/output_matrix.txt', result, fmt='%d', delimiter=' ',newline='\r\n')
