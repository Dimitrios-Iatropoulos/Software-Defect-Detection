# Software-Defect-Detection

## Project Overview
This project applies machine learning models to automatically identify defects in software, utilizing a range of classifiers and datasets to assess their performance in software defect detection tasks. It was developed in collaboration with Panagiotis Ioannou.

## Classifiers 

- Logistic Regression

- Perceptron

- Support Vector Machines (linear & RBF kernel)

- Decision Tree

- Random Forests

- Feed-forward Neural Network

## Datasets
- **jm1**: Extracted from [OpenMl](https://www.openml.org/search?type=data&status=active&id=1053&sort=runs)
- **mc1**: Extracted from [OpenMl](https://www.openml.org/search?type=data&status=active&id=1056&sort=runs)
- **pc3**: Extracted from [OpenMl](https://www.openml.org/search?type=data&status=active&id=1050&sort=runs)

  

## Experiments and Evaluation
- Experiments involve training on 80% of the data and testing on 20%, employing 5-fold cross-validation. 
- Performance metrics include Accuracy, F1-score, G-Mean score, and Fit time 
- Three different normalization methods (No normalization, Min-max normalization, Feature Standardization).

## Results
The notebook presents all analyses and visualizations, including bar plots comparing the performance of classifiers across normalization methods, are presented along with a discussion on which model is the most effective in detecting software defects.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Feedback
Your thoughts and feedback are welcome! Please feel free to open an issue or contact me directly at jimiatro@hotmail.com.
