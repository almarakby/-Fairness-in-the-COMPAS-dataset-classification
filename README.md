# Investigating the fairness in the COMPAS dataset classifications

This project is revisiting the famous COMPAS dataset by performing data exploration and analysis on the samples to investigate the bias of the produced compas scores towards certain underlying groups (namely race and gender). Moreover Different classifier are trained on to the ground truth scores and their performance compared with the compas scores for different groups. Furthermore, we visit the definition of fairness in machine learning and investigate the scores of compas with respect to the different groups, and after, we utilize a method for calibrating the scores of the classifiers that perturbe the labels so that it produces a more fair predictions (with respect to our definition of fairness). Finally we define metrics to assess the performance of the fairness method used and we compute its performance

### Dependecies

Packages used in the project

* numpy
* pandas
* matplotlib
* plotly
* sklearn
* pprint
* aif360 IBM fairness in machine learning package
* jupyter notebook

### Installing
* To install and run the project, the above mentioned dependencies must be installed and visible to the project path.


* The project is self-contained in a jupyter notebook to better show the analysis and the visualization on the dataset.


## Authors

* **Mohammed Almarakby** 
* **Eslam Mohammed**


<!-- ## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc 
-->
