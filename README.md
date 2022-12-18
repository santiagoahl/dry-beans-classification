<h1 align="center">
  <br>

  <br>
Dry Beans Classification
  <br>
</h1>

<h4 align="center">Machine Learning model to classify a bean class from its data. 
</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://numpy.org/' target="_blank"><img alt='numpy' src='https://img.shields.io/badge/Numpy-100000?style=for-the-badge&logo=numpy&logoColor=0250BD&labelColor=8BBFEA&color=B1DCFF'/></a>  <a href='https://pandas.pydata.org/' target="_blank"><img alt='pandas' src='https://img.shields.io/badge/pandas-100000?style=for-the-badge&logo=pandas&logoColor=2D0090&labelColor=9D7BEA&color=D2C0FA'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a> 
</p>

![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F3fdfeb20-0c08-4413-8f32-0ee24af9b5e7%2FUntitled.png?id=a5de4fca-45cd-4834-a264-e611d5c6017f&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=1590&userId=&cache=v2)

## Key Features

This machine learning model clusters a set of costumers from its personal data. This prediction is one of 3 clusters. The dataset is taken from the [Dry Bean Dataset](https://www.kaggle.com/datasets/sansuthi/dry-bean-dataset/download?datasetVersionNumber=1). So here are the key features of this project:

* Prediction is based on these beans attributes

	* `Area` (A): The area of a bean zone and the number of pixels within its boundaries.
	* `Perimeter` (P): Bean circumference is defined as the length of its border.
	* `Major axis length` (L): The distance between the ends of the longest line that can be drawn from a bean.
	* `Minor axis length` (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
	* `Aspect ratio` (K): Defines the relationship between L and l.
	* `Eccentricity` (Ec): Eccentricity of the ellipse having the same moments as the region.
	* `Convex area` (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
	* `Equivalent diameter` (Ed): The diameter of a circle having the same area as a bean seed area.
	* `Extent` (Ex): The ratio of the pixels in the bounding box to the bean area.
	* `Solidity` (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
	* `Roundness` (R): Calculated with the following formula: (4piA)/(P^2)
	* `Compactness` (CO): Measures the roundness of an object: Ed/L
	* `ShapeFactor1` (SF1)
	* `ShapeFactor2` (SF2)
	* `ShapeFactor3` (SF3)
	* `ShapeFactor4` (SF4)
	* `Class` (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira)

* The target feature is `Class`, which tells us which class does the bean belong to.

* Data balancing with **SMOTE**.
* Based on **Scikit-Learn** modules and functions such like:
  - `model_selection.GridSearchCV`: Dimensionality reduction.
  -  `linear_model.LogisticRegression` : Machine model classifier

* We've gotten a **91.9%** of `f1_score`.
* The confusion matrix is the following:
![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F8c1c5076-9c0f-44e9-9b9d-48421a046a94%2FUntitled.png?id=6afff152-686a-460d-bf9d-da9d168a6151&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=730&userId=&cache=v2)
## How To Use

To clone and run this application, follow these steps

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/dry-beans-classification.git

# Go into the repository
$ cd dry-beans-classification

```

## Credits
This software uses the following open libraries and datasets:


- [Numpy](http://electron.atom.io/)
- [Matplotlib](https://nodejs.org/)
- [Seaborn](https://github.com/chjj/marked)
- [Pandas](http://showdownjs.github.io/showdown/)
- [Sci-kit Learn](http://codemirror.net/)
- [Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
