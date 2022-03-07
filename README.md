# `CMPSC 302` Web Development, Week 1: Basic HTML (Lab)

* Assigned: 7 March 2022, 1:30 PM
* Due: 13 March 2022, 11:59 PM

## HTML with _style_

Today we begin our journey into learning CSS styling, namely around basic selectors, inline versus block elements, 
the basic rule of the "box model" and how go about implementing our style using an external file known as a `CSS stylesheet`.

If you were waiting to break free from Times New Roman on a white background, this is your time to shine.

This week's exercises have a few different prerogatives to follow, namely that CSS thrives on interoperability and reuse. 
Putting this principle into action will require some level of modification of the recipe _you found_ as you will see in 
the requirements below. There's much more to think about as pertains CSS than we can cover in a few class sessions, so 
we'll continue this work well into next week. But, by Spring Break, you'll be at least an intermediate HTML/CSS user.

(Yes, you can walk around saying you're a PRO. I won't correct you.)

### Requirements

#### `docs/lorem-ipsum.html`

* Use at least `2` `<strong>` and `<em>` tags

#### `docs/lorem-style.css`

The `lorem-style.css` file must style the following `tag`s _at a minimum_:

* `html`
* `body`
* `h1`
* `a`
  * including the new idea of "pseduo-class": `hover`, `visited`
* `div`
* `p`

#### `docs/recipe-style.css`

The `recipe-style.css` file must both style the following `tag`s, `id`, and `classes`, _and_ be interoperable with 
the recipe you found and added during last week's work. This _will mean_ "refactoring" (that is, revising) your 
work to _at a minumum_ use the styling in the included stylesheet. You can, of course, go beyond that.

`tag`s to style:

* `html`
* `section`
* `h1`, `footer`
  * You will need to add a `<footer>` element to _your recipe_ (`1-recipe.html`), likely
* `ul`
* `a`
  * including "psuedo-class": `hover`, `visited`

`id`s and `class`es:

* `container` (`id`)
* `detail-label` (`class`)
* `detail-text` (`class`)

Don't forget that this sheet should show up in the `<head>` of the `1-recipe.html` file!

## Making a GitHub Pages page

This assignment also requires you to make your work available via GitHub Pages. For a primer on where to find it
and how to do it:

- [ ] locate and click the `Settings` tab at the top of the screen
- [ ] from the menu at the left, select `Pages`
- [ ] locate the "Source" heading; set the "Branch" as `main`, and change the second drop-down to `/docs`
- [ ] click `Save`
- [ ] One last step: make the page _public_ by setting `GitHub Pages visibility` to `Public`
  * This step is _required_ for your HTML and CSS to pass validation!
A green box will appear at the top of the page listing the random URL that you've been assigned. This is your
URL!

## Accepting the assignment

- [ ] Using either the link posted to our class Discord or the [course schedule](https://cmpsc302.chompe.rs)
- [ ] Click the link provided for the lab assignment and accept it in GitHub classroom
- [ ] Once the assignment finishes building, click the link to go to your personal repository assignment

## "Cloning" a repository

### Using the correct download link

- [ ] On this repository's page, click the `Clone or download` button in the upper right hand corner
* You may need to scroll up to see it
- [ ] In the upper right corner of the box that appears, click `Use SSH`
- [ ] Copy the link that appears in the textbox below the phrase "Use a password with a protected key."

#### Cloning

* [ ] Type `ls` in your terminal window
* You should be in your `~` directory
- [ ] Find the folder you've made to hold class assignments (may involve `cd`ing)
- [ ] Once there, "clone" the repository using the link copied above
  * If I (the instructor) were to clone my own repository, I'd enter (your link will look different):

```
git clone git@github.com:Allegheny-ComputerScience-302-S2022/cmpsc-302-week-2-basic-style-exercises.git
```

## Wrap-up

### Submitting the assignment/saving progress

The GitHub platform is a place to store your work. So, it makes some sense that should be able to _clone_ (download) from it, and push back (upload) to it. Here, we'll learn this second part.

- [ ] `cd` to your `~` folder
- [ ] Locate your `cmpsc-302-week-2-basic-style-exercises` folder and `cd` to it.

Once in this folder, we need to tell git that there have been changes.

- [ ] Type `git add -A` and press `Enter`
* This tells git to look through the _entire_ folder structure for new changes and "stage" them

- [ ] Type `git commit -m "YOUR COMMIT MESSAGE"` to "label" the commit
* This is typically something like `git commit -m "Fixing a typo"` -- the message in quotes should be as descriptive as possible, while still remaining somewhat short

- [ ] To send all changes to the server, type `git push`
- [ ] At the prompt, input the password associated with the `SSH Key` you created earlier in this exercise (yesterday)

Once the process finishes successfully, we're done!
