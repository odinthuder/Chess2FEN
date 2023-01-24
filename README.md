## To-Do List

1. Collect a dataset of images of chess boards and corresponding FEN or PGN notation for each image.

2. Preprocess the images using `image_preprocessing.py` script to standardize the size and format, and possibly perform image enhancement techniques to improve the quality of the images.

3. Use the `cnn.py` script to train a model using the preprocessed data that can recognize the chess board layout in the images.

4. Use the `ocr_module.py` script to detect and read the FEN/PGN notation

5. Use the trained model to predict the FEN or PGN notation for new images of chess boards using the `main.py` script.

6. Build a user interface to allow users to input an image of a chess board and display the predicted FEN or PGN notation.

7. Test the model on unseen data and evaluate the performance using appropriate metrics.

8. If necessary, fine-tune the model and repeat steps 6 and 7 until satisfactory performance is achieved.

9. Document your findings, insights, and decisions in the README file

10. Add the necessary dependencies in the `requirements.txt` file