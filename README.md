# Image-Classification-Spark-Scala
### Final Project Goal:- Use machine learning for foreground-background classification in high-resolution brain scans.

I decided to choose Random Forest Classification model to train our image data. 
Random Forest is an ensemble model where the trees are trained with bagging method. 

Here is the link to the detailed report of the Project [Click Here](https://drive.google.com/open?id=1pzJ6WToFNEMSfkWQdZI8SVCuw5nL-xTc)

Link to the source code [Click Here](https://github.com/Karan1909/Image-Classification-Spark-Scala/blob/master/SparkProject/src/main/java/newdriver/randomforest.scala)



### Steps to Use this code:- 
1. Clone the repository in your local file system 
2. Required IDE is Eclipse with Scala Nature. Scala Nature will be already added once you import the project as Maven Project 
3. Once the project is imported, remove any build or pom errors. Mostly they won't occur 
4. Finally, open the file randomforest.scala under src/main/java/newdriver folder to check the code 
5. Go to Run Configurations, we need to add RUN arguments. First arg- Input Folder location(Image pixel file) , Second arg-    PredictionOutput location, Third arg- Model save location 
6. Now we will click on apply and run. 
7. After successful run, the outputs will be added to the specified location as mentioned in args 

