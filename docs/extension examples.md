# Extension examples

PyMdown extensions includes some extensions, 3 of which replaces default markdown extensions.

Some extensions:
* Arithmatex
* B64
* BetterEm
* Caret
* Critic
* Details
* Emoji
* EscapeAll
* Extra
* ExtraRawHTML
* Highlight
* InlineHilite
* Keys
* MagicLink
* Mark
* PathConverter
* ProgressBar
* SmartSymols
* Snippets
* StripHTML
* SuperFences
* Tasklist
* Tilde

See https://facelessuser.github.io/pymdown-extensions/

## Arithmatex

idk how to use this. I might need MathJax.

$p(x|y) = \frac{p(y|x)p(x)}{p(y)}$, \(p(x|y) = \frac{p(y|x)p(x)}{p(y)}\)

$$
E(\mathbf{v}, \mathbf{h}) = -\sum_{i,j}w_{ij}v_i h_j - \sum_i b_i v_i - \sum_j c_j h_j
$$

Here are some non-extensions:
h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x


## SuperFences

Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow

## Tasklist

Task List

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3


## Tilde (subscript)

~~something~~

text~a\ subscript~

## Caret (superscript)

H^2^0

text^a\ superscript^

^^Insert me^^


## Progress Bar

[=0% "0%"]
[=5% "5%"]
[=25% "25%"]
[=45% "45%"]
[=65% "65%"]
[=85% "85%"]
[=100% "100%"]

## Details

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.

??? warning classes
    Content.
	
??? success 
    Content.	

## magiclink

This text would not be hyperlinks without this extension:

https://plasmatech8.github.io/Python-Mkdocs-Demo/

http://127.0.0.1:8000/extension%20examples/
