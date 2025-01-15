# Horizontal Drag Scroller

A lightweight JavaScript/JQuery utility to enable horizontal drag scrolling on any scrollable container.

## Features

- Easy to integrate and use.
- Smooth horizontal scrolling using click and drag gestures on Desktops.
- Works with any scrollable container.

---

## How to Use

### 1. Include the Script

Add the `horizontal_drag_scroller.js` script to your HTML file:

```html
<script src="scripts/horizontal_drag_scroller.js"></script>
```

### 2. Initialize Drag Scrolling
Pass the ID of the scrollable container to the initDragScroll function:
```html
<script>
  initDragScroll('#scroll-container'); // Example: ID selector
</script>
```

### 3. Example HTML Structure
```html
<div id="scroll-container" style="overflow-x: auto; white-space: nowrap;">
  <div style="display: inline-block; width: 300px; height: 200px; background: lightblue;">Item 1</div>
  <div style="display: inline-block; width: 300px; height: 200px; background: lightcoral;">Item 2</div>
  <div style="display: inline-block; width: 300px; height: 200px; background: lightgreen;">Item 3</div>
</div>
```
