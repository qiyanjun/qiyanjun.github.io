# About
This site is generated by [Jekyll](http://jekyllrb.com) + minimal-mistakes theme   + [PostTagging](https://www.jokecamp.com/blog/listing-jekyll-posts-by-tag/) .


# A list of easy steps to set up a project blog web using Jekyll GitPage

1. set up ruby: please follow the step from [steps](https://gist.github.com/mcls/3118518) for mac version

2. install jekyll
```sh
~ $ gem install jekyll
```

3. using the following page to setup minimal-mistakes theme 
[https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/#installing-the-theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/#installing-the-theme)

- and [layout](
https://mmistakes.github.io/minimal-mistakes/docs/layouts/)

4. now deploy it locally
```sh
~/web-name $ bundle install
~/web-name $ bundle exec jekyll serve
```
Now use your favorite browser to open http://localhost:4000

5. add year-month-date-name.md under '_posts' folder

6. push into your git-site, using the site's -> "setting" -> section "GitHub Pages" to setup and publish the web as GitPage

7. configure tags/ collections / archives according to
[https://mmistakes.github.io/minimal-mistakes/docs/collections/](https://mmistakes.github.io/minimal-mistakes/docs/collections/)

8. add more customized post tagging using codes from [here]([PostTagging](https://www.jokecamp.com/blog/listing-jekyll-posts-by-tag/)

9. add more interesting liquid programming using [Tips](https://gist.github.com/smutnyleszek/9803727)




# This starts from the 

### Minimal Mistakes remote theme starter

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
