To implement the functionality, I will add a function that takes value inputted into the textarea(textInput) and the value of the radio button (conversionMode).

This function will check the value of the conversionMode and transform the textInput accordingly. but it will first check if there

this function will be called by the eventListener added to the button.

```
function transformText:
  if !textInput:
    return 'Please enter some string value'
  else if conversionMode == 'uppercase':
    return textInput.toUpperCase()
  else
    return textInput.toLowerCase()
```