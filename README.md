# Incorrect use of innerHTML to retrieve text content

This example demonstrates a common mistake when working with HTML: using `innerHTML` to retrieve the plain text content of an element.  `innerHTML` returns the HTML content, which might include HTML tags, whereas `textContent` returns only the plain text.  The solution shows the correct approach using `textContent`.

## Bug
The bug lies in the JavaScript code where `innerHTML` is used to get the text content of a div element. This returns the HTML content along with the text making the retrieval of the text more difficult.

## Solution
The solution uses `textContent` instead of `innerHTML` to retrieve only the text content of the element.