# Creating UI in Sapiens

UI in Sapiens relies on a few different things. This page will somewhat introduce the vocabulary, and show a quick example.

## Getting Started

To get started, you should start with an entry point that contains UI that you can hook into, for example the `gameUI`.

Then, you can start your view: `mainView = View.new(gameUI.view)`. Every time you create a new View, pass in your parent view as the first argument.

`Note:` `View` and other kinds of Views such as `ImageView` are not defined in lua. Just use them.

On each view you can set fields such as:
 - `Hidden` : `bool`
 - `RelativePosition`: `ViewPosition`
 - `size` : `vec2`

# UI Types

## View

Blank slate, like `div`

## Model View

Render a model. Useful for creating background plates.




