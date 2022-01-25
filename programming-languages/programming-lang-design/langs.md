# Koka(Ref. talk used here: https://www.youtube.com/watch?v=6OFhD_mHtKA):

- Disclaimer: I have tried my best to understand stuff, I maybe turn out to be the person who most understood it in the most wrong way, if you think so, please correct me.

- So koka works completely on concept of effects and their handlers, some examples of effects are emit(as in like it will emit a value), then ask(i.e. it will ask for a value)
- And these effects are transformed form one to another
- Like an exception effect can be converted to a string effect
- data is seperate from effects(effects are not even near classes)
- Remember this is a functional language which aims to
- It mainly aims to provide clear effect to effect transformation which can be translated to algebraic forms
- So effects are of different type there are function effects then there are value effects
