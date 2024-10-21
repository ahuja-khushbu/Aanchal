#viva questions on css
Here is the set of viva questions in LaTeX format based on the CSS content provided in the PDF:

```latex
# CSS Viva Questions and Answers

## 1. **What is CSS and why is it used?**
\textbf{Answer:} CSS (Cascading Style Sheets) is used to control the style and layout of web pages. It allows for styling HTML elements by setting various properties such as color, font, and spacing. It is commonly used to improve the presentation of web pages, making them more visually appealing and easier to maintain.

## 2. **What are the different types of CSS?**
\textbf{Answer:} 
There are three main types of CSS:
\begin{itemize}
    \item Inline CSS: Applied directly to a specific HTML element using the `style` attribute.
    \item Internal CSS: Written within a `<style>` tag inside the `<head>` section of an HTML document.
    \item External CSS: Stored in a separate CSS file and linked to the HTML document via the `<link>` tag.
\end{itemize}

## 3. **What is a CSS selector?**
\textbf{Answer:} A CSS selector is used to target HTML elements for styling. It is a pattern used to select the element(s) you want to apply the style to. Examples of selectors include:
\begin{itemize}
    \item Tag selector: Targets elements by their HTML tag name, e.g., `p`, `h1`.
    \item Class selector: Targets elements with a specific class using a period (`.`) followed by the class name, e.g., `.classname`.
    \item ID selector: Targets an element with a specific ID using the hash symbol (`#`), e.g., `#elementID`.
\end{itemize}

## 4. **What are CSS properties and how do they work?**
\textbf{Answer:} CSS properties define the styles that can be applied to HTML elements. Each property has a value that specifies how the selected element should be styled. For example:
\begin{itemize}
    \item `color`: Sets the color of text.
    \item `background-color`: Specifies the background color of an element.
    \item `font-size`: Sets the size of the text.
\end{itemize}

## 5. **What is the box model in CSS?**
\textbf{Answer:} The CSS box model describes how elements are displayed on a webpage, including their padding, borders, and margins. It consists of:
\begin{itemize}
    \item Content: The actual content of the box (e.g., text, images).
    \item Padding: The space between the content and the border.
    \item Border: The line around the padding.
    \item Margin: The space outside the border between this element and others.
\end{itemize}

## 6. **What is the difference between `padding` and `margin`?**
\textbf{Answer:} 
\begin{itemize}
    \item \textbf{Padding}: The space between the content of the element and its border.
    \item \textbf{Margin}: The space outside the element's border, separating it from other elements.
\end{itemize}

## 7. **Explain the concept of specificity in CSS.**
\textbf{Answer:} Specificity determines which CSS rule is applied when multiple rules target the same element. It is calculated based on the type of selectors used. The hierarchy is as follows:
\begin{itemize}
    \item Inline styles (`style` attribute): Highest specificity.
    \item IDs: Higher specificity than classes.
    \item Classes, attributes, and pseudo-classes: Higher specificity than elements.
    \item Elements and pseudo-elements: Lowest specificity.
\end{itemize}

## 8. **What are pseudo-classes in CSS?**
\textbf{Answer:} Pseudo-classes are used to define the special state of an element. They target elements based on their state or position in the document. Some examples include:
\begin{itemize}
    \item `:hover`: Styles the element when the user hovers over it.
    \item `:first-child`: Styles the first child of a parent element.
    \item `:nth-child(n)`: Styles the nth child of a parent element.
\end{itemize}

## 9. **What is the difference between `absolute`, `relative`, and `fixed` positioning in CSS?**
\textbf{Answer:}
\begin{itemize}
    \item \textbf{Relative}: Positioned relative to its normal position in the document flow.
    \item \textbf{Absolute}: Positioned relative to its closest positioned ancestor (or to the initial containing block if none exists).
    \item \textbf{Fixed}: Positioned relative to the browser window, so it stays in place when the page is scrolled.
\end{itemize}

## 10. **What are media queries and how are they used in responsive design?**
\textbf{Answer:} Media queries allow for the application of different styles based on the characteristics of the user's device, such as screen width, height, or orientation. They are a core part of responsive design, enabling web pages to adapt to different screen sizes. Example:
```css
@media screen and (max-width: 768px) {
    body {
        background-color: lightblue;
    }
}
```

---

## License
This document is licensed under the MIT License.
```

This LaTeX code can be used to generate a README file for the CSS viva questions. Let me know if you need further customization or additional topics.