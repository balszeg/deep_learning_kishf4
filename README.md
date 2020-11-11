# Transfer learning for a pre-trained model 

Created for VITMAV45 course as the fourth mid-term assignment.

The given task was that, to choose 3 different category from Google Open Image database. Then download and separate 600 images per category, in 400 training, 100 validation, 100 test splitting. With these data, choose a well known base model and retrain it. I chose Imagenet V3 for this task.

I used a toolkit for getting the necessary datas. The toolkit can be found here: [link](https://github.com/EscVM/OIDv4_ToolKit)

I set up the compulsary flags and settings in the toolkit, so the user doesn't have to. I didn't write about these details, but in the link above it can be read.

The hyperparameters were chosen based on experimentation and recommendations.

The logs file can be found in this Google Drive directory: [link](https://drive.google.com/drive/folders/1UGNP5xxmJBi1rSNGhlgMMS6hZDYlBaob?usp=sharing)

As for the results, it can be seen on the test result, that it was a successful training. Altough I would say, the network may overfitted the dataset.
