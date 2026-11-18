# BuildBot Kids

Website for BuildBot Kids: 3D printing, creativity, design and STEM.

Instagram: [@buildbotkids](https://www.instagram.com/buildbotkids/)

## How the site is put together

The whole site is one file, `index.html`. Product photos go in the `images/` folder.

## Adding or changing a listing

Open `index.html` and find the list that starts with `var DEFAULTS = [`. Each line is one listing:

```js
{ name: "Custom Keychains", blurb: "Short description.", price: "$5", img: "images/keychain.jpg", tint: "#E8508F", category: "Gifting" },
```

- `name`: the title on the card
- `blurb`: one short sentence
- `price`: for example `"$5"`. Leave `""` to show "Message for price"
- `img`: a photo in the `images/` folder. Leave it out to show the placeholder
- `tint`: background color of the photo area
- `category`: `"Christmas"`, `"Halloween"` or `"Gifting"`. Leave it out to show under All only
- `cta`: button text. Leave it out for "Order"
