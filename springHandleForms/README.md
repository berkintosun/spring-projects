https://spring.io/guides/gs/handling-form-submission/

The Greeting is a @ModelAttribute so it is bound to the incoming form content, and also the submitted data can be rendered in the result view by referring to it by name (the name of the method parameter by default, so "greeting" in this case).
