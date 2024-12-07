# cs5830_final

## Files of Interest

Because this is a larger-scale project that required resources from multiple sources, files are distributed throughout the repository.

- Pre-Processing Files 
  - `final_project.ipynb` processes the images and stores their data in CSV files
  - `img_data_edges.csv` and `img_data_raw.csv` store processed image data for edge-detected and regular images, respectively
- Decision Tree
  - `decision_tree.ipynb` generates a selection of decision trees, including SVGs for each
  - `(regular|edge)_(d3|)_dt.png` is an image representation of the generated decision tree
- CNN
  - `do_cnn_models.py` does the training and testing for all the CNNs.
  - `output.txt` is the summary of CNN output
  - `(cnn)_confusion_matrix.png` is the confusion matrix for `cnn`
  - `(cnn)_plot_accuracy.png` plots the accuracy over the course of CNN training
  - `(cnn)_plot_train.png` plots the training loss over the course of CNN training
  - `(cnn)_plot_validation.png` plots the validation loss over the course of CNN training
