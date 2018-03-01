## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
It represents the value parameter. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
This does not work, because there is no  path specified in routes.

3. What type of request did your browser just perform?
a GET request

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:300/teachers

5. Why does `localhost:3000/teachers` work now?
It works because the route is specified from CREATE, so you can only get to this url when you press the create button 