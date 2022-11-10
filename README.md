# 01-Laravel-crud-app

This web application is made in Laravel. MySQL is used as the database, and the materialize framework is used for the layout of the pages. This application enables the creation of post content, i.e. Create, Read, Update, Delete. At the bottom of the page, the last three postings are displayed. Flash messages are obtained for CRUD operations. The active menu is highlighted. Error object, validation, name routes, fillable property, type hinting, route model binding...

- Type hinting means providing type hints to function to only accept the given data type.  public function update(Post $post)
- Laravel route model binding provides a convenient way to automatically inject the model instances directly into your routes.
- Named routes allow referring to routes when generating redirects or Urls more comfortably.
- Helper function helps us to create a function that can be called anywhere in our app  Providers/hellpers.php
- If we want to place global variables, we do it in the Service Provider. Go to the app/Providers/AppServiceProvider.php and in boot()method and then we set a specific  method that we store in a global variable.


![1](https://user-images.githubusercontent.com/56784702/201114132-35a5cafe-1f35-4000-b5f9-dcc8eae886aa.png)
![2](https://user-images.githubusercontent.com/56784702/201114139-8ca9796a-a278-4417-bf8e-9d48f0db9293.png)
![3](https://user-images.githubusercontent.com/56784702/201114144-23821309-1134-4df1-afdc-3d8275356a6f.png)
![4](https://user-images.githubusercontent.com/56784702/201114145-b8cc84cd-7fe3-4b53-8ad8-dca2cd558ccc.png)
![5](https://user-images.githubusercontent.com/56784702/201114154-b1705167-4129-4127-9b98-ad6e34052d1f.png)
