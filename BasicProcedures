# Histograms and Boxplots

################################

# 1) Histograms

# Practice Code Here

hist(iris$Sepal.Length)

hist(iris$Sepal.Length, col=c("red","blue","yellow","green")) 

###############################

# 2) Boxplots

fivenum(iris$Sepal.Length)

boxplot(iris$Sepal.Length)

#Change the orientation from vertical to horizontal
boxplot(iris$Sepal.Length, horizontal = TRUE)

boxplot(Sepal.Length ~ Species, data = iris)

###############################

# 2b) Using boxplots for comparison by category

 #Recall that the Iris data contain measurements for three different specied of iris; virginica, setosa and versicolor.

 # Suppose we wish to compare the respective categories in terms of one of the variables.
 # We can divide the dataset into the three subgroups, and constructing a boxplot for each. 
 # The subgroups are aligned along the same scale so as to allow for convenient visual inspection.

attach(iris)
boxplot(Petal.Length ~ Species, horizontal = TRUE)

###############################
