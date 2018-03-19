# HTML-Forms
HTML Forms

-Each form is wrapped with the <form></form> element.
-You cannot nest form elements within form elements as that is invalid html.

-The form element has an action and method attribute.
-The action is the location of the script that processes the data.
-The Method could be POST or GET.  
    1) POST just posts the data to the server. You don't see anything in your URL when this happens.
    2) GET will create a query string appended to the URL i.e data is sent inside the URL.

-The 'name' attribute in input elements are used for server-side data processing.

-A textarea is not self-closing like an input element, so it needs a closing tag.

BUTTON
-we create a button with type="submit". But there are two other types; "reset" and "button".
-Reset type will automatically clear all form data when it is clicked.
-Button type has no default behaviour, and used in combination with JavaScript.
-Submit type's default behaviour is to send the data over to the server for processing.

USING LABELS
-Using the 'for' attribute, will link the label to the appropriate input via the id.

FIELDSETS AND LEGENDS
-certain inputs (form controls) belong together and can be logically grouped. This is what fieldsets are used for. They group them together, but also add some spacing to help make this more visually obvious.
-We can then label these fieldsets using legends.