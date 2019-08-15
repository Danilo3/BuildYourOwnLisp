Build your own Lisp
===================

Original: http://buildyourownlisp.com

Russian Translation: http://danilo.pythonanywhere.com/ (Choose Russian in left bottom corner)

About
-----
This is a fork of great and popular book from Daniel Holden. The aim of project - translate all book to Russian Language.


This is the HTML and website code for the book of the above title.

Corrections / Edits / Contributions Welcome

`contact@theorangeduck.com`

Licensed under Creative Commons Attribution-NonCommercial-ShareAlike 3.0

http://creativecommons.org/licenses/by-nc-sa/3.0/


Running
-------

You can't just browse the raw HTML files of the site. The links wont work, and it wont have a proper header or footer. If you want to run this website locally, you should install Flask and run the website as follows.

```
pip install Flask
pip install Flask-Mail
python lispy.py
```

You can specify port via `$PORT`.

```
env PORT=5000 python lispy.py
```

This will serve the site locally at `http://127.0.0.1:5000/`. You can browse it from there.
