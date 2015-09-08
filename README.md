# Surfer-competition
General information:
--------------------
This repository contains the localisation for the Surfer competition website. 
The main language is english and can be found in the direcotry en. It contains 3 html files that need to be translated: Imaginary.html, Imaginary_gallery.html and Imaginary_gallery_upload.html.

Creating a new localisation:
----------------------------
Create a fork of the repository:

Then checkout a new branch, e.g. for a french translation

```git checkout -b fr-translation```

Create a new directory with the translations, e.g. and copy the html files into the directory
```
mkdir fr
cp en/*html fr/
```

Then prepare your translation in French, remembering to use UTF-8 fileformat.
add and commit your changes:
```
git status
git add fr
git commit -m '[fr] creating French translation
```
Now you can create a pull request with the IMAGINARY repository and merge the changes into it. 

Lastly, add your name in the AUTHORS file, so that it can be tracked who did certain translations.
