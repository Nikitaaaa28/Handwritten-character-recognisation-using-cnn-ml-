# Handwritten-character-recognisation-using-cnn-ml-
In the pursuit of advancing human-computer interaction, this report presents a comprehensive analysis and implementation of a hand gesture recognition system utilizing computer vision and deep learning techniques. The integrated system combines the robust capabilities of OpenCV and the predictive power of a convolutional neural network (CNN) implemented using the Keras framework. 
The cornerstone of the developed solution lies in a meticulously trained CNN model, loaded from the 'devanagari_model.h5' file, specifically designed for the recognition of handwritten characters. A well-defined dictionary, denoted as letter_count, serves as a key reference mapping numeric class labels to their corresponding linguistic representations. This not only facilitates accurate classification but also enhances the interpretability of the system's outputs. 
 The main function orchestrates the real-time capture of video frames through OpenCV, employing a colour-based segmentation approach to isolate hand gestures. The dynamic tracking of hand movement is achieved through the application of contour analysis and circular approximations. The resultant system not only detects hand gestures but also associates them with specific characters, presenting the recognized output in a structured and informative manner.
This report delves into the technical intricacies of the implemented solution, providing insights into the image processing pipeline, contour analysis, and the underlying deep learning model. The amalgamation of these components culminates in a sophisticated hand gesture recognition system poised to contribute to the evolving landscape of human-computer interaction.
