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
* `<%`=>      `<%= %>`
* `if`=>      if-end  
* `ife`=>     if-else-end
* `case`=>    case-when-when-end
* `when`=>    when
* `each`=>    object-each-do-end
* `tap`=>     object-tap-do-end
* `try`=>     object-try-do-end
* `erbform`=> form-for
* `erbimg`=>  image-tag
* `erblink`=> link-to
* `:`=>       key-value

## JavaScript
* `docready`: Document ready function which is common in jQuery practice
* `console`: console.log() function — help debug JavaScript
* `anonimus-function`: anonimus function 

## RSpec
* `itsrt`=> it-should-respond-to
* `itsbt`=> it-should-belong-to
* `itshm`=> it-should-have-many
* `itshabtm`=> it-should-have-and-belong-to-many
* `its`=> its-property-should

## Ruby on Rails
* `match`=> match-path-action
* `res`=> resources
* `reso`=> resources-only
* `rese`=> resources-except
* `:`=> key-value ~>1.9 (the old one is at `Ruby/hash-pair`)

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

## Other
* `snippet`: just for generation of other snippets

More to come. Stay tuned.
