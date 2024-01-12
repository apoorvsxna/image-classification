# How to run-
1. The code (final-model.ipynb) can be run on either Jupyter Notebook or [Google Colaboratory](https://colab.research.google.com/). I'd recommend running it on Google Colaboratory, (with the runtime type set to GPU) if your machine is not high-end.
2. You'll need a dataset to train the model, and the path will have to be modified in the code accordingly. Upload it to your Google Drive.
Here's the [dataset](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf) I used.

Note: Dataset archives can take quite some time to extract, and then some more to upload it to your Google Drive. It's better to just upload the compressed archive itself to your Drive and then unzip it on Colab using better hardware (See first cell in code for reference).

3. Once you're done with the above, open the code in Colab, connect to a GPU runtime and mount your Drive.
4. You can skip the first cell if you uploaded an already extracted dataset folder.
5. Start executing each cell one by one. Be sure to change the path in case you use a different dataset.

The cell containing the model.fit command will take a while to execute. Bear with it. This is where the model is trained. You can change some parameters here if required.

6. Once all cells are executed, you should see a link at the bottom of the last cell. Click on it to go to the interface.
7. Here, you can provide input images and get predictions.
![3](https://github.com/apoorvsxna/image-classification/assets/112375644/9cdd0072-d10e-4952-993c-7c7b530b32ba)
![2](https://github.com/apoorvsxna/image-classification/assets/112375644/7caa58a6-0607-492c-9c16-317af42dbb8e)
![1](https://github.com/apoorvsxna/image-classification/assets/112375644/d96b6979-31d1-409c-8ef7-dc7fd6048dd4)
