# Birchtree.css

### Work in progress

A few UI elements to get you going with simple web projects. This is not meant to replace Bootstrap by any means, it's just aimed at giving you a lightweight way to make things like personal site and test pages look a little nicer.

## Usage

Similar to Bootstrap, this is almost entirely based on classes. Simply create a <code>button</code> element and give it the class <code>bt-btn</code>. So something like...

```html
<button class="bt-btn">Pay Now</button>
```

<button class="bt-btn">Pay Now</button>

...is all it takes to get a styled button.

Next, add a second class to create a specific type of button, such as...

```html
<button class="bt-btn bt-danger">Danger</button>
```

You can choose between 5 styles of buttons (besides the default blue):

* <code>bt-submit</code>
* <code>bt-warning</code>
* <code>bt-danger</code>
* <code>bt-dark</code>
* <code>bt-light</code>

Finally, you can choose the size of the button. The standard size is fine for most situations, but if you want something a bit smaller or larder, options are available using <code>bt-sm</code> and <code>bt-mega</code>.

```html
<button class="bt-btn bt-submit bt-sm">Confirm, Do the Thing</button>
<button class="bt-btn bt-danger bt-mega">Warning, Please Confirm This</button>
```
