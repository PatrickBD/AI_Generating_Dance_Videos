# AI-Generating-Dance-Videos
Using Autoencoder CNN and Stacked LSTM RNN to train an computer to generate it's own dance videos

This code is made to run on Kaggle Kernels. Fork the code here: https://www.kaggle.com/valkling/how-to-teach-an-ai-to-dance

Watch a sample output from this notebook here: https://youtu.be/1IvLdoXSoaU

NLP and image CNNs are all the rage right now, here we combine techniques from both to have a computer learn to make it's own dance videos. This notebook is a consolidation of 3 smaller notebooks I made for this project:

Part 1-Video Preprocessing: We will take the frames from a dance video of silhouettes, preprocess them to smaller and simpler, and add them to a zip file in sequence.

Part 2-Autoencoder Compression: To save even more memory for our model, we will compress these frames with an Autoencoder into a much smaller numpy array.

Part 3-Train AI w/ RNNs: We will put these compressed frames into sequences and train a model to create more.

I based this kernel off the project in this youtube video: https://www.youtube.com/watch?v=Sc7RiNgHHaE While he does not share his code, the steps expressed in the video were clear enough to piece together this project. Thanks to Kaggle's kernals GPU and some alterations, we can achieve even better results in less time than what is shown in the video. While still pretty computationally expensive for modern computing power, using these techniques for a dancing AI opens up the groundwork for AI to predict on and create all types of different videos.
