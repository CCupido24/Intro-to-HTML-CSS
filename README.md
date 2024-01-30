# Intro-to-HTML-CSS
This course teaches HTML, the foundation of website and web app development, and semantic markup, which ensures content is understandable to both humans and computers. It covers fundamental syntax, content formatting, image incorporation, hyperlinks, global attributes, navigation menus, content organization, interactive forms, and data tables. This helps improve web accessibility for differently abled individuals.

Week 1 Uint 1: Intoduction to HTML
- HTML is a crucial component in web technology, serving as a channel for various content types such as words, images, videos, audio, forms, and interactive 
  experiences.
- It forms the foundation for all digital realms. The internet serves as a meeting point between human and computer languages, as websites are programmed and consumed 
  by people or other computers. 
- Artificial intelligence aims to enable computers to intelligently comprehend human activities. HTML is designed to bridge the gap between human and computer 
  languages, allowing us to structure content and bridge the gap between human and computer languages.
- The Web relies on three programming languages: HTML, CSS, and JavaScript, each with its unique role. Developers combine these languages to achieve resilience, 
  robustness, and power in their websites. They use the more robust features of these languages and use the remaining parts to enhance the site. HTML is preferred for 
  tasks that can be done in HTML, while other languages are used if necessary. Learning all the elements and attributes of HTML is essential to fully benefit from its 
  capabilities.

Week 1 Unit 2: HTML Text Formatting
HTML Paragraphs 
- HTML is a language for structuring web pages. It distinguishes between elements by using tags surrounded by less-than and greater-than marks. Tags occur in two 
  varieties: opening tags and closing tags. A paragraph's opening and ending tags are \<p> and \</p>, respectively.
- This course explores the use of HTML elements, which are packages containing content. Some elements, like paragraphs, require both an opening and a closing tag, 
  while others do not. The purpose of HTML markup is to provide meaning to content and help computers understand it. It serves as a bridge between humans and 
  computers. An example is a short paragraph with emphasized text wrapped in p tags. An emphasized phrase is turned into a separate element using em tags. HTML 
  elements can be nested within one another, enhancing their functionality.
- An HTML document is a collection of HTML elements nested within each other, creating a tree structure like a family tree. This structure is called a DOM tree, or 
  Document Object Model, and is crucial for working with CSS, JavaScript, and developers. 
- The DOM tree also creates an accessibility tree, which impacts the user experience on a website, including those with disabilities.The choice of HTML elements 
  significantly impacts the user experience on a website.
- It's crucial to consider the placement of HTML tags and how elements are nested within each other to convey content and interfaces effectively.

HTML HeadLines
- Headlines are essential elements in web pages, dividing lengthy text into smaller, more digestible chunks.
- They are found everywhere and act as clickable titles on landing pages. Headlines come in six different types: h1, h2, h3, h4, h5, and h6. Each headline has a 
  distinct visual effect and conveys a sense of hierarchy in how the browser interprets and communicates about the page. The h1 element is the largest and most 
  prominent, while h6 is the smallest and least attention-grabbing.
- Selecting the appropriate headline level is generally straightforward, starting with the opening tag (e.g. h1) and ending with the closing tag. However, determining 
  the most suitable level of headline can be challenging at times.
- Although there isn't a set formula, using these six stages can significantly improve the organization and consistency of your content. The six tiers of headline 
  possibilities give you the freedom to choose when and how to use them to create a semantic hierarchy.
  
HTML Bold and Italics
- HTML contains four components that allow us to mark text as bold or italics. Two of them, "\<em>" and "\<strong>", transmit meaning and fulfill a linguistic purpose.
- The other two, "\<i>" and "\<b>", do not have any specific purpose and are only used for visual design.

HTML Lists
- Lists are integral to our daily lives, including to-do lists, recipes, wish lists, and bucket lists. However, they are more prevalent on the internet, often 
  appearing in navigation bars or landing pages with captivating content.
- In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. These lists can be found in various formats, such as navigation bars 
  and landing pages.
