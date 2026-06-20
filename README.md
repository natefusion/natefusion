# About Me
Hello, my name is Nathan. I'm a computer science graduate student at Florida Polytechnic University and a software engineer at [Fadr](https://fadr.com).

I also have a personal website: [https://ncp.one](https://ncp.one). It mostly exists as a way to experiment with visual design, maybe I will write something one day.

# Projects
Personal projects that I especially like.

- [website](https://github.com/natefusion/website)
  - Source for [https://ncp.one](https://ncp.one)
  - Includes custom static site generator that enables me to write in mostly plain HTML with some custom tags that are expanded into real HTML at build time
  - Site builds are committed as well to make it fully self contained.
- [pid_controller](https://github.com/natefusion/pid_controller)
  - A mediocre quadcopter simulation using rigid-body physics in Odin and Raylib. I created this project to help me understand how pid controllers work in order to make a real quadcopter fly ⬇️ (it never did).
- [SECON26](https://github.com/natefusion/SECON26)
  - Code for a quadcopter and ground bot designed by the Florida Poly Robotics and Automation Society for IEEE Southeastcon 2026.
- [finite-automata](https://github.com/natefusion/finite-automata/blob/master/fa.lisp)
  - Regular expression parser and finite automata simulator. Includes code to display finite automata graphs (with labels) with Graphviz.
- [midi_controller](https://github.com/natefusion/midi_controller)
  - Interprets data from a linear hall effect sensor as a MIDI keyboard press + velocity. Paired with an itty-bitty custom keyboard with magnets on the bottom for the sensors to read.
- [cl-matrix](https://github.com/natefusion/cl-matrix)
  - Includes matrix operations that display unevaluated subexpressions (instead of the resulting number) that result from operations (determinant, inverse, solving systems of linear equations, ...)
  - Also includes half of a computer algebra system. It can receive expressions in regular math notation ("a+b*c") and transform the expressions into a simpler form. Also supports symbolic differentiation and indefinite integration (integration only sort of works).
    - (prefix->infix (diff 'z (notation "sin(3 z + z^2) / (6 - z^4)^3"))) => (((((6 - (Z ^ 4)) ^ 3) * ((COS ((3 * Z) + (Z ^ 2))) * (3 + ((2 * (Z ^ 2)) / Z)))) - ((3 * ((SIN ((3 * Z) + (Z ^ 2))) * (((6 - (Z ^ 4)) ^ 3) * (0 - ((4 * (Z ^ 4)) / Z))))) / (6 - (Z ^ 4)))) / ((6 - (Z ^ 4)) ^ 6))
- [boolean](https://github.com/natefusion/boolean)
  - Can parse boolean expressions into Common Lisp code using a math-like notation
    - (notate "a+b*c") => (OR A (AND B C))
  - Includes an "automatic" term rewriter intended for boolean algebra simplification
    - (defaxiom or-commutative "x+y" "y+x") -> (or-commutative (OR A (AND B C))) => (OR (AND B C) A)
- [c-micrograd](https://github.com/natefusion/c-micrograd), [micrograd](https://github.com/natefusion/micrograd)
  - Inspired from [Andrej Karpathy's micrograd](https://github.com/karpathy/micrograd)
  - C and Common Lisp implementation
  - C version experiments with arena allocation. Includes a value oriented interface and a tensor oriented interface that is intended to be as easy to use as pytorch (pipedream). Computational graphs can be viewed with Graphviz.
  - Common Lisp version includes web interface that displays the computational graph
- [subsynth](https://github.com/natefusion/subsynth)
  - Subtractive synthesizer made in C with Raylib
  - Includes envelopes and oscillators that interact in various ways
- [forth](https://github.com/natefusion/forth)
  - Forth interpreter in Common Lisp
- [chip8](https://github.com/natefusion/chip8)
  - Chip8 emulator, assembly language and disassembler in Common Lisp

# Other interests
- I play the trumpet 🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺🎺
