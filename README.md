# birchtree-buttons

A few buttons to get you started on your next proejct. These are meant to be simple, but add a little style to your projects without having to think about them much.

## Usage

Similar to Bootstrap, this is all based on classes. Simply create a <code>button</code> element and give it the class <code>bt-btn</code>. So something like...

```
<button class="bt-btn">Pay Now</button>
```

...is all it takes to get a styled button.

Next, add a second class to create a specific type of button, such as...

```
<button class="bt-btn bt-danger">Danger</button>
```

You can choose between 5 styles of buttons (besides the default blue):

* bt-submit
* bt-warning
* bt-danger
* bt-dark
* bt-light

Finally, you can choose the size of the button. The standard size is fine for most situations, but if you want something a bit smaller or larder, options are available using <code>bt-sm</code> and <code>bt-mega</code>.

```
<button class="bt-btn bt-submit bt-sm">Confirm, Do the Thing</button>
<button class="bt-btn bt-danger bt-mega">Warning, Please Confirm This</button>
```
