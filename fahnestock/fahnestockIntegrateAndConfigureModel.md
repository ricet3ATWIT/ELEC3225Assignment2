# Integrate and Configure
![integrateAndConfigureDiagram](img/integrateAndConfigureDiagram.png)

Through using the [Django Web Framework](https://www.djangoproject.com/) several of the steps of this project can be combined, and the timeline can be reduced. Similarly to the other two process models the interface should be the starting point. Django utilizes an ORM so the both the database work and class work are combined into one step. This enables a single source of truth for the structure of the application. Django calls these structures models, and their written as Python classes. Any change to a model can be applied to the database using migrations. These migrations are stored and act as the databases version control. These models can be queried, and mutated with the Model API. Most of the UI would be written using Django's Forms which can be rendered as HTML and manipulate/display the models. Along with this Django comes with a built in admin panel to control user accounts and authentication. Most of the testing would be done with unittest a module built into the Python standard library. Other than some date/time packages not much else would be needed for this project. 


