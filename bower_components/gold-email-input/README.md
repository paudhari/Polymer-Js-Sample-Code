
<!---

This README is automatically generated from the comments in these files:
gold-email-input.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/gold-email-input.svg?branch=master)](https://travis-ci.org/PolymerElements/gold-email-input)

_[Demo and API docs](https://elements.polymer-project.org/elements/gold-email-input)_

⚠️ This element is deprecated ⚠️

This element will not be upgraded to Polymer 2.0. We recommend you use [`paper-input`](https://github.com/PolymerElements/paper-input) with [`type="email"`](https://www.webcomponents.org/element/PolymerElements/paper-input/elements/paper-input#property-type).

e.g. `<paper-input type="email" value="test@test.com"></paper-input>`

## &lt;gold-email-input&gt;

`<gold-email-input>` is a single-line text field with Material Design styling
for entering an email address.

```html
<gold-email-input></gold-email-input>
```

It may include an optional label, which by default is "Email".

```html
<gold-email-input label="your email address"></gold-email-input>
```

### Validation

The input can be automatically validated as the user is typing by using
the `auto-validate` and `required` attributes. For manual validation, the
element also has a `validate()` method, which returns the validity of the
input as well sets any appropriate error messages and styles.

See `Polymer.PaperInputBehavior` for more API docs.

### Styling

See `Polymer.PaperInputContainer` for a list of custom properties used to
style this element.


