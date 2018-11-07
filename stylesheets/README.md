# Variation of 7-1 Sass Boilerplate (this one apply shame file and bootstrap custom)

This is a sample project using the [7-1 architecture pattern](http://sass-guidelin.es/#architecture) and sticking to [Sass Guidelines](http://sass-guidelin.es) writing conventions.

Each folder of this project has its own `README.md` file to explain the purpose and add extra information. Be sure to browse the repository to see how it works.


# Main file

The main file (usually labelled `main.scss`) should be the only Sass file from the whole code base not to begin with an underscore. This file should not contain anything but `@import` and comments.

Reference: [Sass Guidelines](http://sass-guidelin.es/) > [Architecture](http://sass-guidelin.es/#architecture) > [Main file](http://sass-guidelin.es/#main-file)

# Shame file

There is an interesting concept that has been made popular by Harry Roberts, Dave Rupert and Chris Coyier that consists of putting all the CSS declarations, hacks and things we are not proud of in a shame file. This file, dramatically titled _shame.scss, would be imported after any other file, at the very end of the stylesheet.

Reference: [Sass Guidelines](http://sass-guidelin.es/) > [Architecture](http://sass-guidelin.es/#architecture) > [Shame file](http://sass-guidelin.es/#shame-file)

## Bootstrap file

This boilerplate does provide a option to custom bootstrap directly from  `custom_bootstrap.scss` variables file.

Reference: [Bootstrap Docs](https://getbootstrap.com/docs/4.1/getting-started/introduction/) > [Theming](https://getbootstrap.com/docs/4.1/getting-started/theming) > [Boostrap file](https://getbootstrap.com/docs/4.1/getting-started/theming/#importing)