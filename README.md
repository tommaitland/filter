filter.js
=========

A very basic jQuery filter plugin. Show/hide elements based on selected tags.

### Usage

```javascript
$(element).filter({
		nav: '[data-filter]' // selector for filter nav (optional)
});
```

Set the tag to filter with `data-filter`, eg:
```html
<a data-filter="tag">Tag</a>
```

Filterable elements should have their tags comma separated in `data-filter-tags`, eg:
```html
<div data-filter-tags="tag1,tag2,tag3">This is a block</a>
```

### Demo

*Coming soon*

### Support

I haven't done much testing on this script, and it could probably be more flexible. It requires an element be matched to all selected tags, this could be set to be more loose (etc).

Suggestions/bugs welcome through [Issues](https://github.com/tommaitland/filter.js/issues)
