# Wow Sublime 2 and 3 Snippets Collection

Includes snippets for: Ruby, Ruby on Rails, ERB, RSpec, Javascript, PHP, Symfony2, Doctrine2, Twig.
Forked from [snippets pack by EvercodeLab][5]

## Setup

#### For OS X:

ST2

    git clone git@github.com:dmishh/wow-sublime-snippets.git \
        ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/WowSnippetsPack

ST3

    git clone git@github.com:dmishh/wow-sublime-snippets.git \
        ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/WowSnippetsPack


#### For Linux:

    git clone git@github.com:dmishh/wow-sublime-snippets.git \
        ~/.config/sublime-text-2/Packages/WowSnippetsPack

## Ruby
* `u8`: \# encoding = utf-8

## Ruby on Rails
* `match`: match-path-action
* `get`: get-path
* `post`: post-path
* `res`: resources
* `ro`: resources-only
* `re`: resources-except

## ERB
* `<%`: `<% %>`
* `erb`: `<%= %>` seems wierd at first, but is easy to type with just left hand
* `if`: if-end
* `ife`: if-else-end
* `case`: case-when-when-end
* `when`: when
* `each`: object-each-do-end
* `tap`: object-tap-do-end
* `try`: object-try-do-end
* `formfor`: form-for
* `fi`: form input
* `imgtag`: image-tag
* `linkto`: link-to
* `optforsel`: options for select
* `optfrom`: options from collection for select
* `render`: render partial
* `selecttag`: select tag
* `simplefields`: simple fields for form
* `simpleform`: simple form with fields

## RSpec
* `itsrt`: it-should-respond-to
* `itsbt`: it-should-belong-to
* `itshm`: it-should-have-many
* `itshabtm`: it-should-have-and-belong-to-many
* `its`: its-property-should

## JavaScript
* `docready`: jQuery [document ready][2] function
* `console`: console.log() function — help debug JavaScript
* `anonymous-function`: anonymous function
* `on`: jQuery [`on`][3]function, 'click' by default

## Symfony 2 snippets

### Controller
* `sf-crud-controller`: generate whole CRUD controller
* `sf-controller-with-annotation`: controller with annotations
* `sf-action-with-annotation`: action annotated with @Route and @Template
* `sf-em`: getting Entity Manager in Controller
* `sf-get-repository`: getting repository with Entity manager
* `sf-get-user-from-security-context`: get User information from security.context
* `sf-redirect`: redirect
* `sf-flash`: flash message
* `sf-403`: throwing 403 exception
* `sf-404`: throwing 404 exception

### Doctrine
* `sf-entity-class`: generates entity class
* `sf-orm-column`: generates ORM column defenition
* `sf-orm-column-with-set-and-get`: generates ORM column defenition with setter
and getter
* `sf-repository-class`: generates entity repository class
* `sf-query-builder`: generate query builder
* `sf-setter-and-getter`: setter and getter methods
* `sf-setter`: settere
* `sf-getter`: getter

### Form
* `sf-form-type`: creates form type class
* `sf-cnoice-list-class`: creates choice list class

### Twig
For basic Twig functions use [PHP Twig][4]. It provide next snippets:

* `}}`: `{{  }}`
* `%%`: `{%  %}`
* `block`: `{% block name %}{% endblock %}`
* `blockb`: block with blank line
* `extends`: `{% extends 'template' %}`
* `filter`: `{% filter name %}{% endfilter %}`
* `filterb`: filter with blank line
* `for`: `{% for item in seq %}`
* `fore`: for with else
* `if`: `{% if condition %}{% endif %}`
* `ifb`: same as `if` but with blank line
* `ife`: same as `if` but with else statement
* `else`: `{% else %}`
* `set`: `{% set var = value %}`
* `setb`: same as `set` but in other syntax

And here some more Twig snippets:

* `twig-path`: path function
* `twig-include`: include other template
* `twig-render`: render other template
* `twig-spaceless`: render peace of templte without spaces

### SonataAdmin
* `sf-sonata-admin-class`: creates SonataAdmin class

### Config
* `sf-service`: yml service defenition
* `sf-service-admin`: yml admin service defenition

## PHP
* `class`: just PHP class
* `php`: PHP open tag
* `pubf`: public function
* `pubsf`: public static function
* `privf`: private function
* `protf`: protected function

## Other
* `snippet`: just for generation of other snippets

[1]: https://sublime.wbond.net/installation "Package Control"
[2]: http://api.jquery.com/ready/ "ready function"
[3]: http://api.jquery.com/on/ "on function"
[4]: https://github.com/Anomareh/PHP-Twig.tmbundle "PHP Twig"
[5]: https://github.com/EvercodeLab/evercodelab-sublime-snippets "Orignal snippets pack by EvercodeLab"