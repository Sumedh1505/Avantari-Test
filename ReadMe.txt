Procedure:

1. Checked the Images how they were looking
2. Image size was (512, 512, 3)
3. Reduced image sixe to (128, 128) since image size was too heavy to hold my pc (lower configuration pc)
4. Divided Data in 80-20 Train-Test Split
5. Since I'm not allowed to use any predifined AutoEncoder (like sckit-learn's convencoders), i built my own custom autoencoder.
6. I have used simple conv2d layers with different kernal size
7. Lastly, taking the Encoder Layers output, i tried to find similar images of a given test image


NOTE: Reason not used Colab or Ibm cloud or any other thing, I have to revist that tab, every 15-20 mins which was tough (taking care office work)
