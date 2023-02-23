ML operations and materials in class
Hidden technical debts in ML systems:-Configuration, servicing infrastruture, data collection, data verification, feature extraction, analysis tools, monitoring, process management tools and machine resource management
if you have a lot of data movement and huge amounts of data to store, you can look to build data lakes using AWS S3 and AWS Glue
https://towardsdatascience.com/what-is-mlops-everything-you-must-know-to-get-started-523f2d0b8bd8
Training---testing---building pipeline---distribution/tid
artifactory--- 
publishing of a model means--publish ur model publically as a package by a python
tensor flow is a public indexed
private index--- oly the user have that in private
tit regression model 
jupyter notebook---repository--model packages are created in git hub---requirement of txt file---then config.yml file---utility funcyion---core py which will read my config file---feature.py read from config file---pipeline---training file---paths of file---validate the dtaa---validation.py----try and catch---raise the exception if any--train & test---fit into model---retrive the data---packaging---everything should be integrated into main file 

risk evaluation for sending into production?
model impact to end user?
avoid pipeleine breaking
whenever  a new dtaa comes we need aa automation tool , so a cicd pipeline needed so we wrote the steps in yml file
automate the model publishing+

neptune.ai for NLP Projects
