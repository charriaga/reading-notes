# CSS Basics

## Definition

Also known as **Cascading Style Sheet**, CSS is the language used to add visual appeal and aesthetic choices to websites. It is important for graphic design and readability.

## Linking CSS to an HTML File

There are 3 main ways one can attach css stylization to an HTML file.

### External

**External CSS** is the practice of creating a separate CSS file and linking it to an HTML file via the `<link>` element in the `head` section of the document. This allows a clean separation of code languages and allows you to make edits to one aspect of the repository without accidentally altering another.

This is the industry standard and should be the default way one applies CSS.

### Internal

Used in instances one HTML page might have a unique style, **Internal CSS** utilizes the HTML element `<style>`. CSS code can be written nestled in the `<style>` element within the HTML file. This is typically applied within the `head`.

### Inline

**Inline CSS** is used in very specific cases one might wish to make a single CSS edit to a single HTML element. The `style` attribute can be added to any element and used to contain CSS specifications.

## Syntax

The basic syntax is divided into two parts, the `selector` and the `declaration` - written as such: 

`selector {declaration, declaration, etc}`

One selector can contain endless declarations.

### Selector

The **selector**  can be one of three things. The name of the HTML element that you wish to add CSS alterations to, the class of an HTML element, or the ID of an HTML element. Examples of selectors are 'h2','p', and 'section'.

A class selector is written as `.class`.

An ID selection is written as `#id`.

### Declaration

The **declaration** is divided further into two parts, a **property** and a **value**. The property is what you want changed, (example: text color) and the value is what you want it changed to (example: red). It is written as `{property: value; property: value;}`.

### Example

To change every paragraph's text color to red in an HTML document, one would use the `p` selector with the `color` property.

`p {color: red;}`