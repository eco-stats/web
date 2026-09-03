# UNSW Eco-Stats Research Group Website

This is the repo for the website of the Eco-Stats Research group at UNSW. It is modified on top of a Jekyll template developed by the Allan Lab and used by the Coley Lab at MIT.

### Adding you or someone else to the "People" page

Adding yourself to the People page is very simple!
1. Upload an image of yourself to `images/teampic/` with the format `{firstname}_{lastname}.[png|jpg|jpeg]`. **Please crop your image to a square**.
2. Navigate to the `_data/` folder and locate the `.yml` file that matches your position in the group (for instance, if you are a grad student, open `grad_students.yml`). 
3. Add all relevant information in the `.yml` file. 
    - Fill out `name` and `email` at minimum, with optional URLs provided in `twitter`, `linkedin`, and/or `website` fields.
    - Add a short biography for the `description` field.

That's it! Go ahead and make a pull request when you are satisfied.

### Other changes

The following have been set up to be similarly easy to add new content to. Hopefully it should be simple to extrapolate the editing of `.yml` files to the following, but ask Kevin or Kento if you need help.
- News (`_data/news.yml`)
- Group photos (`_data/photos.yml`, images go in `images/grouppic/`)
- Open source software (`_data/software.yml`, logos go in `images/logopic`)
- Research relevant to Connor's directions on the "Research" page (`_data/research.yml`)
- WIP: The carousel highlighting recent work still needs to be refactored to be easily editable with `.yml` files. For now, they are manually declared in `_includes/carousel.html` with pictures in `image/carouselpic`)
