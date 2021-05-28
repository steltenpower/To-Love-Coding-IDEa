# To-Love-Coding-IDEa
I reflect on wrestling with code and code tools and imagine functionality that could've helped
<img src="https://repository-images.githubusercontent.com/322005861/4432c680-5848-11eb-8940-14545437ca82">

Some thoughts that didn't get their own repo (yet), like
[MultiTouchFlowBasedProgramming](https://github.com/steltenpower/MultiTouchFlowBasedProgramming)
and
[TangibleJigsawCoding](https://github.com/steltenpower/TangibleJigsawCoding)
and
[TableFilteringByDataViz](https://github.com/steltenpower/TableFilteringByDataViz)
and
[DataSetAndSketch](https://github.com/steltenpower/DataSetAndSketch)
) are piled up below:

https://twitter.com/steltenpower/status/1337191471116677120
If programming is a lot of sticking one thing into another (assigning, passing,...) and debugging a lot of finding where it doesn't really fit, shouldn't every IDE have at least the option to visualize a specific line in some jigsaw-y way? types, structures, sizes


https://twitter.com/steltenpower/status/1338472142577561602
Anybody ever saw a thread (as in wire) used to visualize the route your machine takes through your code?
Also as IDE functionality?
Bonus: being able to move along that thread and see reachable data change


https://twitter.com/steltenpower/status/1328827432745504779
I never liked the code or no-code discussion. I want the possibility of having multiple synchronized representations (varying mixes of text and visualisation). I'm very interested in your approach.

Especially for big screens maybe have the rich views of what a user is working on surrounded by smart-updating pallettes of interactive visual examples to swipe in there? Building LEGO or electronics people often seem to collect what they sort of need out of the bigger pile 1st

And for those reading this and thinking, but how is this different from you average search result: Make Image search your default search for a while and of course watch "The humane representation of thought" :-)

> We couldn't agree more! We'll be showing off even more of that in upcoming previews.

If you ever want to talk to somebody with very strong love/hate relationship with programming, knowing many concepts (and having thought about how/where these concepts should be made interactive easier), also touched on a dozen, but too little routine for much expert blindness


https://twitter.com/steltenpower/status/1337354061608267778

>love coding?

-programming!

>same

-No, code among synched interactive visualizations

>choose!

-42"

>Keyb, mouse?

- plus cam, pen, mic, …

>Language?

-data structure and interface/workflow

>R(stats),Python,JavaScript,Golang?

Easier to combine/switch. And with AI you should be able to use your own not-fully-consistent pseudo-code-of-the-day and have "did you mean"-options in the actual languages your aiming at show up.

> Did you just say multiple languages?

As every language has its advantages

> But how do they work together?

Communicate over standard interfaces with standardized data formats. Share in-memory variables. Share function definitions via Wikifunctions. Have WASM-based implementations cooperating within notebooks in your web browser

>debug?

-much less (pain), more pair, taking advantage of multi-cursor, and rich person-to-person interaction beyond videochat.

>docs/examples?

-just appear

>But then anyone can!

-Would be nice, but can anyone literate write good stories?

>Shakespeare great at English

-What about Mandarin?

>what?

-there are so many languages, each with own strengths for expressing thought

>THROW-AWAY GESTURE

-exactly

>ANGRY LOOK

-maybe paint that

>Vague, be more concrete

-ingredients exist, some for decades

>which?

-Look at design tools for many things other than code, like 3D and electronics, formulas/diagrams in physics, knitting, etc. , Scratch, blockly, dataviz

>Code and data are different

-flavours indeed, rich

>Links?

- https://vimeo.com/115154289 to start

>More?

- anything @worrydream @ibdknox @observablehq, search from there

>More?

-Look at many experts (work) out there

>More?

-If you insist, I can screen share for a bit

>More?

-Will cost you

>How much?

-Smarter-than-me colleagues

>How do you get to all this?

-Using tools I love and hate

>Frustration?

-In a constant mix with inspiration and creativity

>You need to learn your tools more?

-Certainly. Better when tools are more learnable while working. Context an important word

>Latest inspir/frustr?

-Rstudio


https://twitter.com/steltenpower/status/1339029789567578113
Dear IDEs:
Please use Levenshtein distance to warn me when the slightest typo in a variable/function name could turn it into another available one (possibly defined in a different file).
.
Dear IDEs:
For every function I use show (on hover?) a list of other available functions with similar descriptions.
In R for example it might help you find where you have used length( ) instead of nrow

https://twitter.com/steltenpower/status/1339206125854593024
@semanticarts I still point many to your datacentricmanifesto, as their thoughts start on applications. Nowadays I'm also thinking many programming tools should put data front and center more; A carpenter or sculptor is not focusing on their tools primarily either. Thoughts?

Have a view option to show the namespace of everything, what package/library/file things come from

Temporarily shape formulas (function calls, regular expressions, etc.) as icicle diagrams to show the structure. Replace parts by a variable by dragging it out and that part will automatically be assigned to that variable above the formula. You can also drag it (back) in. And make it easy to switch from traditional passing-into-a-function-as-parameters and the alternative shape of the equivalent with pipe (e.g. in Tidyverse and nowadays also base R)

Text has many more options to distinguish things than just color, which probably can also help code readability; size, font, whatever, depending your focus of the moment.

Having sensitive or big, or complex data (who doesn't nowadays) makes it harder to ask for help. Some things that could help when made crazy easy in some GUI:
- Scramble data (keeps the structure, order and links, but removes the data)
- Synthesize data (throw in an empty data structure, set a few parameters)
- Sample (how much do you have, how much do you need, how should it be distributed)
- Visualize some standard data structures, for example with [TableFilteringByDataViz](https://github.com/steltenpower/TableFilteringByDataViz)
- Some/same GUI to help put constraints (regex, other) on variables. Also learn from frictionless, tidy, FAIR, Linked data.
