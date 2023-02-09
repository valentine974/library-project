
# THE BUG-US

### A library project
*by Valentine & Shengwei*

![about us](/public/images/about us.jpg)

## Principal fonctionalities

### HOME PAGE with top picks and top rated books

* Top picked : the most added to shelf books by our users
* Top rated: books on our users' shelfs with the best google average ratings
* **Nice feature**: running title to prevent multi-lines wraped title
![Home page](/public/images/home page.jpg)

### SIGN UP/LOG IN 

Basic sign up page with username, email and protected password
Possibility to add your own profile image here, or add it latter in my profile page once logged in. 
If no photo is provided on sign up, a random site photo is given. 
![sign up page](/public/images/sign-up.jpg)

Log in fonctionality with isLoggedIn middleware 

isLoggedIn activates: 
* My profile page
* Add to shelf button
* Comment section on book detail page
![Log in page](/public/images/log-in.jpg)
### BOOK details page

Basic book informations like title, authors, descriptions...
**Extra feature**: 
Bug-us recommandation: a few similars books based on book title generated by openai. 
![book details without log in](/public/images/detail-no-log-in.jpg)

![book details onece logged in](/public/images/detail-logged-in.jpg)

