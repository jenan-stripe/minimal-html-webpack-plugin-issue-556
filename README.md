## Example of html-webpack-plugin issue #556

This is a minimal example of [webpack issue #556](https://github.com/ampedandwired/html-webpack-plugin/issues/556). See there for details.

### Instructions

```bash
# Run once
npm run build
# outputs `dist/index-049353bd93a9f89ff66e.html`

# Update js and run again
echo >> example.js
npm run build
# outputs `dist/index-049353bd93a9f89ff66e.html` again
# with different content
```
