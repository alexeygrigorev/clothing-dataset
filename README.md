## Clothing dataset
Over 5,000 images of 20 different classes.

<img src="https://repository-images.githubusercontent.com/296936930/66951d00-fabe-11ea-823a-cfdec51c055e" /> 

This dataset can be freely used for any purpose, including commercial:

For example:
* Creating a tutorial or a course (free or paid)
* Writing a book
* Kaggle competitions (as an external dataset)
* Training an internal model at any company

### Data

The `images.csv` file contains:

* `image` - the ID of the image (use it to load the image from `images/<ID>.jpg`)
* `sender_id` - the ID of a person who contributed the image
* `label` - the class of the image
* `kids` - flag, `True` if it's clothes for kids 

### Links

* If you're looking for a subset of the clothing dataset, check here: https://github.com/alexeygrigorev/clothing-dataset-small
* You can read more about this dataset here: https://medium.com/data-science-insider/clothing-dataset-5b72cd7c3f1f
* This dataset is also awailable on Kaggle (with images in higher resolution): https://www.kaggle.com/agrigorev/clothing-dataset-full/ (please upvote it!)

### Top-10 subset

Images of some classes don’t appear very often. Training a neural network to predict these classes is quite difficult — we need at least 100-200 images of each class to make a meaningful model.

That’s why, for educational purposes, we created a subset of the full dataset that covers only the top-10 classes.

Check it here: https://github.com/alexeygrigorev/clothing-dataset-small


### Examples

* https://www.kaggle.com/agrigorev/collage
* [Train a self-supervised model using lightly on the clothing-dataset](https://docs.lightly.ai/tutorials/package/tutorial_simclr_clothing.html)
* Add a link here

Do you use this dataset somewhere? Please submit a PR with a link


### Acknowledgements 

We'd like to thank

* Kenes Shangereyev and [Tagias.com](tagias.com) for helping with 3000 images
* All the 32 people who contributed their images to the dataset via the forms:
  * [Patricia Goldberg](https://www.linkedin.com/in/patricia-goldberg/)
  * [Chandana Priya](https://www.linkedin.com/in/chandanapriyanivarthi/)
* Everyone who supported the initiative by engaging with the announcements on social media   

It wouldn't be possible to collect this dataset without your help!
