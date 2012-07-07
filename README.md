Backbone Dispose
----------------

A small Backbone extensions that allows to dispose a view, therefore to release used resources. Useful when you have a view that bound to some events of a model and you want to remove this view and unbind it from the model.

If a view has a subviews they will be disposed automatically if a `parent` parameter pointing to the parent view was passed:

```
new SubView({collection: collection, parent: this});
```