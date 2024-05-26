Notes from CSS Class #1:

• What is CSS?
    CSS stands for Cascading Style Sheets.

• What are Cascading Style Sheets (CSS) used for?
    It is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG [Scalable Vector Graphics], MathML [Mathematical Markup Language] or XHTML [Extensible Hyper Text Markup Language]). CSS describes how HTML documents are to be displayed on screen, paper, or in other media.

• Did you know? 
    CSS saves a lot of work. It can control the layout of multiple web pages all at once. External stylesheets are stored in CSS files.

• How does CSS function?
    When a browser loads a file, it identifies and fetches any linked or embedded CSS. It then parses these CSS rules and contructs a render tree that combines the document's content and styles. Using this render tree, the browser paints the visual representation of the web page. This process ensures that all specified styles are applied to the corresponding HTML elements, resulting in a styled web page.

• CSS Inheritance: 
    Not all CSS properties are inherited. Inheritance in CSS only occurs when an inheritable property is not set on an element. It goes up in its parent chain to set the property value to its parent value.

• CSS Cascade: 
    In CSS, "cascading" refers to the process by which the browser determines which styles to apply to an element when multiple rules could apply. This is done through a hierarchy of importance where styles are prioritized based on specificity, importance and source order. The '!important' keyword can override other rules, and if specificity and importance are equal, the last declared rule in the source order takes precedence. 

• CSS Specificity:
    It represents a measure of how precisely a selector targets an element. It is used to determine which styles are applied when multiple selectors share the same element. It is calculated based on system weights assigned to different types of selectors: inline styles (styling within an HTML tag) have the highest specificity, followed by IDs, classes/attributes/pseudo-classes, and finally tag selectors. 

• CSS Specificity Order: 
    1. Inline Styles
    2. IDs
    3. Classes/Attributes/Pseudo-Classes
    4. Tag Selectors

• CSS Common Attributes: 
    This concept refers to the set of CSS properties that are frequently applied across different HTML elements to control their appearance and layout. These properties address common styling needs such as color, font, margin, padding, border and background. 

• CSS Units: 
    CSS has several different units for expressing a length. Many CSS properties take "length" values, such as width, margin, padding, font-size, etc. Lenght is a number followed by a length unit, such as 10px, 2em, etc. 
        ABOSOLUTE LENGTHS
                cm ---- centimeters
                mm ---- millimeters
                in ---- inches (1in = 96px = 2.54cm)
                px ---- pixels (1px = 1/96th of 1in)
                pt ---- points (1pt = 1/72th of 1in)
                pc ---- picas  (1pc = 12pt)
        RELATIVE LENGTHS 
                em ---- relative to the font-size of the element (2em means 2 times the size of the current font)
                ex ---- relative to the x-height of the current font (rarely used)
                ch ---- relative to the width of the "0" (zero)
               rem ---- relative to the font size of the root element
                vw ---- relative to 1% of the width of the viewport
                vh ---- relative to 1% of the height of the viewport
                %  ---- relative to the parent element

TIP: The em and rem units are practical in creating perfectly scalable layout!
* Viewport = the browser window size. If the viewport is 50cm wide, 1vw = 0.5cm. 

• CSS Box Model: 
    In CSS, the term box model is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: content, padding, border and margin. It allows us to add border around elements, and to define space between elements. 
    -Explanation of the different parts: 
     • CONTENT: The content of the box, where text and images appear.
     • PADDING: Clears an area around the content. The padding is transparent. 
     • BORDER: A border that goes around the padding and content. 
     • MARGIN: Clears an area outside the border. The margin is transparent. 