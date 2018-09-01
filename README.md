# Python-Flask-Checkerboard
Using flask to create a custom-sized checkerboard

Install flask using pip in your terminal (pip install Flask) 

Install/Run a virtual environment
https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/

In the root folder of this project, in your terminal, run "python server.py"

Navigate to localhost:5000

Your custom url will show the size of the checkerboard you wish to see, the default size is 8x8.

Example: http://localhost:5000/10/10 will bring up a 10x10 checkerboard

CSS Note: this was built utilizing CSS Grid via grid-template-rows and grid-template-columns with dynamic inputs.

Side note: it is best to use identical dimensions, otherwise the board may not replicate the way you want.  If you want to have some fun, "break" it by putting in odd numbers like http://localhost:5000/11/11.
