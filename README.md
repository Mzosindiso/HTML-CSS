
```markdown
# HTML-CSS

1. **HTML** is responsible for marking up the content of a website and informs the user's computer about various elements on the page.
2. **DOM** (Document Object Model) is important when working with CSS and JavaScript.
3. **HTML** default font-size is 16px.
4. **HTML** is used for structure and semantics (meaning).
5. **Elements** identify different parts of the HTML using tags.
6. **Attributes** provide additional information about a particular instance of an element.

## HTML List Tags
- `ol` = ordered (numbered) list.
- `li` = list item.
- `dl` = definition (description) list.
  1. `dt` = definition term.
  2. `dd` = definition description.
- `ul` = unordered (bulleted) list.

**Superscripts** - characters that are set above the normal baseline of text.  
**Subscripts** - characters that are set below the normal baseline of text.

**Global attributes** - `class`, `id`, `lang`, `dir`.  
To prevent line breaks, use `&nbsp`.

**Title attribute** - provides additional information about an element (tooltip).  
**Contenteditable attribute** - enables editing of an element's content.  
**Deprecated attributes** - tags that are no longer valid.

**HTTPS** - HyperText Transfer Protocol Secure.

**SVG format** is good for sketches, while **PNG** is best for transparency in photographs.  
**Captions** - use `kind="subtitles/captions"` and `srclang` for language.  
**Attribute**: `description` enables us to create a VTT file that describes visual elements in the video.  
**Element used for captions**: `<track>`.  
**Div element** is used for grouping, while **span element** is for inline text.

**Meta element** - informs the browser that the layout has been adjusted to support all small screens.

## HTML5 Sectioning Elements
- `header`
- `footer`
- `aside`
- `section`
- `article`

**HTML Table tags**: `table`, `tr`, `th`, `td`.  
HTML5 is called the living standard.  
**Div tags** are used to logically divide the document.  
**ASCII** - American Standard Code for Information Interchange.

## Cascading Style Sheets (CSS)
CSS is divided into two parts:
1. The selector.
2. The declaration block.

The selector specifies the pattern in HTML, and if matched, the styles within the declaration block apply to the corresponding HTML elements.

```html
<style>
   p {
       color: red;
   }
</style>
```

- `p` = selector.
- `color` = property.
- `red` = value.

The declaration block consists of (property + value).

## Types of Selectors
1. Element selector
2. Class selector
3. ID selector
4. Universal selector
5. Descendant selector
6. Attribute selector

**Universal selector (`*`)** - matches any element type.  
**Relative link** - points to your own stylesheet.  
**Absolute link** - a stylesheet not residing in your own site.

- `display: block` - generates a block box, adding line breaks before and after the element.
- `display: inline` - generates inline boxes without line breaks.

**CSS property `z-index`** - specifies the stacking order of positioned elements.

## Managing Positions in CSS
1. **Static** – default, elements flow according to normal rules.
2. **Relative** – positioned relative to its normal position.
3. **Absolute** – positioned relative to its first positioned ancestor.
4. **Fixed** – stays in place, fixed to the background during scrolling.
5. **Inherit** – inherits its position value from the parent.

(i) **Absolute sizes** do not change with screen size (pixels & points).  
(ii) **Relative sizes** change with screen size and zoom (percentages & rems), offering better flexibility.

**Hexadecimal code notation** - consists of six digits (0-9, A-F). If each two-digit pair is the same, it can be shortened (e.g., `#776655` = `#765`).

The **box model** consists of four main parts: margin, padding, content, and border.
1. **Margin** - space outside the border.
2. **Padding** - space between content and border.
3. **Content** - the actual text, image, or media inside the element.
4. **Border** - surrounds the padding/content if there is no padding.

## Pseudo-classes
1. Pseudo-classes start with a colon and select elements in a specific state (e.g., `:hover`, `:focus`).
2. Pseudo-elements start with a double colon and act as if new HTML markup has been added (e.g., `::before`).

**Flexbox** - enables vertical centering of block content inside its parent. All columns in a multi-column layout adopt the same height, even if they contain different amounts of content.

**WCAG** - Web Content Accessibility Guidelines.

## Media Query Basics
Media queries consist of a media type (specifying the kind of media for the code) and a media expression (rules that must be met for the contained CSS to apply).

## CSS At Rules (@)
These CSS statements instruct how CSS should behave, starting with `@` followed by an identifier and CSS block.
(i) They enable you to create a block of rules that apply to a specific subsection of the HTML on your page.

The cascade works by assigning every property and selector a weight based on specificity. If a class selector has more weight than an element selector, properties from the class style block will override those in the element style block, helping to avoid repetition in CSS.

## em & rem
(i) **em** unit means "my parent element's font-size" when used for font-size.  
(ii) **rem** unit means "the root element's font-size" (rem stands for "root em").

## Colors
1. **H** - Base shade of the color (hwb() function).  
   **W** - How white is the color.  
   **B** - How black is the color.  
2. **H** - Hue (hsl() function).  
   **S** - Saturation.  
   **L** - Lightness.  

A **reduced test case** is a simplified code example that demonstrates a problem clearly.

## ARIA
**Accessible Rich Internet Applications (ARIA)** - a set of roles and attributes designed to enhance accessibility for people with disabilities in web content and applications.
```
