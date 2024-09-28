# Dynamic iframe resizing

Dynamic resizing of an iframe in cooperation with cross-origin content provider

## The problem
You put an iframe on your page and have no idea how tall to make it to integrate nicely in your design. Especially if the content is dynamic and changes its size due to user interaction.
There is no probing of the inner iframe content from the outer host page due to security reasons, especially same-origin policy.

## The solution
Go talk to your content provider, the person responsible for the stuff inside the iframe. Nicely ask them to put some javascript on their page, which reports the height of the content to the parent element/window.

## Use cases
Race registration via [sportt.cz](https://sportt.cz), for example at [trailmaniacs.cz/registrace/](http://trailmaniacs.cz/registrace/) and [trailmaniacs.cz/prihlaseni-zavodnici/](http://trailmaniacs.cz/prihlaseni-zavodnici/)

## See it in action
See it in action at https://ondrahlavac.github.io/dynamic-iframe-resizing/

Made with :yellow_heart: in [Prague](https://mapy.cz/s/jfYj)