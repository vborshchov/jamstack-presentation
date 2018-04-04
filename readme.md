### You might not need

WORDPRESS
=========

Victor Borshchov, [Triare](https://triare.net/)

Topics
------

*   Headless CMS

  *   What
  *   Why
  *   Demo

*   Git-based CMS

  *   What
  *   Why
  *   When do not use
  *   Demo

### Headless CMS

#### Into

'Headless CMS' is also commonly known as 'JAMstack CMS' or 'Decoupled CMS'

> JAMstack: noun \\’jam-stak’\
>
> Modern web development architecture based on client-side JavaScript, reusable APIs, and prebuilt Markup.

#### What

Your project is built with the JAMstack if it meets three key criteria:

*   JavaScript
*   APIs
*   Markup

Why
---

*   Better Performance
*   Cheaper, Easier Scaling
*   Higher Security
*   Better Developer Experience
*   The best solution if you have several different apps or sites pulling the same managed content

### When is your site NOT built with the JAMstack?

*   A site built with a server-side CMS like WordPress, Drupal, Joomla, or Squarespace.
*   A single page app that uses isomorphic rendering to build views on the server at runtime.
*   A monolithic server-run web app that relies on Ruby, Node, or another backend language.

Demo time
---------

[Storyblok](http://storyblok-headless-cms.herokuapp.com/)

[Contentful](http://contentful-headless-cms.herokuapp.com/)

### Git-based CMS

#### What

With a git-based CMS you are pushing changes to git that then triggers a new build of your site.

Why Git-based CMS
-----------------

*   Full version control on all content out of the box.
*   All content lives as normal text files so developers can use all the normal tools they use as a developer.
*   Much easier to rollback.
*   Is the most homogenous approach with the existing git-based workflow of most web-developers.

### When do not use Git-based CMS

*   Not a good solution if you want several apps or sites to pull content from the same CMS.
*   If you have tons of content, you would in some cases want a database instead.

Demo time
---------

[Github pages](https://vborshchov.github.io/forestry-demo/)
