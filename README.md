# Tripline

Tripline is designed to allow for a user to make any variable into a type of interrupt. This is done by allowing the user to define triggers that are linked to void functions so that anytime the variable is set to that value the void function would activate. This system also has different levels of interrupts so that when the highest level interrupt is occuring a lower interrupt can't on the function. This can help prevent infinite loops within when an interrupt occurs.

# Currently Functioning

Tripline should be fully functioning, however inorder to compile the code one needs iochannel for pawlib. A library designed by my associates at MousePaw media.
