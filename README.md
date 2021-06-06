# Produce Pal

## Application Summary
Have you ever been to a farmer’s market or specialty grocery store and seen an item and thought, “what kind of strange looking fruit/vegetable is that?” Gone are the days of having to search Google Images for *spikey broccoli* (that’s romanesco) or *giant green grapefruit* (some might call this a pummelo) to figure out what the real name for that item is. With Produce Pal, simply use your iOS device’s camera to snap a photo of your item, or upload one from your camera roll, and within seconds the app will give you the two most likely classifications of that fruit or vegetable.

## Data 
https://drive.google.com/drive/folders/1G_ECh2THEP5QG8vkGNg30gan4oHtPK9b?usp=sharing

## Technologies Used
- Google Colab: Hosted Jupyter Notebook with access to free GPU and TPU. Used to create train/test datasets and for training of model. 
- Keras: Deep learning API with a Python interface. Acts as an interface for the machine learning platform Tensorflow. Used transfer learning with the pre-trained MobileNet for training of Produce Pal model.
- Xcode: Apple’s integrated development environment used to develop software for iOS devices. Used to build the Produce Pal application software.
- coremltools: A Python package that allows easy conversion of third-party models to the Core ML format for itegration of machine learning models into iOS apps. Used coremltools to convert Keras model to Core ML format.
