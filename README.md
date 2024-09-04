# HTML-CSS
<strong>Html</strong> is responsible for marking up content of a website, and it informs the user's computer about various elements on the page. <br>
<strong>DOM</strong> - Document Oriented Model, it is important when working with CSS and JavaScript. <br>
<strong>HTML</strong> default font-size = 4. <br>
<strong>HTML</strong> is used for structure & semantics(meaning).
<strong>Elements</strong>, identify different parts of the HTML using tags.<br>
<strong>Attributes</strong>, provide additional information about a particular instance of an element.<br>
<strong>Elements</strong> that make text bold/italicized, <em></em> and <strong></strong>. convey meaning and serve a language-related purpose. 
<i></i>, <b></b> do not carry any meaning.
			
			HTML 3 types of list tags
- ol = ordered/numbered list.
- li = stands for (list items).
- dl = definition/description list.
	1. dt = definition term.
	2. dd = definition description/names.
- ul = unordered/bulleted list.

Superscipts - characters that are set above the normal baseline of text. <br>
Subscripts - characters that are set below the normal baseline of text.

Global attributes - class, id, lang, dir.
For not breaking line we use - &nbsp

HTML attribute that is used to provide additional information about an element (tooltip) - title. <br>
HTML contenteditable attribute enables editing of the element's content. <br>
Depecated attributes, are tags that are no longer valid to use.

HTTPS - HyperText Transport Protocol Secure.

SVG format it is good for sketches, <br> PNG for transparency in a potograph <br>
Working with captions (kind ="subtitles/captions"), srclang - for language. <br>
Attribute: description, enables us to create vtt file that decribes visual elements in the video. <br>
Element used for captions: <track> <br>
The div element is used for grouping, and span element is used for inline text. <br>
Meta element: informs the browser that the layout has been adjusted to support all small screens.

			HTML 5 Sectioning Elements
-header.
-footer.
-aside.
-section.
-article.

HTML Table tags: table,tr,th, td. <br>
HTML5 is called the living standards.

- div tags: are used to logically divide the document. <br>
ASCII - American Standard Code for Information Interchange.

			Cascading Style Sheets (CSS)
-It is divided intop two parts:
1. The selector.
2. The declaration block.
Selector specifies the pattern in HTML, and if that matches, the styles within the declaration block are applied to the coreesponding HTML elements.

   p{
	color: red;
   } <br>
p = selector. <br>
color = property. <br>
red = value. <br>
declaration block consist of (property + value).

			Types of Selectors
1. Element selector
2. Class selector
3. ID selector
4. Universal selector
5. Descendant selector
6. Attribute selector

(*) - This is a universal selector, matches(targets) any element type.<br>
A relative link, your own style sheet.<br>
An absolute link, a style sheet that doe not reside in your own site.

display: block (the element generates a block box, generating line breaks both before and after the element when in the normal form)<br>
display: inline (the elemenmt generates one or more inline boxes that do not generate line breaks before or after themselves)

CSS property z-index - specifies the stacking order of positioned elements.

			Managing positions in CSS: 

1. Static – default, elements flow according to the rules of normal flow. 
2. Relative – elements are positioned relative to its normal position. 
3. Absolute – elements are positioned relative to its first positioned ancestor element. 
4. Fixed – element not moving, fixed to the background even when scrolling the page. 
5. Inherit – the selected/current element should use the same value for position as its parent element.

(i) absolute sizes, do not change with screen size (pixels & points). <br>
(ii) relative sizes, changes with screen size and zoom (percentage & rems) and it is better for flexibility.

Hexidecimals code notation - hex values consists of six digits long(numbers: zeo to nine, letters: A to F). <br>
-If each two-digit pair is the same, it can be shortened, e.g(#776655 = #765). <br>

Box model comsists of four main parts, margin, padding, content and border.
1. Margin - space outside the border.
2. Padding - space between the content and border.
3. Content - the actual text, image or other media inside the element.
4. Border - surrounds the padding/content if there is no padding.


			Pseudo-classes
1. Pseudo classes start with a colon. <br>
 - Is a selector that select elements in a specific state, e.g :hover, :focus are pseudo-class. They target some bit of the document that is in a certain state.
2. Pseudo elements starts with a double colon. <br>
 - They act as if a whole new HTML element markup has been added. e.g ::before <br>

Flexbox - enables you to vertically center a block content inside its parent.
- All columns, in a multiple column layout adopt the same height even if they contain different amount of content.


WCAG - Web Content Accessibility Guidelines.

			Media Query Basics
It consists of a media type (tells the browser what kind of media this code is for), <br> 
Media expression (rule/test that must be passed for the contained CSS to be applied).

			CSS At Rules(@)
These are CSS statements that instruct how CSS should behave. They start with: @ followed by identifier and CSS block.
(i) Enables you to create a block of rules that will only apply to a specific subsection of the HTML on your page.

- Cascade works by giving every property and a selector a weight, and the weight is a combination of what we call specifity.
- If a class selector has more weight than the element selector, properties defined in the class style blocks will override those in the element style block.
- The behaviour helps to avoid repetition in CSS

			em & rem
(i) em unit means "my parent element's font-size" if used for font-size. <br>
(ii) rem unit means "the root element's font-size" (rem stands for "root em").

			Colors
1. H - The base shade of the color. hwb() function<br>
   W - How white is the color. <br>
   B - How black is the color. <br>
2. H - Hue. hsl() function <br>
   S - Saturation. <br>
   L - Lightness. <br>

- Reduced test case, is a code example that demonstrate the problem in the simpliest way.

			Aria
- Accessible Rich Internet Applications, set of roles and attributes that define ways to make a web content and web applications more accessible to people with disabilities.

			NB: Porfolio requirements
- Professional bio, Acquired skills, Showcase completed projects, and get in touch. (HTML) <br>
- Apply css to web pages, use selectors, manage color and multimedia, apply the box model, style hyperlinks.

