# rails-bootstrap
[rails][bootstrap][asset pipeline]

Incorporate bootstrap and SASS into your rails app.
Use the asset pipeline to get JS and CSS to the browser.

### bootstrap
- install the boostrap gem in your rails app and `@import` it in your app.
- incorporate the bootstrap starter template into your `app/views/layouts/application.html.erb` file
- [https://getbootstrap.com/docs/4.1/getting-started/introduction/#starter-template](https://getbootstrap.com/docs/4.1/getting-started/introduction/#starter-template)

- or: [https://getbootstrap.com/docs/4.1/examples/jumbotron/](https://getbootstrap.com/docs/4.1/examples/jumbotron/)
- or look at more here: [https://getbootstrap.com/docs/4.1/examples/](https://getbootstrap.com/docs/4.1/examples/)

### SASS
- use `asset-url` to set a css `background-image` style
- use a bootstrap variable [https://github.com/twbs/bootstrap-rubygem/blob/master/assets/stylesheets/bootstrap/_variables.scss](https://github.com/twbs/bootstrap-rubygem/blob/master/assets/stylesheets/bootstrap/_variables.scss) somewhere in your style sheet
- use your own variables to set text color, background color and other styles for `body`

### js
- create a js file with an alert
- place in your `app/assets/javascripts` directory to see that it works.

### Further
- implement the jquery table sorting code here: https://github.com/wdi-sg/user-songs/blob/asset-pipeline/frontend.md
