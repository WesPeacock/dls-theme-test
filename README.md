# Modified just-the-docs jekyll theme for SIL Dictionary and Lexicography Services
Fork of University of British Columbia Library Research Comons theme, which in turn, is a fork of
Patrick Marsceill's [Just the Docs](https://github.com/pmarsceill/just-the-docs) jekyll theme. The files below were added or changed for the UBC Library Research Commons implementation.

- ` _layouts/default.html`. Modified to point to `footer_rc.html` file and to simplify behaviour of the "View in Github" footer link. Do not over-write when pulling changes from upstream. 
- ` _sass/color_schemes/rc.scss`. File added, change default link color to blue.
- ` assets/images/SILDLS-logo.png`. File added, SIL DLS logo.
- ` _includes/footer_rc.html` File added, sets copyright info in left side panel.
- ` _sass/custom/custom.scss` Modified, contains all RC-related css changes. Upstream file is blank so this should be preserved when pulling.

Instructions to create a new site are at <https://ubc-library-rc.github.io/rc-workshop-template/>
