
<!---

This README is automatically generated from the comments in these files:
iron-icon.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

-->

[![Build Status](https://travis-ci.org/PolymerElements/iron-icon.svg?branch=master)](https://travis-ci.org/PolymerElements/iron-icon)

_[Demo and API Docs](https://elements.polymer-project.org/elements/iron-icon)_


##&lt;iron-icon&gt;



The `iron-icon` element displays an icon. By default an icon renders as a 24px square.

Example using src:

    <iron-icon src="star.png"></iron-icon>

Example setting size to 32px x 32px:

    <iron-icon class="big" src="big_star.png"></iron-icon>

    <style is="custom-style">
      .big {
        --iron-icon-height: 32px;
        --iron-icon-width: 32px;
      }
    </style>

The iron elements include several sets of icons.
To use the default set of icons, import `iron-icons.html` and use the `icon` attribute to specify an icon:

    <link rel="import" href="/components/iron-icons/iron-icons.html">

    <iron-icon icon="menu"></iron-icon>

To use a different built-in set of icons, import the specific `iron-icons/<iconset>-icons.html`, and
specify the icon as `<iconset>:<icon>`. For example, to use a communication icon, you would
use:

    <link rel="import" href="/components/iron-icons/communication-icons.html">

    <iron-icon icon="communication:email"></iron-icon>

You can also create custom icon sets of bitmap or SVG icons.

Example of using an icon named `cherry` from a custom iconset with the ID `fruit`:

    <iron-icon icon="fruit:cherry"></iron-icon>

See [iron-iconset](iron-iconset) and [iron-iconset-svg](iron-iconset-svg) for more information about
how to create a custom iconset.

See the [iron-icons demo](iron-icons?view=demo:demo/index.html) to see the icons available
in the various iconsets.


### Styling

The following custom properties are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--iron-icon-width` | Width of the icon | `24px`
`--iron-icon-height` | Height of the icon | `24px`
`--iron-icon-fill-color` | Fill color of the svg icon | `currentcolor`
`--iron-icon-stroke-color` | Stroke color of the svg icon | none


