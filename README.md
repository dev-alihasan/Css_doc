## Selectors:
  >Targeting Elements:
  1. Selectors are used to target specific elements on a webpage.
  2. You define selectors followed by curly braces {} where you specify the properties and their values.

```css
    selector {
    property: value;
    /* more properties... */
    }
```
  >Targeting by Class:
  1. You can target elements with a specific class using a dot (.) followed by the class name.
  2. This is useful when you want to style multiple elements with the same class.
```css
.class1 { }
```

 >Targeting by Multiple Classes:
1. You can target elements that have multiple classes by chaining the class names together without spaces.
```css
.class1.class2 { }
```
>Targeting by Element Type:
1. You can target elements based on their tag names directly.
2. This will style all elements of that type on the page.
```css
div { }
```
>Targeting by ID:
1. You can target elements with a specific ID using a hash (#) followed by the ID name.
2. IDs should be unique within a page.
```css
#id { }
```
>Targeting by Attribute Presence:
1. You can target elements based on the presence of an attribute regardless of its value.
```css
[attr] { }
```
>Targeting by Attribute Value:
1. You can target elements with a specific attribute value.
```css
[attr='value'] { }
```
>Targeting by Attribute Value Prefix (CSS 3):
1. You can target elements with an attribute whose value starts with a specific string.
```css
[attr^='val'] { }
```
>Targeting by Attribute Value Suffix (CSS 3):
1. You can target elements with an attribute whose value ends with a specific string.
```css
[attr$='ue'] { }
```
>Targeting by Attribute Value Containing a Word:
1. You can target elements with an attribute containing a specific word in a space-separated list of values.
```css
[otherAttr~='foo'] { }
```
>Targeting by Attribute Value Containing a Dash-Separated Word (CSS 3):
1. You can target elements with an attribute containing a specific word in a dash-separated list of values.
```css
[otherAttr|='en'] { }
```
