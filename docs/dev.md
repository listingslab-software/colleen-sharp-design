## Dev

Documents are stored in NoSQL with the following _Shape_

```javascript
const portfolioObjectShape = {
    title: "Most important four words",
    excerpt: "Short strapline for underneath title",
    body: "If you've got a lot to say about this one, say it here"
    image: {
        title: "alt tag for this image"
        src: "...filepath.jpg"
    }
}
```