# Facial-Expression-Recognizer
This program could identify face in picture or video and detect if the person is happy, sad or miscellaneuous.
We used HOG(Histogram of Oriented Gradients) to detect facial features. We can use it to circle out the facial part and even put landmarks on it.
For classification, we trained convolutional neural networks on the facial part of the picture/video and make a judgement of what expression the selected person is presenting. We only have three expressions right now, but it is very optimistic to have more expressions to classify. We have an accuracy around 65% right now, and we are still trying new algorithms to improve the performance.
