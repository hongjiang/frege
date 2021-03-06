What is Frege?
==============

Frege is a [non-strict](http://en.wikipedia.org/wiki/Non-strict_programming_language), 
pure functional programming language in the spirit of Haskell. 
It enjoys a strong static type system with type inference. 
Higher rank types are supported, though type annotations are required for that.

Frege programs are compiled to Java and run in a JVM. Existing Java Classes and Methods can be used seamlessly from Frege.

The Frege programming language is named after and in honor of Gottlob Frege. (This is surprisingly hard for english speakers to pronounce, but [you can use this translator page](http://translate.google.de/#de/en/Frege) to get it right. Just click the audio symbol in the left (german) part.)

Motivation
----------

There have been attempts to [port Haskell to the JVM](http://www.haskell.org/haskellwiki/GHC/FAQ#Why_isn.27t_GHC_available_for_.NET_or_on_the_JVM.3F), though said projects seem failed or stuck. The common wisdom suggests that it is not easily possible.

Frege is thought as a substitute for this missing GHC port. 
While not derived from any existing Haskell implementation, it is more or less equivalent to Haskell 2010. 
Please see the [wiki page that details the differences](https://github.com/Frege/frege/wiki/Differences-between-Frege-and-Haskell).

Project State
-------------

The compiler, an Eclipse plugin and a provisional version of the documentation can be [downloaded](https://github.com/Frege/frege/releases). 
Note that Frege requires JDK 7 to compile and run programs.

The compiler and the documentation tool are quite stable, the documentation provisional and the library is evolving. 
It already supports important parts of the Haskell 2010 standard library.

See the [Getting Started](https://github.com/Frege/frege/wiki/Getting-Started) page for 
getting started at the command-line or read the [Eclipse plugin](https://github.com/Frege/eclipse-plugin) page.

There is also an [interpreter (REPL)](https://github.com/Frege/frege-repl). 
An online version of the REPL is available [here](http://try.frege-lang.org/).

Contributions
-------------

If you are interested in contributing, here are some hot topics:

* write Frege code to support more of the Java API
* port Haskell libraries or tools
* open issues on the Issues page if you find bugs, errors in documentation, etc.
* help make Frege popular by writing code for projects like Rosetta Stone or Computer Language Shootout.

Contact
-------

You can contact the project members through the
[discussion group](http://groups.google.com/group/frege-programming-language)
devoted to the Frege programming language.
Specific programming problems are best solved on
[Stack Overflow](http://stackoverflow.com/questions/tagged/frege),
we check questions tagged "frege" on a regular basis.

If you find a bug or have an idea for enhancements, please let us know by opening an issue in the issue tracker.
(You'll need a GitHub account to do this.)

Please understand that the issue tracker is neither a discussion forum nor a place to ask questions.

Links
----

[Frege Wiki](https://github.com/Frege/frege/wiki/_pages)

[Author's Blog](http://fregepl.blogspot.com/)

[Nightly Builds](http://jenkins.jamestastic.com/job/frege/)

[Online Docs (Runtime Javadoc)](http://www.frege-lang.org/doc/index.html)

[Online Docs (Frege)](http://www.frege-lang.org/doc/index.html)
