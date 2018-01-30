# Element.offsetHeight
offsetHeight = height + padding + border + horizontal scrollbar (if 
present)

* it doesn't include the height of pseduo-elements such as :before or
:after.

* round the value to integer.

# Element.clientHeight
clientHeight = height + padding - height of horizontal scrollbar (if present)

* round the value to integer.

# Element.scrollHeight
scrollHeight = height + padding - height of horizontal scrollbar (if
present)

* the height is mesured in the same way as the clientHeight.

* it can also include the pseduo-elements such as :before or :after.

* if the element's content can fit without a need for vertical scrollbar, its scrollHeight is equal to clientHeight.
