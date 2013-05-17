# Website template

This Jekyll site template was created by [Victor Chahuneau](http://victor.chahuneau.fr) for the [cdec website](http://github.com/cdec/cdec.github.com).

It has since been used by [several](http://www.cs.cmu.edu/~cdyer/) [other](http:/www.cs.cmu.edu/~nasmith/) [people](http://filebox.ece.vt.edu/~dbatra/index.html).

If you want to use this template for your own website, you are free to modify it under the conditions of the [CC BY](http://creativecommons.org/licenses/by/3.0/) license.

## Instructions

- Modify some files
- Run `jekyll server` to preview your website
- Run `jekyll build` to update your static site
- Once done, copy the contents of the `_site` folder to your website

Read the [Jekyll documentation](http://jekyllrb.com/docs/home/) for more details.

### File structure
- `_config.yml` : Jekyll [configuration](http://jekyllrb.com/docs/configuration/)
- `_layouts/`
	-  `default.html` : default template
- `_includes/`
	- `header.html`, `footer.html` : header and footer used by the default template
- `style.css`: CSS stylesheet
- `index.md` : main page
- `publications.md`, `software.md`, `stuff.md` : example additional pages

The pages must specify a template (default) and a title, and can be written in [Markdown](http://daringfireball.net/projects/markdown/), HTML or a mixture of these.