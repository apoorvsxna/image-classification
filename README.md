# How to run-
The code (final-model.ipynb) can be run on either Jupyter Notebook or [Google Colaboratory](https://colab.research.google.com/). I'd recommend running it on Google Colaboratory, (with the runtime type set to GPU) if your machine is not high-end.
You'll need a dataset to train the model, and the path will have to be modified in the code accordingly. Upload it to your Google Drive.
Here's the [dataset](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf) I used.
Note: Dataset archives can take quite some time to extract, and then some more to upload it to your Google Drive. It's better to just upload the compressed archive itself to your Drive and then unzip it on Colab using better hardware (See first cell in code for reference).
Once you're done with the above, open the code in Colab, connect to a GPU runtime and mount your Drive.
You can skip the first cell if you uploaded an already extracted dataset folder.
Start executing each cell one by one. Be sure to change the path in case you use a different dataset.
The cell containing the model.fit command will take a while to execute. Bear with it. This is where the model is trained. You can change some parameters here if required.
Once all cells are executed, you should see a link at the bottom of the last cell. Click on it to go to the interface.
Here, you can provide input images and get predictions.
