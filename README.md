# Eversnippets Collection

Just some peace of code that helps us in work.

## Setup

### For osX:

    git clone git@github.com:EvercodeLab/sublime2-snippets.git \
        ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/EvercodeSnippetPack

### For Linux:

    git clone git@github.com:EvercodeLab/sublime2-snippets.git \ 
        ~/.config/sublime-text-2/Packages/EvercodeSnippetPack

## HTML (Rails)
* `<%`=>      `<% %>`
* `erb`=>     `<%= %>` seems wierd at first, but is easy to type with just left hand
* `if`=>      if-end  
* `ife`=>     if-else-end
* `case`=>    case-when-when-end
* `when`=>    when
* `each`=>    object-each-do-end
* `tap`=>     object-tap-do-end
* `try`=>     object-try-do-end
* `formfor`=> form-for
* `imgtag`=>  image-tag
* `linkto`=>  link-to

## JavaScript
* `docready`: Document ready function which is common in jQuery practice
* `console`: console.log() function — help debug JavaScript
* `anonimus-function`: anonimus function 
* `on`: document-on function, 'click' by default

## RSpec
* `itsrt`=> it-should-respond-to
* `itsbt`=> it-should-belong-to
* `itshm`=> it-should-have-many
* `itshabtm`=> it-should-have-and-belong-to-many
* `its`=> its-property-should

## Ruby on Rails
* `match`=> match-path-action
* `get`=> get-path
* `post`=> post-path
* `res`=> resources
* `ro`=> resources-only
* `re`=> resources-except

## Symfony 2 snippets

### Controller
* `sf-action-with-annotation`: action annotated with @Route and @Template
* `sf-controller-with-annotation`: controller with annotations
* `sf-em`: getting Entity Manager in Controller
* `sf-get-repository`: getting repository with Entity manager
* `sf-get-user-from-security-context`: get User information from security.context
* `sf-redirect`: redirect

### Doctrine
* `sf-entity-class`: generates entity class
* `sf-orm-column`: generates ORM column defenition
* `sf-orm-column-with-set-and-get`: generates ORM column defenition with setter
and getter
* `sf-repository-class`: generates entity repository class
* `sf-query-builder`: generate query builder

### Form
* `sf-form-type`: creates form type class
* `sf-cnoice-list-class`: creates choice list class

### Twig
For basic Twig functions use [PHP Twig][1]. It provide next snippets:
* `}}`: `{{  }}`
* `%%`: `{%  %}`
* `block`: `{% block name %}{% endblock %}`
* `blockb`: block with blank line
* `else`: `{% else %}`
* `extends`: `{% extends 'template' %}`
* `filter`: `{% filter name %}{% endfilter %}`
* `filterb`: filter with blank line
* `for`: `{% for item in seq %}`
* `fore`: for with else
* `if`: `{% if condition %}{% endif %}`
* `ifb`: same as `if` but with blank line
* `ife`: same as `if` but with else statement
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

## Other
* `snippet`: just for generation of other snippets

More to come. Stay tuned.

[1]: https://github.com/Anomareh/PHP-Twig.tmbundle "PHP Twig"