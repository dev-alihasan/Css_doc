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
