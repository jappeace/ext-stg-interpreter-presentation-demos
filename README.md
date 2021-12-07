# External STG interpreter presentation demos

Demo programs of the presentation

## Why and How the External STG Interpreter is Useful

**abstract**  
*The external STG interpreter is a from scratch implementation of the STG machine in Haskell.
Currently it supports almost all GHC primops and RTS features.
It can run real world Haskell programs that were compiled with GHC Whole Program Compiler (GHC-WPC).
GHC-WPC is a GHC fork that exports the whole program STG IR.
The external STG interpreter is an excellent tool to study the runtime behaviour of Haskell programs, i.e. it can run/interpret GHC or Pandoc.
The implementation of the interpreter is in plain simple Haskell, so it makes compiler backend and tooling development approachable for everyone.
It already has a programmable debugger which supports step-by-step evaluation, breakpoints and execution region based inspection.
It also can export the whole program memory state and call-graphs to files for further investigation.
These features make it easy to find a memory leak or to identify a performance bottleneck in a large real world Haskell application.*

[![Watch the video](https://img.youtube.com/vi/wt6iCgYmVGA/hqdefault.jpg)](https://youtu.be/wt6iCgYmVGA)

[youtube video](https://www.youtube.com/watch?v=wt6iCgYmVGA)  
[slides](https://docs.google.com/presentation/d/1Lmfpwtx_7TbIAGYnSE0HqkawRu75y2GGwbObuu0xYPY/edit#slide=id.p)


## Build & Run

1. Watch the presentation
2. Install GHC-WPC: https://github.com/grin-compiler/ghc-whole-program-compiler-project#usage
3. Clone this repository
4. Reproduce the demo part of the presentation: https://youtu.be/wt6iCgYmVGA?t=2054
