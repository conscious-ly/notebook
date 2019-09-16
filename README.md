# notebook

This is the repo containing the notebook for the HCI project. It was originally generated with [Hugo](https://gohugo.io/) using the [Cupper](https://themes.gohugo.io/cupper-hugo-theme/) theme.

However, due to archaic restrictions on how we need to serve our notebook, we're now directly modifying the statically built site which can lead to some minor inconveniences here and there.

It's recommended you do all your work on a branch other than `master`

#### Adding a new page
1. Copy paste the `index.html` file, make sure to rename it
2. Modify the name in the `<link rel="canonical" href="index.html">` to what you renamed it to 
3. Strip your new page of it's contents in the `<main>` tag.
4. Update the menu in all your other `html` files and add the newly created page

#### Modifying content
The majority of the content is in the `<main>` tag in the html files

#### Saving your work
`git add . && git commit -m "your message" && git push`
