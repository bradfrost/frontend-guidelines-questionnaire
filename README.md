# Frontend Guidelines Questionnaire
A one-page questionnaire to help your team establish effective frontend guidelines, so that you can write consistent & cohesive code together.

## HTML
### HTML Principles
- **What are some general principles your team should follow when writing HTML?** *(for example, authoring semantic HTML5 markup, accessibility, etc. See [these](http://www.yellowshoe.com.au/standards/#html) [resources](http://codeguide.co/#html) for [inspiration](http://manuals.gravitydept.com/code/html))*


### HTML Tools
- **Are you using an HTML preprocessor** *(such as [HAML](http://haml.info/), [Jade](http://jade-lang.com/), etc)*?
- **Are you using a templating engine** *(such as [Mustache](https://mustache.github.io/), [Handlebars](http://handlebarsjs.com/), etc)*?
- **Does your backend architecture influence the frontend markup in any way** (for example, WordPress will add `wp-paginate` to a class in your markup)? If so, can you highlight these conventions? 

### HTML Style
- **Spaces or Tabs?**
- **What does HTML commenting look like?** 

---------------

## CSS 

### CSS Principles
- **What are some general principles your team should follow when writing CSS?** *(For example, modularity, avoiding long selector strings, etc. See [these](http://cssguidelin.es/) [resources](http://www.yellowshoe.com.au/standards/#css) [for](http://manuals.gravitydept.com/code/css) [inspiration](http://codeguide.co/#css))*

### CSS Methodology
- **Is your team using a CSS methodology** *(such as [SMACSS](https://smacss.com/), [BEM](https://en.bem.info/method/), or [OOCSS](http://oocss.org/))*? If yes, where is the documentation for that methodology?
- **Are you deviating from the methodology in any way?** If so, can you highlight these conventions?

### CSS Tools
- **Is the team using a preprocessor** *(such as [Sass](http://sass-lang.com/) or [Less](http://lesscss.org/))*?
- **What are the guidelines for using that preprocessor** *(check out [Sass Guidelines](https://sass-guidelin.es/) for inspiration)*?
- **Are you using a CSS base** *(such as [Normalize](https://necolas.github.io/normalize.css/) or a [reset](http://meyerweb.com/eric/tools/css/reset/))*?
- **Are you using any CSS postprocessors** *(such as [Prefixfree](https://leaverou.github.io/prefixfree/) or [Autoprefixer](https://github.com/postcss/autoprefixer))*?
- **Are there specific CSS techniques you're utilizing** *(such as [critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/))*?

### CSS Frameworks
- **Is the team using a framework** *(such as [Bootstrap](https://getbootstrap.com/) or [Foundation](http://foundation.zurb.com/))*? If yes, where is the documentation for that framework?
- **Are you deviating from the framework in any way?** If so, can you highlight these conventions?

### CSS Style
- **Spaces or Tabs?**
- **Spacing around rules?**
- **[Grouping](https://smacss.com/book/formatting#grouping) properties?**
- **What does CSS commenting look like?** 

---------------

## JavaScript

### JavaScript Principles
- **What are some general principles your team should follow when writing JavaScript?** *(See [these](https://github.com/airbnb/javascript) [resources](https://github.com/rwaldron/idiomatic.js) for [inspiration](https://github.com/styleguide/javascript))*


### JavaScript tools
- **Are you using a JavaScript framework** *(such as [jQuery](https://jquery.com/), [Ember](http://emberjs.com/), [Angular](https://angularjs.org/), etc)*?
- **Where is the documentation for those frameworks?**
- **Are you using any polyfills or shims** *(such as [any of these](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills))*?
- **What third-party scripts are dependencies for your project** *(such as scripts for form validation, graphs, animation, etc)*?
- **Do you test your JavaScript?** If so, what tools do you use *(such as [Jasmine](https://jasmine.github.io/), [Karma](https://github.com/karma-runner/karma), [Selenium](http://docs.seleniumhq.org/), etc)*?

### JavaScript Style 
*(See [these](https://github.com/airbnb/javascript) [resources](https://github.com/rwaldron/idiomatic.js) for [inspiration](https://github.com/styleguide/javascript))*
- **Spaces or Tabs?**
- **What does JS commenting look like?** 
- **What patterns are you following?** *(See [these](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) [resources](https://shichuan.github.io/javascript-patterns/))*

---------------

## Media
- **How are you handling icons** *(such as using SVG, icon fonts, etc)*?
- **How are you handling responsive images** *(such as using `srcset` & `<picture />`)*?
- **Are you using any [tools](https://addyosmani.com/blog/image-optimization-tools/) to optimize and serve images**?

---------------

## Fonts
- **How do you load custom fonts?**
- **Do you use any tools to help implement web fonts** *(such as [Font Squirrel](https://www.fontsquirrel.com/), etc)*?
- **Do you use a service to manage and serve custom fonts** *(such as [Fonts.com](https://www.fonts.com/), [Typekit](https://typekit.com/), etc)*?


---------------

## Performance
- **Do you use performance budgets?** If so, what [metrics](https://timkadlec.com/2014/11/performance-budget-metrics/) are you using to determine budgets? Where are you keeping track of performance budgets?
- **How are you measuring your project's speed** *(such as [Pingdom Speed Test](http://tools.pingdom.com/) or [Google PageSpeed](https://developers.google.com/speed/pagespeed/))*?
- **What techniques are you using to decrease file size** *(such as [Gzip](https://css-tricks.com/snippets/htaccess/active-gzip-compression/), [Image Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization))*?
- **What performance-related tools are you using in your workflow?** *(such as [WebPagetest](http://www.webpagetest.org/), [BigRig](https://aerotwist.com/blog/bigrig/) [Speedcurve](https://speedcurve.com/))*?


---------------

## Accessibility
- **Are you following the accessibility recommendations laid out in [this checklist](http://a11yproject.com/checklist.html)?**
- **What accessibility-related [tools](http://a11yproject.com/resources.html) are you using in your workflow?**

---------------

## Tooling
- **Are you using a task runner** *(such as [Grunt](http://gruntjs.com/) or [Gulp](http://gulpjs.com/))*?
- **Are you using a dependency manager** *(such as [Bower](http://bower.io/) or [Composer](https://getcomposer.org/))*?
- **Are you using any scaffolding tools** *(such as [Yeoman](http://yeoman.io/))*?
- **Are you using any tools to reinforce frontend style** *(such as [Editor Config](http://editorconfig.org/) or [linters](https://github.com/CSSLint/csslint))*?
- **Are any other specific pieces of software that are needed to work on this project?**

---------------

## Version control
- **What version control system are you using for your frontend code** *(such as [Git](https://git-scm.com/) or [Subversion](https://subversion.apache.org/))*?
- **Where is your version-controlled code hosted** *(such  as [Github](https://github.com/) or [Bitbucket](https://bitbucket.org/))*?
- **Do you use a version control workflow** *(such as [gitflow](http://nvie.com/posts/a-successful-git-branching-model/), [centralized](https://www.atlassian.com/git/tutorials/comparing-workflows/centralized-workflow), [feature-branch](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow), etc)*?
- **Who's responsible for managing and governing the version controlled code?**?
- **Where are issues tracked?**

-----------

## Support and Optimization
It's important to recognize the difference between ["support" and "optimization"](http://bradfrost.com/blog/mobile/support-vs-optimization/). You should do your best to support as many environments as possible while simultaneously optimizing for the environments that make the most sense for your business and users. 

- **What browsers are you *optimizing* for?** 
- **What devices are you *optimizing* for?** 
- **Are you using a [graded browser support](https://github.com/yui/yui3/wiki/Graded-Browser-Support) system?**
- **Are there specific components that require [more specific grading](https://www.filamentgroup.com/lab/grade-the-components.html)?** 

-----------

## Localization
- **Is your website served in different languages?** If so, what considerations do you need to address when localizing for other languages?

-----------

## Deployment/Integration
- **How is your front-end code integrated into a production environment?**

-----------

## Documentation
- **Are you using a [pattern library tool](http://styleguides.io/tools.html) to document your front-end architecture?**
- **Where does your documentation live?** What are the links to the documentation?
- **Who's responsible for maintaining and governing the documentation?**
- **What happens when the guidelines are updated?**

-----------

*Feel free to modify or extend (such as adding specific sections for performance, accessibility, etc) this document for your own organization's needs. For questions, comments, additions, and corrections, please open an issue on Github and/or reach out to [@brad_frost](https://twitter.com/brad_frost) on Twitter.*
