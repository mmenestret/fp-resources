# Curated list of great functional programming resources (mainly Scala or Haskell based)
![functional programming path](https://cdn-images-1.medium.com/max/800/1*AM83LP9sGGjIul3c5hIsWg.png)

## Categories

* [Functional programming patterns](#fp-patterns)
* [Types](#types)
* [Functional Effects](#effects)
* [Semigroup / Monoid](#semigroup-monoid)
* [Tagless Final / MTL](#taglessfinal-mtl)
* [Monad stack](#monad-stack)
* [Free Monad](#free-monad)
* [Typeclass](#typeclass)
* [Concurrency](#concurrency)
* [Optics](#optics)
* [Recursion Schemes](#recursion-schemes)
* [Theory](#theory)
* [Academic papers](#academic-papers)
* [Lectures](#lectures)
* [Blogs](#blogs)
* [Books](#books)
* [Chat rooms](#chat-rooms)
* [Newsletters](#newsletters)
* [Podcasts](#podcasts)
* [Repositories](#repositories)

<a name="fp-patterns"></a>
## Functional Programming Patterns

### Talks

* [Functional Programming is Terrible - Rúnar Bjarnason](https://www.youtube.com/watch?v=hzf3hTUKk8U)
    * _Tail Recursion, Trampolining, Higher Kinded Types, Benefits of Functional Programming_

* [What Referential Transparency can do for you - Luka Jacobowitz](https://www.youtube.com/watch?v=X-cEGEJMx_4&feature=youtu.be&t=228)
    * _Functional Programming Design, Referential Transparency and side-effects_

* [Functional Design Patterns - Scott Wlaschin](https://www.youtube.com/watch?v=srQt1NAHYC0)
    * _Functional design patterns from partial application to Monads and Monoids_

* [FP to the Max - John De Goes](https://www.youtube.com/watch?v=sxudIMiOo68)
    * _Live coding session on Functional Programming design and techniques_

* [Constraints Liberate, Liberties Constrain — Runar Bjarnason](https://www.youtube.com/watch?v=GqmsQeSzMdw)
    * _Functional Programming design_
    
* [May Your Data Ever Be Coherent](https://www.youtube.com/watch?v=gVXt1RG_yN0)
    * _Functional Programming design_

* [Functional Patterns in Domain Modeling — Debasish Ghosh](https://www.youtube.com/watch?v=U0Rk9Knq8Vk)
    * _Functional domain modeling_

* [Thinking Functionally](https://www.youtube.com/watch?v=-KA3BSdqYug)
    * _Live-refactor concurrent imperative program with ZIO_

### Articles

* [Anatomy of functional programming](http://geekocephale.com/blog/2018/10/08/fp)
    * _Functional Programming design_

* [Data Modeling in FP vs OOP](http://degoes.net/articles/fp-vs-oop-part1)
    * _Functional Programming design_

* [Scala best practices](https://nrinaudo.github.io/scala-best-practices/index.html)
    * _List of good practice in Scala_

* [Trampolining and stack safety in Scala](https://medium.com/@olxc/trampolining-and-stack-safety-in-scala-d8e86474ddfa)
    * _Trampolining, tail call elimination_

* [Algebraic API Design - Types, Functions, Properties](https://typelevel.org/blog/2019/02/06/algebraic-api-design.html)
    * _Types, Functions, Properties_

* [Anatomy of an algebra](http://geekocephale.com/blog/2018/10/06/algebras)
    * _Algebraic Data Type (ADT)_

<a name="types"></a>
## Types

### Talks

* [Why do Functional Programmers always talk about Algebra(s)?](https://www.youtube.com/watch?v=s2ay9nEW3ak)
    * _Domain Algebra, Algebraic structure_

* [Type Members vs Type Parameters](https://www.youtube.com/watch?v=R8GksuRw3VI)
    * _How to choose between Type Members and Type Parameters_

### Articles

* [Scala’s Types of Types](http://ktoso.github.io/scala-types-of-types)
    * _Scala Type System_

* [Types: Never commit too early](https://www.sderosiaux.com/articles/2018/08/15/types-never-commit-too-early-part1)
    * _Function encodings_

* [Kinds of types in Scala](https://kubuszok.com/2018/kinds-of-types-in-scala-part-1/)
    * _Type Theory in Scala_

* [From Type Theory to Haskell in 10 Minutes](https://www.stackbuilders.com/news/from-type-theory-to-haskell-in-10-minutes) [**Haskell**]
    * _Type Theory in Haskell_

* [Practical Type Safety](http://www.lihaoyi.com/post/StrategicScalaStylePracticalTypeSafety.html)
    * _Using Scala in a Type Safe way_

* [Functional APIs: an OOP approach to FP](https://blog.hablapps.com/2017/06/26/functional-apis-an-oop-approach-to-fp/)
    * _Generalized Algebraic Data Types (GADTs)_

* [How do Algebraic Data types compare to the concept of inheritance in Object Oriented Languages ?](https://www.quora.com/How-do-Algebraic-Data-types-in-say-Haskell-compare-to-the-concept-of-inheritance-in-Object-Oriented-Languages-in-say-Java/answer/Bartosz-Milewski?share=1c2ac3a8)
    * _Algebraic Data Types (ADTs)_

<a name="effects"></a>
## Functional Effects

### Talks

* [Functional Programming with Effects - Rob Norris](https://www.youtube.com/watch?v=po3wmq4S15A)
    * _Effects and Equational Reasoning_

* [The Death of Final Tagless](https://skillsmatter.com/skillscasts/13247-scala-matters)
    * _Functional Effects, Tagless Final alternative with ZIO_

* [The Making of an IO - Daniel Spiewak](https://www.youtube.com/watch?v=g_jP47HFpWA)
    * _IO Monad with Cats Effect_
    
* [http4s: pure, typeful, functional HTTP in Scala – Ross Baker](https://www.youtube.com/watch?time_continue=1915&v=urdtmx4h5LE)
    * _IO, HTTP4s, Kleisli_
    
* [Declarative Control Flow with fs2 Stream – Fabio Labella](https://www.youtube.com/watch?v=YSN__0VEsaw)
    * _Functional Stream with fs2_

* [Regaining Control with State Monad and Friends](https://www.youtube.com/watch?v=Pgo73GfHk0U)
    * _State, StateT, IndexedState_
    
* [Michał Płachta - Fast & Functional](https://www.youtube.com/watch?v=xAhrgxUeOvY)
    * _FP design, tagless final, performance_  

* [Gabriel Volpe - Cats Effect: The IO Monad for Scala](https://www.youtube.com/watch?v=8_TWM2t97r4&t=18s)
    * _ Cats Effect, error handling, safe resource management, concurrency, parallelism_

### Articles

* [ZIO Monad, Scala's ReaderT pattern](http://degoes.net/articles/zio-environment)
    * _Functiona Effects, Tagless Final, ReaderT_

* [Effekt: Extensible Algebraic Effects in Scala](https://conf.researchr.org/event/scala-2017/scala-2017-papers-effekt-extensible-algebraic-effects-in-scala-short-paper-)
    * _Algebraic effects, Scala library Effekt_

* [Handle pattern](https://jaspervdj.be/posts/2018-03-08-handle-pattern.html) [**Haskell**]
    * _Modularize Effectful layer of medium to large scaled Haskell applications_

* [ReaderT pattern: RIO](https://www.fpcomplete.com/blog/2017/06/readert-design-pattern) [**Haskell**]
    * _Better globals with ReaderT_

* [Why Functional Programming? It's the composition](https://tech.iheart.com/why-fp-its-the-composition-f585d17b01d3)
    * _Compositions, Effects, Functor, Monad, Category Theory_

<a name="semigroup-monoid"></a>
## Semigroup / Monoid

### Talks



### Articles

* [A tale on Semirings](https://typelevel.org/blog/2018/11/02/semirings.html)
    * _Journey to Semirings through Semigroups and Monoids_

* [Anatomy of semigroups and monoids](http://geekocephale.com/blog/2018/11/06/semi-monoid)
    * _Semigroups and Monoids_

<a name="taglessfinal-mtl"></a>
## Tagless Final / MTL

### Talks

* [Advanced Tagless Final - Saying farewell to Free - Luka Jacobowitz](https://www.youtube.com/watch?v=E9iRYNuTIYA)
    * _Free Monad, Tagless Final_

* [A roadtrip with monads: from MTL, through tagless, to BIO - Paweł Szulc](https://www.youtube.com/watch?v=QM86Ab3lL20)
    * _MTL, Tagless Final, BIO_

* [Getting more mileage from your monads and MTL - Paweł Szulc](https://www.youtube.com/watch?v=knK70T4X7YE)
    * _MTL style_

* [Free monad or tagless final? How not to commit to a monad too early - Adam Warski](https://www.youtube.com/watch?v=IhVdU4Xiz2U)
    * _Live coding session on Free monads and Tagless Final_

* [Freestyle, Free & Tagless: Separation of Concerns on Steroids - Michał Płachta](https://www.youtube.com/watch?v=-4lB5EKS5Uk)
    * _Free and Tagless in a real application_

### Articles

* [Introduction to Tagless final](https://www.beyondthelines.net/programming/introduction-to-tagless-final/)
    * _Tagless Final_
* [Exploring Tagless Final pattern for extensive and readable Scala code](https://blog.scalac.io/exploring-tagless-final.html)
    * _Tagless Final_

* [Gist about Fabio Labella's on inital vs final tagless encodings](https://gist.github.com/mmenestret/0b746cfd650796a639723ee74a3de302)
    * _Tagless Final_
    
* [Testing tagless final with Discipline](https://www.iteratorshq.com/blog/tagless-with-discipline-testing-scala-code-the-right-way/)
    * _Tagless Final with the Typelevel library Discipline_

* [Structuring Functional Programs with Tagless Final](https://www.becompany.ch/en/blog/2018/06/21/tagless-final)
    * _Tagless Final_

* [Typed tagless-final interpretations: Lecture notes](http://okmij.org/ftp/tagless-final/course/index.html)
    * _Tagless Final_

* [Optimizing Tagless Final – Saying farewell to Free](https://typelevel.org/blog/2017/12/27/optimizing-final-tagless.html)
    * _Tagless Final_

* [From Object Algebras to Finally Tagless Interpreters](https://oleksandrmanzyuk.wordpress.com/2014/06/18/from-object-algebras-to-finally-tagless-interpreters-2/) [**Haskell**]
    * _Tagless Final_

* [Intro to MTL](https://typelevel.org/blog/2018/10/06/intro-to-mtl.html)
    * _MTL style_

* [Typed tagless-final interpretations](http://okmij.org/ftp/tagless-final/course/index.html) [**Haskell**]
    * _Typed Tagless Final embeddings of Domain-Specific Languages (DSLs)_
    
* [Finally Tagless - Not Quite Dead Yet](https://github.com/ncreep/bloggable-thoughts/tree/master/finally-tagless-not-quite-dead)
    * _Tagless Final, code examples_

<a name="monad-stack"></a>
## Monad stack

### Talks

* [Monad transformers down to earth - Gabriele Petronella](https://www.youtube.com/watch?v=jd5e71nFEZM)
    * _Monad Transformer_

* [The Eff monad, one monad to rule them all - Eric Torreborre](https://www.youtube.com/watch?v=KGJLeHhsZBo)
    * _Eff monad_

* [Monad Stacks or: How I Learned to Stop Worrying and Love the Free Monad – Harry Laoulakos](https://www.youtube.com/watch?v=2TDDDFGa8-0)
    * _Monad Stacks_

### Articles

* [Monad transformer variance](https://typelevel.org/blog/2018/09/29/monad-transformer-variance.html)
    * _Monad Transformer_

* [Monadic EDSLs in Scala](https://typelevel.org/blog/2016/09/21/edsls-part-1.html)
    * _(EDSLs) Embedded domain specific languages_

* [EDSLs as functions](https://typelevel.org/blog/2016/10/26/edsls-part-2.html)
    * _(EDSLs) Embedded domain specific languages_

<a name="free-monad"></a>
## Free Monad

### Talks

* [Free monad or tagless final? How not to commit to a monad too early - Adam Warski](https://www.youtube.com/watch?v=IhVdU4Xiz2U)
    * _Live coding session on Free monads and Tagless Final_

* [Freestyle, Free & Tagless: Separation of Concerns on Steroids - Michał Płachta](https://www.youtube.com/watch?v=-4lB5EKS5Uk)
    * _Free and Tagless in a real application_

* [Move Over Free Monads: Make Way for Free Applicatives! — John de Goes](https://www.youtube.com/watch?v=H28QqxO7Ihc)
    * _Free Applicatives_

* [A Year living Freely – Chris Myers](https://www.youtube.com/watch?v=rK53C-xyPWw)
    * _Free Monad_

* [Free as in Monads by Daniel Spiewak](https://www.youtube.com/watch?v=aKUQUIHRGec)
    * _Live coding session on Free Monad_

### Articles

* [Free and tagless compared - how not to commit to a monad too early](https://softwaremill.com/free-tagless-compared-how-not-to-commit-to-monad-too-early/)
    * _Free Monad and Tagless Final_

* [Free Monoids and Free Monads](http://blog.higher-order.com/blog/2013/08/20/free-monads-and-free-monoids/)
    * _Free structure with Monoids and Monads_

* [A tale of two Monads: Free vs MTL](http://tech.frontrowed.com/2017/09/28/benching-free/)
    * _Free Monad vs MTL style_

* [A tale of two Monads: Free vs MTL](https://tech.freckle.com/2017/09/28/benching-free/)
    * _Journey through Free and MTL style

<a name="typeclass"></a>
## Typeclass

### Talks

* [Mastering Typeclass Induction — Aaron Levin](https://www.youtube.com/watch?v=Nm4OIhjjA2o)
    * _Inductions and Typeclasses_ 

* [Oh, all the things you'll traverse - Luka Jacobowitz](https://www.youtube.com/watch?v=GhLqTZaix5U)
    * _Traversable Typeclass, starting with folds all the way to Monoids and Traversable Functors_
    
* [Type class, ultimate ad hoc](https://www.youtube.com/watch?v=2EdQFCP5mZ8)
    * _Parametric and ad hoc polymorphism, Typeclasses_    

### Articles

* [Anatomy of a type class](http://geekocephale.com/blog/2018/10/05/typeclasses)
    * _Typeclasses, Polymorphic functions_

* [Type classes in Scala](https://blog.scalac.io/2017/04/19/typeclasses-in-scala.html)
    * _Typeclasses_

* [Implicits, type classes, and extension methods](https://kubuszok.com/compiled/implicits-type-classes-and-extension-methods/)
    * _Implicits and Typeclasses_  

* [Typeclasses in perspective](https://diogocastro.com/blog/2018/06/17/typeclasses-in-perspective/) [**Haskell**]
    * _Typeclasses, Extensibility, Conditional implementation, Polymorphism_

* [Inheritance vs Generics vs Typeclasses in Scala](https://dev.to/jmcclell/inheritance-vs-generics-vs-typeclasses-in-scala-20op)
    * _Parametric Polymorphism (generics) and Typeclasses_

* [Typeclass counterexample](https://blog.functorial.com/posts/2015-12-06-Counterexamples.html) [**Haskell**]
    * _Typeclasses_

* [OOP vs. FP. The pursuit of extensibility](https://medium.com/virtuslab/oop-vs-fp-the-pursuit-of-extensibility-part-2-22a37a33d1a0)
    * _Typeclasses_

<a name="concurrency"></a>
## Concurrency

### Talks

* [Concurrency with Cats-effect - Michael Pilquist](https://www.youtube.com/watch?v=Gig-f_HXvLI)
    * _fiber, Cats Effects, fs2_

* [ATOMICALLY { DELETE YOUR ACTORS } - John A De Goes & Wiem Zine Elabadine](https://www.youtube.com/watch?v=d6WWmia0BPM&list=PL8NC5lCgGs6MYG0hR_ZOhQLvtoyThURka)
    * ZIO, STM, Promise, Queue and more_

### Articles



<a name="optics"></a>
## Optics

### Talks

* [Beyond Scala Lenses — Julien Truffaut](https://www.youtube.com/watch?v=6nyGVgGEKdA)
    * _Lenses_

### Articles



<a name="recursion-schemes"></a>
## Recursion schemes

### Talks

* [Pure Functional Database Programming with Fixpoint Types — Rob Norris](https://www.youtube.com/watch?v=7xSfLPD6tiQ)
    * _Fixpoint, Recursion Schemes_

* [Peeling the Banana: Recursion Schemes from First Principles - Zainab Ali](https://www.youtube.com/watch?v=XZ9nPZbaYfE)
    * _Recursion Schemes_

* [Those 10000 classes I never wrote - Valentin Kasas](https://www.youtube.com/watch?v=1TUgSaD6cCo)
    * _Hylomorphisms, Expressive Schemes_

* [Going bananas with recursion schemes for fixed point data types - Paweł Szulc](https://www.youtube.com/watch?v=IlvJnkWH6CA)
    * _Catamorphism, Fixpoint data type, Matryoshka_

### Articles

* [Recursion training](https://github.com/softwaremill/recursion-training#sources-and-resources)
    * _Resources and examples on Recursion Schemes_

<a name="theory"></a>
## Theory

### Talks

* [Propositions as Types - Philip Wadler](https://www.youtube.com/watch?v=IOiZatlZtGU)    
    * _Relation between Logic and Computation_
    
* [A History of Computation, Logic and Algebra](https://www.youtube.com/watch?v=c_nPnURW6BU)
    * _Logic, Algebra and Category Theory_

* [Crash course into category theory - Rúnar Bjarnason](https://www.youtube.com/watch?time_continue=2&v=ml5rU06z0Fk)
    * _Category Theory_

* [Category Theory for the Working Hacker - Philip Wadler](https://www.youtube.com/watch?v=V10hzjgoklA)
    * _Category Theory_

* [Category Theory - Bartosz Milewski](https://www.youtube.com/user/DrBartosz/playlists)
    * _Category Theory playlist_

* [Propositions as Types - Philip Wadler](https://www.youtube.com/watch?v=IOiZatlZtGU)    
    * _Relation between Logic and Computation_
    
* [Stephen Pimentel - Propositions as Types for Beginners in Haskell](https://www.youtube.com/watch?v=tfG7T54MhIU&index=29&t=0s&list=PL7DZ7q3nEWhzLs7nLb57N75EY4py_P7pI) [**Haskell**]
    * _Curry-Howard isomorphism_
    
* [Why a monad is a monoid in the category of endofunctors](https://www.youtube.com/watch?v=pvTycwaAmLo)
    * _Functor, Natural Transformation, Bifunctor, Monoidal Category, Monoid, Monad_

### Articles

* [Proof and types](http://www.paultaylor.eu/~pt/stable/prot.pdf)
    * _Type Theory_

* [Category theory and programming](http://yogsototh.github.io/Category-Theory-Presentation/categories.html)
    * _Category theory_

* [Category theory material](https://www.logicmatters.net/categories/)
    * _Category theory_

* [Sequent calculus tutorial](http://logitext.mit.edu/logitext.fcgi/tutorial)
    * _Category theory_

* [A History of Computation, Logic and Algebra](https://pron.github.io/computation-logic-algebra)
    * _Logic, Algebra and Category Theory_

* [Anatomy of functors and category theory](http://geekocephale.com/blog/2019/02/16/functors-cat-theory)
    * _Functors and Category Theory_

* [Why do monads matter ?](https://cdsmith.wordpress.com/2012/04/18/why-do-monads-matter/)
    * _Monad and Category Theory_

<a name="academic-papers"></a>
## Academic papers

* [Theorems for Free! - P. Wadler](http://ttic.uchicago.edu/~dreyer/course/papers/wadler.pdf)
    * _Polymorphic function, Abstraction Theorem_

* [Propositions as types - P. Wadler](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)
    * _Type Theory, Programming Language_

* [Freer Monads, More Extensible Effects](http://okmij.org/ftp/Haskell/extensible/more.pdf) [**Haskell**]
    * _Extensible Effects_

* [Data types a la carte](http://www.cs.ru.nl/~W.Swierstra/Publications/DataTypesALaCarte.pdf) [**Haskell**]
    * _Assembling Data Types and functions_

* [Why Functional Programming Matters - John Hughes](https://www.cs.kent.ac.uk/people/staff/dat/miranda/whyfp90.pdf)
    * _High-Order Functions (HOFs) and Lazy Evaluation_

* [Algebraic effects for Functional Programming](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/08/algeff-tr-2016-v3.pdf)
    * _Algebraic Effects, Type Inference, compilation scheme

<a name="lectures"></a>
## Lectures

* [Goteborg university - Haskell advanced Functional Programming](https://chalmers.instructure.com/courses/3766/assignments/syllabus) [**Haskell**]
    * _Haskell Course_

- [Data61 Haskell functional programming course](https://github.com/data61/fp-course)
    * _Functional Programming Course_

<a name="blogs"></a>
## Blogs

* [The morning papers](https://blog.acolyer.org/)

* [Typelevel](https://typelevel.org/blog/)

* [SoftwareMill](https://softwaremill.com/blog/)

* [J. De Goes](http://degoes.net/)

* [Runar](http://blog.higher-order.com/)

* [Habla](https://blog.hablapps.com/)

* [Li Haoyi](http://www.lihaoyi.com/)

* [Kubuszok](https://kubuszok.com/#blog)

* [FP Complete](https://www.fpcomplete.com/blog) [**Haskell**]
    
* [Yann Esposito](http://yannesposito.com/Scratch/en/blog/)
 
* [Mine ! :D](https://github.com/mmenestret/fp-ressources/)

* [Blog: reasonably polymorphic](http://reasonablypolymorphic.com/)

<a name="books"></a>
## Books

* [Functional Programming in Scala](https://www.manning.com/books/functional-programming-in-scala)

* [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling) 

* [https://underscore.io/books/scala-with-cats/](https://underscore.io/books/scala-with-cats/)

* [Functional Programming for Mortals](https://leanpub.com/fpmortals/read)

* Category theory for programmers
    * [Haskell](http://www.blurb.com/b/9008339-category-theory-for-programmers) 
    * [Scala](https://github.com/typelevel/CT_from_Programmers.scala)

* [A History of Computation, Logic and Algebra](https://pron.github.io/computation-logic-algebra)

* [The Books of Monads](https://www.goodreads.com/book/show/42449863-the-book-of-monads) [**Scala**] [**Haskell**]

<a name="chat-rooms"></a>
## Chat rooms

* [Scala FR gitter](https://gitter.im/scala/fr)

* [Typevel General gitter](https://gitter.im/typelevel/general)

* [Cats gitter](https://gitter.im/typelevel/cats)

* [Functional programming Slack](https://functionalprogramming.slack.com/messages/C0436F0PY/)

<a name="newsletters"></a>
## Newsletters

* [Scalatimes](https://scalatimes.com/)

* [Awesome Scala](https://scala.libhunt.com/newsletter)

<a name="podcasts"></a>
## Podcasts

* [Functional Geekery](https://www.functionalgeekery.com/)

* [Co-recursive](https://corecursive.com/category/podcast/)

* [FP podcast list](https://www.fpcasts.com/)

<a name="repositories"></a>
## Repositories

* [Scala pet store](https://github.com/pauljamescleary/scala-pet-store)
    * _Http4s, Circe, Doobie, Cats, Cats Effects, ScalaCheck, Circe Config, Tagless Final_

* [Befunge-93](https://github.com/SystemFw/Befunge-93)
    * _Cats, Cats Effetcs, fs2, Tagless Final_

* [Scala typeclassopedia](https://github.com/lemastero/scala_typeclassopedia)
    * *Patterns from math (Category theory, Abstract algebra) in Scala*
    
## Special thanks

Thanks to [@olivierschultz](https://twitter.com/OlivierSchultz) who helps me maintain that list ! 
