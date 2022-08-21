Reason for Assignment: To review basic HTML syntax and semantics, including a basic form and table.

Populate three HTML files with the specified elements and content. Styling is optional.

All html pages must be valid (according to the validator) and meet the specifications for elements, attributes and content.

## 1-1: [signup.html](signup.html)

0. Valid and file created. The HTML must be valid according to html-validate.
1. A `form` element is present with 2 `input` elements: one of type email for email, and one input of type 'checkbox', and a required submit button with the text "Submit". 
2. Add a password input of type "password"
3. Each input element must be wrapped in a paragraph tag.
4. Each input element should have a corresponding `label`, which is associated **explicitly* (using the `for` attribute) with the `id`s: "email", "signup", "passowrd". The label for the checkbox should be exactly "Sign up for our newsletter". Do not include the input as a child of the label in this case.
5. The checkbox is set as default checked
6. Both email and password must be required.
7. The form action should send the results to "thanks.html"

## 1-2: [index.html](index.html)

0. Valid `index.html` file containing html created. The HTML must be valid according to html-validate.
1. The entire page should have a header (`h1`), with the contents "My Blog"
2. A home page that contains two posts represented as "article" elements.
3. Each article should have the class "post"
4. The posts should contain both a h2 element and one or more paragraph elements, and not be empty. The content is up to you.

## 1-3: [posts.html](posts.html)

Create a page with the header "Your Posts" with the following table:

| Title       | Summary                           | Date      | Published |
|-------------|-----------------------------------|-----------|-----------|
| New Job     | I was hired for a new position... | 9-1-2022  | False     |
| Hello World | A new version                     | 10-1-2022 | True      |

1. A header element with the text content "Your Posts"
2. A table element
3. A header row with the columns "Title", "Summary", "Date" and "Published"
4. Two content rows, formatted using appropriate elements:

