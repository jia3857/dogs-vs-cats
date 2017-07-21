
Dogs vs Cats
============
* problem: https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
* dataset: https://www.kaggle.com/c/dogs-vs-cats/data
* workflow:
** [[classifier_from_little_data_script_1.py][https://gist.github.com/fchollet/0830affa1f7f19fd47b06d4cf89ed44d]]
** [[classifier_from_little_data_script_2.py][https://gist.github.com/fchollet/f35fbc80e066a49d65f1688a7e99f069]]
* results:
** classifier_from_little_data_script_1.py

Training a small convnet from scratch: 80% accuracy in 40 lines of code
This approach gets us to a validation accuracy of 0.79-0.81 after 50 epochs

** classifier_from_little_data_script_2.py

Using the bottleneck features of a pre-trained network: 90% accuracy in a minute