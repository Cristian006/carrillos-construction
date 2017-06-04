# Carrillos Construction

Website at: [https://carrillos-construction.com](https://carrillos-construction.com);

Remember to remove snippet from `bower_components/app-header-layout/app-header-layout.html`

```javascript
/* REMOVE THESE LINES OF CODE */
// Update the content container position.
var containerStyle = this.$.contentContainer.style;
if (header.fixed && !header.condenses && this.hasScrollingRegion) {
  // If the header size does not change and we're using a scrolling region, exclude
  // the header area from the scrolling region so that the header doesn't overlap
  // the scrollbar.
  containerStyle.marginTop = headerHeight + 'px';
  containerStyle.paddingTop = '';
} else {
  containerStyle.paddingTop = headerHeight + 'px';
  containerStyle.marginTop = '';
}
```
