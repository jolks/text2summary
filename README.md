Jupyter Notebook running on Google Colab or Paperspace Notebook that attempts to summarize text with deep learning.

This work was presented on 2018 August 11 in [Machine Learning Tokyo (MLT) Project Presentation Day](https://www.meetup.com/Machine-Learning-Tokyo/events/253269325/). Presentation slides can be viewed [here](https://docs.google.com/presentation/d/1kjwEvth-VJn-qZWc73lEfwc9pHTux39FLHPjZyO_QJk/).

# Steps to Reproduce this Work
1. Upload `text2summary_colab.ipynb` file to Google Drive.
2. Open the file with Colaboratory.
3. Run :)
4. In case of `ResourceExhaustedError` error, try lowering down the `ratio` parameter, or running the notebook on a more powerful machine e.g. Paperspace Notebook P100 (Base container: `ufoym/deepo:all-py36-jupyter`).
5. In case of any problem running this notebook, please submit an issue [here](https://github.com/jolks/text2summary/issues).

# Dataset
* [DeepMind Q&A](https://cs.nyu.edu/~kcho/DMQA/)

# Deep Learning Applied
* Word-level Sequence-to-Sequence LSTM.

# TODO
* Based on the feedbacks received, I should use dataset that contains topic or subject that I want to summarize. This will help to provide better context.

# References
* https://towardsdatascience.com/how-to-create-data-products-that-are-magical-using-sequence-to-sequence-models-703f86a231f8
* https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html
* https://en.wikipedia.org/wiki/Automatic_summarization
* https://github.com/icoxfog417/awesome-text-summarization

