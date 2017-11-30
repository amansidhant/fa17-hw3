## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?




Go to `localhost:3000/teachers` in your browser; why does this not work?

This does not work because a GET request to the page has not been defined in the routes.rb file. Only a
POST reguest has been defined.

What type of request did your browser just perform?

The browser unsuccessfully performed a GET request. It was trying to retrieved the requested URL but there
was no GET reuquest defined. 

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

'localhost:3000/teachers'.

Why does `localhost:3000/teachers` work now?

The browser is performs a POST request because it is trying to modify the values and the data stored.
A POST request is also defined in the routes.rb file, so it all works now.