- Unordered lists are the most common type of list, such as a recipe list of ingredients. Each item is enclosed in an \<li> element, with a dot or marker before it. To 
  define the entire list and specify its type, all items are wrapped in an \<ul> element, representing an unordered list.
- A definition list, also known as a "description list" in HTML, is a type of list used in computer science to create a key-value pair. It consists of terms and their 
  corresponding descriptions, enclosed in tags. 
- The term or key is enclosed in a tag, while the description or value is enclosed in a tag. Multiple descriptions can be provided for each term using multiple tags. - The entire list is wrapped in a tag, representing the definition list. The tags and tags are placed side by side without any additional wrapper, illustrating the 
  structure of a definition list.
  
HTML Quotes
- The HTML \<blockquote> element defines a section that is quoted from another source.
- The HTML \<abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
- Marking abbreviations can give useful information to browsers, translation systems and search-engines.
Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.

HTML Date and Time Inputs
- HTML simplifies programming by using a single element called <time> to mark specific moments or ranges in time, such as a time of day, date, or duration. The  
  \<time> element consists of an opening tag \(<time>) and a closing tag \(</time>) and can be used in any human-readable format for the text between the tags. The 
  main purpose of the \<time> element is to convey the exact date or time to computers, which is achieved using an HTML attribute called "datetime."
- The datetime attribute allows us to specify the date or time in a format that computers can understand, such as \<time datetime="2025-05-08">May 8, 2025</time>. The 
  format of the time within the datetime attribute must be specific, as dates and times have a special format that machines can understand. For example, May 8th is 
  represented as 05, 08. The machine-readable version of the datetime attribute starts with the year, four digits, followed by the month in two digits, and the date 
  in two digits.
- The datetime attribute allows for the combination of date and time in HTML. It includes the date and time, separated by a space or a T. Machine-readable time 
  formatting rules are acceptable and correct, applicable to many programming languages. There are numerous combinations to use, so it's important to research them 
  when needed. The time element with its datetime attribute allows for the conveying of time in a way that computers can understand.

HTML Code, pre and br
- To showcase code on a webpage, use the code element to create a monospaced font and style it with a monospaced font. By default, code is treated as an inline 
  element, meaning it remains part of the sentence. To change the word "H4" into an actual H4 headline, use an HTML entity like "&lt;" or "&gt;". This will display a 
  less than sign and a greater than sign respectively.
- For example, if we want to display HTML code on a page instead of executing it, we can use the br and pre-elements. The br element is a simple tag without an 
  opening or closing tag, indicating where a line break should occur. It does not contain anything inside it but indicates where a line break should happen.
- When writing code, we can add as many spaces and line breaks as we want, and the browser will ignore them. However, if we want to show those spaces and line 
  breaks, we can use the br element at the end of each line. This will make the poem look correct and make it more readable without affecting the webpage's content.
- In summary, using the br and pre-elements can help showcase code on a webpage, making it more readable and visually appealing.
- The combination of pre and code elements is common for displaying a code block with proper indentation. In HTML, indentation is added to make it easier to 
  understand. CSS code is also indented. The entire code is wrapped in a code element to indicate it's a block of code, while a pre-element preserves formatting and 
  spacing. These three elements are essential for conveying the structure and appearance of code and other content types.


HTML Superscripts, Subscripts and Small Text
- Subscripts, superscripts, and small text are used in HTML to mark-up specific parts of content with different meanings. Subscripts are characters set below the 
  normal baseline for text, like the formula for water, H2O. Superscripts are characters set above the normal baseline, like mathematical formulas or footnote 
  markers.
- To mark-up subscripts and superscripts, use the sub and sup elements. For example, to format H2O as a footnote, wrap the two characters in its sub-element and drop 
  them below the baseline. For superscripts, wrap the two characters in sup, jump up higher, and get smaller. This is how to handle subscripts and superscripts in 
  HTML with the sub and sup elements.
- MathML is a powerful markup language for math that can be used to mark complex equations on websites. It is also useful for indicating small text that is not as 
  important but still needs to be included. For example, copyright information can be placed in the footer of a page, and a small element can be used to convey its 
  low prominence.
