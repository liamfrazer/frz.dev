2022-07-25 17:42
# 17 - Appendix - How JavaScript Works
---

## JavaScript Engine
* Google maps required a lot of power, all previous engines would make Google Maps extremly slow
* V8 was built for Google Maps to run way faster than previous engines

## Inside the engine
* JavaScript file > Parser > AST > Interpreter >
* If everyone created their own JavaScript engine, it would be chaos
* ECMAScript was created to set standards

## Interpreter & Compiler
*  Two ways of translating to machine language

## Interpreter
* Translate and read the files
* The translation happens line by line on the fly
* Taking a set of instructions and return an answer with that code
* Quick to get up and running, no conversion to another language and no extra steps
* Interpreters are a natural fit for JavaScript as originally created for the browser
* Running a lot of JavaScript will get slower & slower
* If in a loop, it can get really really slow, this is where the compiler helps

## Compiler
* This doesn't translate on the fly
* This works ahead of time, and compiles down to a language that the machine understands
* Takes one pass through the code and tries to understand it
* Takes the program > writes a program in a new language
* The language it spits out, if we interpt it, it's going to create the same results as the Interpreter
* The compiler understands what we want to do, to take it into something else such as a lower level language
* Compiler takes a little bit of extra time to review code & spit out into another language
* If the compiler sees loops, it can actually simplify the code and replace the function with a value as an example
* Compilers optimise the code

## JIT Compiler
* Combination of a Interpreter & Compiler

## Inside the V8 Engine
* 



---
## References
[[frz.dev/docs/Languages/JavaScript/index]]
[[frz.dev/docs/Runtimes/Node.js/index]]
[[frz.dev/docs/Courses/Complete Node.js Developer/index]]