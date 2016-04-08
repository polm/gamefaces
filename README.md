# Gameface

This is a collection of square headshots extracted from the [Internet Archive Book Images Flickr Stream](https://www.flickr.com/photos/internetarchivebookimages/). Face positions were extracted using the [Google Cloud Vision API](https://cloud.google.com/vision/).

# Overview

These images have been shrunk and combined with gutters; this gives an overview of what to expect from most of the collection.

![overview1](https://img.itch.io/aW1hZ2UvNjA2NTYvMjczNjkzLmpwZw==/original/06eniI.jpg)
![overview2](https://img.itch.io/aW1hZ2UvNjA2NTYvMjczNjg0LmpwZw==/original/SMfSGi.jpg)

# Samples

These are actual images in the repository at their natural size.

![sample 1](https://github.com/polm/gamefaces/blob/master/faces/14576363307.face.jpg)
![sample 2](https://github.com/polm/gamefaces/blob/master/faces/14598343660.face.jpg)
![sample 3](https://github.com/polm/gamefaces/blob/master/faces/14598420890.face.jpg)
![sample 4](https://github.com/polm/gamefaces/blob/master/faces/14781908461.face.jpg)

# Notes and limitations

- All images are 300px square JPEGs; some were upscaled from the original
- Filenames are Flickr Image IDs
- Sometimes image quality is not great; you'll probably want to pre-process them before use in a game
- No gender information is available
- Due to the nature of the corpus, most photos are of 19th century white men
- Only the first face detected in each picture was used
- Most pictures are photos, but occasionally illustrations or non-faces show up

If you know of a public domain resource or face recognition system that can address any of these points please be in touch.

# License

The Internet Archive books are presumed to be in the Public Domain, and the simple transformation here hopefully doesn't change that.

Any original work here is under the WTFPL, do as you please. 

-POLM
