# css-animations-practice
Notes on each topic - Personal recall, not meant to help others. 

transition-timing-function: how the change in the property will occur

Options:

- ease: the change starts slow then goes faster then finishes slow

- linear: constant speed the entire duration 

- ease-in: starts slow then ends fast (Going into the to the track, starts slow then goes fast)

- ease-out: starts fast then ends slow (Out of the track, fast at first but then slows for the pit)

- ease-in-out: the same as ease

In order to set the examples, we add transition-property: translate() which defines that we want to move the elements for our transition, we also set the transform-duration: 3s which gives a duration. We add the transition-timing-function then finally we provide an action to the hover event. This is done by using transform: translate(900px, 0px) with the first argument being the x axis and the second being the y

Another useful property is the transition delay property which works exactly as you would expect. It delays the start of the transition. transition-delay: 1s would mean that the transiton waits a second before beginning. 

transition-property (the css that is animated) can take multiple arguments and also has an option for all. 