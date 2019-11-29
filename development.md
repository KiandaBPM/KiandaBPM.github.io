## Introduction to widget development with Kianda

Kianda comes with a number of pre-defined field widgets. In case none of them satisfies your specific needs and if you have some level of development skills you can always create your own custom field widget.

## EmberJS templating basics

Ember uses the Handlebars templating library to power application user interface. Handlebar templates contain static HTML and dynamic content inside Handlebars expressions, which are summoned with double curly braces: {{ }}

Dynamic content inside a Handlebars expression is rendered with data-binding. This means if you update a property, your usage of that property in a template will be automatically updated to the latest value.

**Helpers:** Ember gives the ability to write your own helpers, to bring a minimum of logic into Ember templating. For example, let's say you would like the ability to add a few numbers together, without needing to define a computed property everywhere you would like to do so.

![Helper](images\write our own helpers.PNG)

**Conditionals:** Statements like if and unless are implemented as built-in helpers. Helpers can be invoked three ways; inline invocation, nested invocation and block invocation. For more details, click on the following link https://guides.emberjs.com/v2.18.0/templates/conditionals/.

## Widget development basics

<video width="100%" style="width:100%" controls>
    <source src="videos/Creating a widget.mp4">
    Your browser does not support the video tag.
    </source>
</video>

## List widget custom fields

