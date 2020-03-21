# Flask Data Visualization:

This is the code base for my PyCon Ireland 2019 presentation.

For more information and to view my PyCon IE presentation visit my [blog](http://allynh.com/blog/pycon-ie-2019/): 

## This project is a fork of Miguel Grinbergs Microblog project:
See bottom of README for details.

## How to run:

Set environment variables:

`set FLASK_APP=microblog.py`

`set FLASK_ENV=development`

Run command:

`flask run`

## View Finance charts:
Here are some example routes.

The development of these routes was discussed in my PyCon Ireland talk:

### Company 1:
http://127.0.0.1:5000/finance/1/2018

### Company 2:

http://127.0.0.1:5000/finance/2/2017


### To directly view the JSON response from an API request:

http://127.0.0.1:5000/api_1_0/get_finances/1/2018

## To view some chart examples:

All Victory Chart code within these routes was directly copied from: https://github.com/FormidableLabs/victory

http://127.0.0.1:5000/chart_examples


`.`

`.`

`.`

`.`


# Below follows oiginal README.md:

# Welcome to Microblog!

This is an example application featured in my [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). See the tutorial for instructions on how to work with it.
