# Canberra Modern Theme

The basic bones of this theme have been created by Ben Ennis Butler as a starting point for students studying front-end web design (11056).

## Folder structure

`assets`: This folder is often used to store CSS, JavaScript, and images related to your theme.

`inc`: This folder can contain various PHP files, each handling specific functionalities. For example, custom-post-types.php might define custom post types, and theme-support.php might add theme support features.

`templates`: This is where your Twig templates reside. The `partials` subfolder can contain reusable components like headers, footers, and navigation.

`functions.php`: This file includes functions related to theme setup, enqueueing scripts and styles, and other theme-specific functionalities. You probably won't touch it.

`style.css`: A style.css file is needed for WordPress theme identification. When using Tailwind, the styles are automatically added to this, so no need to use it.


## Built upon
There are quite a few things in use in order to get this to work:

#### TailwindCSS v3.4.1
Tailwind is a utility-first CSS framework
[Tailwind Docs](https://tailwindcss.com/docs/)

#### Timber Starter Theme
The "_s" for Timber: a dead-simple theme that you can build from. The primary purpose of this theme is to provide a file structure rather than a framework for markup or styles. [Starter Theme](https://travis-ci.com/github/timber/starter-theme)

#### Twig
Timber uses Twig. Twig is a flexible and secure template engine for PHP used primarily in web development to separate the logic of the application from its presentation layer.
[Twig](https://twig.symfony.com/)


## Other Resources

* [Twig for Timber Cheatsheet](http://notlaura.com/the-twig-for-timber-cheatsheet/)
* [Timber and Twig Reignited My Love for WordPress](https://css-tricks.com/timber-and-twig-reignited-my-love-for-wordpress/) on CSS-Tricks
* [A real live Timber theme](https://github.com/laras126/yuling-theme).