- CSS can adjust the size of text to any desired size, large or small. However, small text can be used to convey that something has very little prominence, like the 
  fine print at the bottom of a page regarding ownership of the content. This text can be conveyed to the browser as "Hey, this is the fine print. " It is not the 
  main attraction. 
- Small, sub, and sup elements can help in typography and convey the full meaning of your content.

Week 1 Unit 3: HTML Capabilities Troubleshooting and Debugging HTML Code
HTML Capabilities
- When evaluating markup, it is critical to visit other websites with similar information and utilize the HTML inspector to identify errors. For example, if the 
  website was created by a team we admire, analyzing their work allows us to better grasp how to structure our own HTML. Additionally, the HTML inspector in the 
  development tools can be utilized to debug errors.
- One problematic code example is an unordered list with four elements that should be numbered one, two, three, four. However, the results display a blank list rather 
  than five things. To resolve this, we can open the developer tools by right-clicking and looking closer. It turns out that the browser adds an additional set of 
  tags while constructing the DOM tree.

HTML Attributes
- HTML is a complex language that offers additional capabilities through attributes, which add power to any element. Some attributes are specific to specific elements, like the daytime attribute, which is only 
  used with the time element. Some attributes work with multiple elements but not all, such as images and videos.
- Global attributes in HTML, such as the class attribute, are highly useful for assigning a reusable name to any element, which can be styled using CSS for all elements sharing that class. These attributes are 
  essential for creating visually appealing and functional websites.
- The ID attribute is a popular attribute in HTML, similar to the class attribute, but unique names can only be used once on an entire HTML page. It is useful for CSS targeting but not for JavaScript or targeted 
  links. However, IDs are useful for addressing specific elements in JavaScript or linked elements. Class and ID attributes provide a way to name HTML elements and reference them in other parts of the code stack.
- HTML offers various attributes that enhance user interaction and provide hooks into browser power. For example, the "content editable" attribute allows visitors to edit content on a web page, while the "lang" 
  attribute specifies the language of the content using a short language code. The "dir" attribute indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left 
  scripts. These attributes are considered Global Attributes and can be used on any HTML element.
- The four most important Global Attributes are "class," "id," "lang," and "dir." A comprehensive list of all Global Attributes can be found on MDM web docs. Feel free to use these attributes on any element of 
  your web pages.

ARIA Roles
- ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. The goal is to rely on proper HTML elements to convey the 
  right message about the content's meaning, without needing ARIA Roles. However, reality does not always align with ideals, and sometimes compromises have to be made in the code. It becomes a big problem if these 
  compromises make a website difficult or impossible for people with disabilities to use it. In fact, it is against the law in many places to have an inaccessible website for people with disabilities.
- You see,HTML even has a significant impact on human rights. ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers 
  to ensure a website is fully accessible. ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex 
  interface in an app.
- Here is an example that demonstrates the need for ARIA Roles. Experiment with CSS Grid to push the boundaries of graphic design on the web. Take the headline "hello world" and use CSS layout to place each letter 
  in a separate cell on the grid. To achieve this, wrap each letter in an HTML element that targets them individually with CSS.
- Unfortunately, this approach creates a poor experience for screen reader users. Instead of reading "hello world" as intended, the screen reader will spell out each letter: H-E-L-L-O-W-O-R-L-D. You can observe 
  this behavior in the Firefox Accessibility Inspector by opening the developer tools and navigating to the Accessibility tab.
- The accessibility tree, a component of the DOM tree, is essential for assistive devices like screen readers to improve user experience. It treats content as separate text containers, potentially causing poor 
  reading experiences.
- To address this, ARIA can be used. By adding an ARIA label to the HTML, specifying the text the screen reader will read, and hiding individual letters within a div element, the accessibility tree is removed 
  while keeping them in the DOM tree. This results in a clear heading of "hello world."
- ARIA is a powerful tool that significantly enhances web accessibility, especially useful for teams working with semantic HTML 
  or complex application interfaces. ARIA Roles provide the necessary tools to make a site accessible to everyone, making it a valuable resource for those working with semantic HTML or complex application 
  interfaces.

  

