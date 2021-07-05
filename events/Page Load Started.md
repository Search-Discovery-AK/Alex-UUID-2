# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventDataUUID2 = window.appEventDataUUID2 || [];
appEventDataUUID2.push({
  "event": "Page Load Started"
});
```




