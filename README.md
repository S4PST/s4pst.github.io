# Stewardship for Programming Systems and Tools

## What is this?

This is a repository that contains the files for the official Stewardship for Programming Systems and Tools project website hosted at [https://www.s4pst.org](https://www.s4pst.org). The site is built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub. 

## How do I contribute?

Fork the repository, make your proposed changes, test locally (see below), and then create a pull request against `main`. For more details about opening pull requests, issues and adding to our Newsletters, see our [Contributing Guide](.github/Contribute.md).


### How do I add to a newsletter (blog post)?

You can add to a newsletter to the site by modifying a markdown file in the [_posts](_posts) folder, organized by year. Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file.


### Previewing the Site

To preview the site locally, you'll need to [install jekyll](https://jekyllrb.com/docs/installation/)
It's then typical to go to the root of the site and issue (just once):

```bash
$ bundle install
```

And then (also in the top level directory of your forked repository) run 

```bash
$ jekyll serve
# or
$ bundle exec jekyll serve
```

and open your browser to <http://localhost:4000>.
If you are having trouble try `rm -rf _site`, followed by `bundle update`, then `bundle exec jekyll serve`.

## Credits

Website design: Kita Cranfill, Oak Ridge National Laboratory.
Maintainers: William F Godoy, Pedro Valero-Lara, Keita Teranishi, Kita Cranfill, Oak Ridge National Laboratory.

## Disclaimer

This manuscript has been authored by UT-Battelle, LLC under Contract No. DEAC05-00OR22725 with the U.S. Department of Energy. The United States Government retains and the publisher, by accepting the article for publication, acknowledges that the United States Government retains a nonexclusive, paid-up, irrevocable, worldwide license to publish or reproduce the published form
of this manuscript or allow others to do so, for United States Government purposes. The Department of Energy will provide public
access to these results of federally sponsored research in accordance with the DOE Public Access Plan [http://energy.gov/downloads/
doe-public-access-plan](http://energy.gov/downloads/doe-public-access-plan).
