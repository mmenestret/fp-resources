# Curated list of great Scala oriented (but not always) Functional Programming resources

## Your personal reading list

If you wish to track your progress in the reading list, follow these steps:

<details>
<summary>Steps</summary>

**Create a new branch so you can check items like this, just put an x in the brackets: [x]**

    Fork a branch and follow the commands below

`git checkout -b my-personal-list`

`git remote add mmenestret https://github.com/mmenestret/fp-resources`

`git fetch --all`

    Mark all boxes with X after you completed your changes

`git add . `

`git commit -m "Marked x" `

`git pull mmenestret`

`git push`
</details>

## Categories

- [Functional Programming in general](#fp-in-general)
    - [Talks](#talks-fp-in-general)
    - [Articles](#articles-fp-in-general)
- [Types](#types)
    - [Talks](#talks-types)
    - [Articles](#articles-types)
- [Effects](#effects)
    - [Talks](#talks-effects)
    - [Articles](#articles-effects)
- [State](#state)
    - [Talks](#talks-state)
    - [Articles](#articles-state)
- [Semigroup / Monoid](#semigroup-monoid)
    - [Talks](#talks-semigroup-monoid)
    - [Articles](#articles-semigroup-monoid)
- [Free monad / Tagless Final and monad stacks](#freemonad-taglessfinal-monadstacks)
    - [Talks](#talks-freemonad-taglessfinal-monadstacks)
    - [Articles](#articles-freemonad-taglessfinal-monadstacks)
- [Typeclass](#typeclass)
    - [Talks](#talks-typeclass)
    - [Articles](#articles-typeclass)
- [Concurrency](#concurrency)
    - [Talks](#talks-concurrency)
    - [Articles](#articles-concurrency)
- [Optics](#optics)
    - [Talks](#talks-optics)
    - [Articles](#articles-optics)
- [Recursion Schemes](#recursion-schemes)
    - [Talks](#talks-recursion-schemes)
    - [Articles](#articles-recursion-schemes)
- [Code Pattern](#code-pattern)
    - [Talks](#talks-code-pattern)
    - [Articles](#articles-code-pattern)
- [Theory](#theory)
    - [Talks](#talks-theory)
    - [Articles](#articles-theory)

- [Academic papers](#academic-papers)

- [Lectures](#lectures)

- [Blogs](#blogs)

- [Books](#books)

- [Chat rooms](#chat-rooms)

- [Newsletters](#newsletters)

- [Podcasts](#podcasts)

- [Repositories](#repositories)

<a name="fp-in-general"></a>
## Functional Programming in General

<a name="talks-fp-in-general"></a>
### Talks

- [ ] [Functional Programming is Terrible - Rúnar Bjarnason](https://www.youtube.com/watch?v=hzf3hTUKk8U)
    - *Tail Recursion, Trampolining, Higher Kinded Types, Benefits of Functional Programming*

- [ ] [What Referential Transparency can do for you - Luka Jacobowitz](https://www.youtube.com/watch?v=X-cEGEJMx_4&feature=youtu.be&t=228)
    - *Functional Programming Design, Referential Transparency and side-effects*

- [ ] [Functional Design Patterns - Scott Wlaschin](https://www.youtube.com/watch?v=srQt1NAHYC0)
    - *Functional design patterns from partial application to monads and monoids*

- [ ] [FP to the Max - John De Goes](https://www.youtube.com/watch?v=sxudIMiOo68)
    - *live coding session on Functional Programming design and techniques*

- [ ] [Constraints Liberate, Liberties Constrain — Runar Bjarnason](https://www.youtube.com/watch?v=GqmsQeSzMdw)
    - *Functional Programming design*
    
- [ ] [May Your Data Ever Be Coherent](https://www.youtube.com/watch?v=gVXt1RG_yN0)
    - *Functional Programming design*

- [ ] [Functional Patterns in Domain Modeling — Debasish Ghosh](https://www.youtube.com/watch?v=U0Rk9Knq8Vk)
    - *Functional domain modeling*

<a name="articles-fp-in-general"></a>
### Articles

- [ ] [Anatomy of functional programming](http://geekocephale.com/blog/2018/10/08/fp)
    - *Functional Programming design*

- [ ] [Data Modeling in FP vs OOP](http://degoes.net/articles/fp-vs-oop-part1)
    - *Functional Programming design*

- [ ] [Scala best practices](https://nrinaudo.github.io/scala-best-practices/index.html)
    - *List of good practice in Scala*
    
- [ ] [Trampolining and stack safety in Scala](https://medium.com/@olxc/trampolining-and-stack-safety-in-scala-d8e86474ddfa)
    - Trampolining, tail call elimination

- [ ] [https://typelevel.org/blog/2019/02/06/algebraic-api-design.html](https://typelevel.org/blog/2019/02/06/algebraic-api-design.html)
    - *Types, Functions, Properties*

- [ ] [Anatomy of an algebra](http://geekocephale.com/blog/2018/10/06/algebras)
    - *(ADT) Algebraic Data Type*

<a name="types"></a>
## Types

<a name="talks-types"></a>
### Talks

- [ ] [Why do Functional Programmers always talk about Algebra(s)?](https://www.youtube.com/watch?v=s2ay9nEW3ak)
    - *Domain Algebra, Algebraic structure*

- [ ] [Type Members vs Type Parameters](https://www.youtube.com/watch?v=R8GksuRw3VI)
    - *How to choose between Type Members and Type Parameters*

<a name="articles-types"></a>
### Articles

- [ ] [Scala’s Types of Types](http://ktoso.github.io/scala-types-of-types)
    - *Scala Type System*

- [ ] [Types: Never commit too early](https://www.sderosiaux.com/articles/2018/08/15/types-never-commit-too-early-part1)
    - *Function encodings*

- [ ] [Kinds of types in Scala](https://kubuszok.com/2018/kinds-of-types-in-scala-part-1/)
    - *Type Theory in Scala*

- [ ] [From Type Theory to Haskell in 10 Minutes](https://www.stackbuilders.com/news/from-type-theory-to-haskell-in-10-minutes) [**Haskell**]
    - *Type Theory in Haskell*

- [ ] [Practical Type Safety](http://www.lihaoyi.com/post/StrategicScalaStylePracticalTypeSafety.html)
    - *Using Scala in a Type Safe way*

- [ ] [Functional APIs: an OOP approach to FP](https://blog.hablapps.com/2017/06/26/functional-apis-an-oop-approach-to-fp/)
    - *(GADTs) Generalized Algebraic Data Types*

- [ ] [How do Algebraic Data types compare to the concept of inheritance in Object Oriented Languages ?](https://www.quora.com/How-do-Algebraic-Data-types-in-say-Haskell-compare-to-the-concept-of-inheritance-in-Object-Oriented-Languages-in-say-Java/answer/Bartosz-Milewski?share=1c2ac3a8)
    - *(ADTs) Algebraic Data Types*

<a name="effects"></a>
## Effects

<a name="talks-effects"></a>
### Talks

- [ ] [Functional Programming with Effects - Rob Norris](https://www.youtube.com/watch?v=po3wmq4S15A)
    - *Effects and Equational Reasoning*

- [ ] [The Death of Final Tagless](https://skillsmatter.com/skillscasts/13247-scala-matters)
    - *Functional Effects, Tagless final alternative with ZIO*

- [ ] [The Making of an IO - Daniel Spiewak](https://www.youtube.com/watch?v=g_jP47HFpWA)
    - *IO Monad with Cats Effects*
    
- [ ] [http4s: pure, typeful, functional HTTP in Scala – Ross Baker](https://www.youtube.com/watch?time_continue=1915&v=urdtmx4h5LE)
    - IO, HTTP4s, Kleisli
    
- [ ] [Declarative Control Flow with fs2 Stream – Fabio Labella](https://www.youtube.com/watch?v=YSN__0VEsaw)
    - *Functional Stream with fs2*

<a name="articles-effects"></a>
### Articles

- [ ] [ZIO Monad, Scala's ReaderT pattern](http://degoes.net/articles/zio-environment)
    - *Functiona Effects, Tagless final, ReaderT*

<a name="state"></a>
## State

<a name="talks-state"></a>
### Talks

- [ ] [Regaining Control with State Monad and Friends](https://www.youtube.com/watch?v=Pgo73GfHk0U)
    - *State, StateT, IndexedState*

<a name="articles-state"></a>
### Articles


<a name="semigroup-monoid"></a>
## Semigroup / Monoid

<a name="talks-semigroup-monoid"></a>
### Talks


<a name="articles-semigroup-monoid"></a>
### Articles

- [ ] [A tale on Semirings](https://typelevel.org/blog/2018/11/02/semirings.html)
    - *Semirings through semigroups and monoids*

- [ ] [Anatomy of semigroups and monoids](http://geekocephale.com/blog/2018/11/06/semi-monoid)
    - *Semigroups and Monoids*

<a name="freemonad-taglessfinal-monadstacks"></a>
## Free Monad / Tagless Final and monad stacks

<a name="talks-freemonad-taglessfinal-monadstacks"></a>
### Talks

- [ ] [Move Over Free Monads: Make Way for Free Applicatives! — John de Goes](https://www.youtube.com/watch?v=H28QqxO7Ihc)
    - *Free applicatives*

- [ ] [Monad transformers down to earth - Gabriele Petronella](https://www.youtube.com/watch?v=jd5e71nFEZM)
    - *Monad transformer*

- [ ] [A Year living Freely – Chris Myers](https://www.youtube.com/watch?v=rK53C-xyPWw)
    - *Free monad*

- [ ] [Free monad or tagless final? How not to commit to a monad too early - Adam Warski](https://www.youtube.com/watch?v=IhVdU4Xiz2U)
    - *live coding session on Free monads and Tagless final*

- [ ] [Advanced Tagless Final - Saying farewell to Free - Luka Jacobowitz](https://www.youtube.com/watch?v=E9iRYNuTIYA)
    - *Free monad, Tagless final*

- [ ] [Free as in Monads by Daniel Spiewak](https://www.youtube.com/watch?v=aKUQUIHRGec)
    - *live coding session on Free monad*

- [ ] [Freestyle, Free & Tagless: Separation of Concerns on Steroids - Michał Płachta](https://www.youtube.com/watch?v=-4lB5EKS5Uk)
    - *Free and tagless in a real application*

- [ ] [The Eff monad, one monad to rule them all - Eric Torreborre](https://www.youtube.com/watch?v=KGJLeHhsZBo)
    - *Eff monad*

- [ ] [Monad Stacks or: How I Learned to Stop Worrying and Love the Free Monad – Harry Laoulakos](https://www.youtube.com/watch?v=2TDDDFGa8-0)
    - *Monad stacks*

- [ ] [A roadtrip with monads: from MTL, through tagless, to BIO - Paweł Szulc](https://www.youtube.com/watch?v=QM86Ab3lL20)
    - *MTL, Tagless final, BIO*

- [ ] [GETTING MORE MILEAGE FROM YOUR MONADS WITH MTL - Paweł Szulc](https://www.youtube.com/watch?v=knK70T4X7YE)
    - *MTL style*


<a name="articles-freemonad-taglessfinal-monadstacks"></a>
### Articles

- [ ] [Introduction to Tagless final](https://www.beyondthelines.net/programming/introduction-to-tagless-final/)
    - *Tagless final*

- [ ] [Free and tagless compared - how not to commit to a monad too early](https://softwaremill.com/free-tagless-compared-how-not-to-commit-to-monad-too-early/)
    - *Free monad and Tagless final*

- [ ] [Exploring Tagless Final pattern for extensive and readable Scala code](https://blog.scalac.io/exploring-tagless-final.html)
    - *Tagless final*

- [ ] [Gist about Fabio Labella's on inital vs final tagless encodings](https://gist.github.com/mmenestret/0b746cfd650796a639723ee74a3de302)
    - *Tagless final*
- [ ] [Testing tagless final with Discipline](https://www.iteratorshq.com/blog/tagless-with-discipline-testing-scala-code-the-right-way/)
    - *Tagless final with the typelevel library Discipline*

- [ ] [Structuring Functional Programs with Tagless Final](https://www.becompany.ch/en/blog/2018/06/21/tagless-final)
    - *Tagless final*

- [ ] [Typed tagless-final interpretations: Lecture notes](http://okmij.org/ftp/tagless-final/course/index.html)
    - *Tagless final*

- [ ] [Optimizing Tagless Final – Saying farewell to Free](https://typelevel.org/blog/2017/12/27/optimizing-final-tagless.html)
    - *Tagless final*

- [ ] [From Object Algebras to Finally Tagless Interpreters](https://oleksandrmanzyuk.wordpress.com/2014/06/18/from-object-algebras-to-finally-tagless-interpreters-2/) [**Haskell**]
    - *Tagless final*

- [ ] [Free Monoids and Free Monads](http://blog.higher-order.com/blog/2013/08/20/free-monads-and-free-monoids/)
    - *Free structure with monoids and monads*

- [ ] [Intro to MTL](https://typelevel.org/blog/2018/10/06/intro-to-mtl.html)
    - *MTL style*

- [ ] [Monad transformer variance](https://typelevel.org/blog/2018/09/29/monad-transformer-variance.html)
    - *Monad Transformer*

- [ ] [Monadic EDSLs in Scala](https://typelevel.org/blog/2016/09/21/edsls-part-1.html)
    - *(EDSLs) Embedded domain specific languages*

- [ ] [EDSLs as functions](https://typelevel.org/blog/2016/10/26/edsls-part-2.html)
    - *(EDSLs) Embedded domain specific languages*

- [ ] [Intro to MTL](https://typelevel.org/blog/2018/10/06/intro-to-mtl.html)
    - *MTL style*

- [ ] [A tale of two Monads: Free vs MTL](http://tech.frontrowed.com/2017/09/28/benching-free/)
    - *Free monad vs MTL style*

<a name="typeclass"></a>
## Typeclass

<a name="talks-typeclass"></a>
### Talks

- [ ] [Mastering Typeclass Induction — Aaron Levin](https://www.youtube.com/watch?v=Nm4OIhjjA2o)
    - *Typeclasses*  

- [ ] [Oh, all the things you'll traverse - Luka Jacobowitz](https://www.youtube.com/watch?v=GhLqTZaix5U)
    - *Traverse*
    
- [ ] [Type class, ultimate ad hoc](https://www.youtube.com/watch?v=2EdQFCP5mZ8)
    - *Typeclasses*    

<a name="articles-typeclasses"></a>
### Articles

- [ ] [Anatomy of a type class](http://geekocephale.com/blog/2018/10/05/typeclasses)
    - *Typeclasses*

- [ ] [Type classes in Scala](https://blog.scalac.io/2017/04/19/typeclasses-in-scala.html)
    - *Typeclasses*

- [ ] [Implicits, type classes, and extension methods](https://kubuszok.com/compiled/implicits-type-classes-and-extension-methods/)
    - *Implicits and typeclasses*  

- [ ] [Typeclasses in perspective](https://diogocastro.com/blog/2018/06/17/typeclasses-in-perspective/) [**Haskell**]
    - *Typeclasses*

- [ ] [Inheritance vs Generics vs Typeclasses in Scala](https://dev.to/jmcclell/inheritance-vs-generics-vs-typeclasses-in-scala-20op)
    - *Typeclasses*

- [ ] [Typeclass counterexample](https://blog.functorial.com/posts/2015-12-06-Counterexamples.html) [**Haskell**]
    - *Typeclasses*  

<a name="concurrency"></a>
## Concurrency

<a name="talks-concurrency"></a>
### Talks

- [ ] [Concurrency with Cats-effect - Michael Pilquist](https://www.youtube.com/watch?v=Gig-f_HXvLI)
    - *Cats Effects and fs2*

<a name="articles-concurrency"></a>
### Articles


<a name="optics"></a>
## Optics

<a name="talks-optics"></a>
### Talks

- [ ] [Beyond Scala Lenses — Julien Truffaut](https://www.youtube.com/watch?v=6nyGVgGEKdA)
    - *Lenses*

<a name="articles-optics"></a>
### Articles


<a name="recursion-schemes"></a>
## Recursion schemes

<a name="talks-recursion-schemes"></a>
### Talks

- [Pure Functional Database Programming with Fixpoint Types — Rob Norris](https://www.youtube.com/watch?v=7xSfLPD6tiQ)
    - *Fixpoint, Recursion schemes*

- [ ] [Peeling the Banana: Recursion Schemes from First Principles - Zainab Ali](https://www.youtube.com/watch?v=XZ9nPZbaYfE)
    - *Recursion schemes*

- [ ] [THOSE 10000 CLASSES I NEVER WROTE - Valentin Kasas](https://www.youtube.com/watch?v=1TUgSaD6cCo)
    - *Hylomorphisms, Expressive Schemes*

- [ ] [Going bananas with recursion schemes for fixed point data types - Paweł Szulc](https://www.youtube.com/watch?v=IlvJnkWH6CA)
    - *Catamorphism, fix point data type, Matryoshka*

<a name="articles-recursion-schemes"></a>
### Articles

- [ ] [Recursion training](https://github.com/softwaremill/recursion-training#sources-and-resources)
    - *Resources and examples on recursion schemes*

<a name="code-pattern"></a>
## FP code pattern

<a name="talks-code-pattern"></a>
### Talks

<a name="articles-code-pattern"></a>
### Articles

- [ ] [Handle pattern](https://jaspervdj.be/posts/2018-03-08-handle-pattern.html) [**Haskell**]

- [ ] [ReaderT pattern](https://www.fpcomplete.com/blog/2017/06/readert-design-pattern) [**Haskell**]

- [ ] [RIO Monad](https://www.fpcomplete.com/blog/2017/06/readert-design-pattern) [**Haskell**]


<a name="theory"></a>
## Theory

<a name="talks-theory"></a>
### Talks

- [ ] [Crash course into category theory - Rúnar Bjarnason](https://www.youtube.com/watch?time_continue=2&v=ml5rU06z0Fk)
    - *Category theory*

- [ ] [Category Theory for the Working Hacker - Philip Wadler](https://www.youtube.com/watch?v=V10hzjgoklA)
    - *Category theory*

- [ ] [Propositions as Types - Philip Wadler](https://www.youtube.com/watch?v=IOiZatlZtGU)    
    - *Relation between logic and computation*
    
- [ ] [Stephen Pimentel - Propositions as Types for Beginners in Haskell](https://www.youtube.com/watch?v=tfG7T54MhIU&index=29&t=0s&list=PL7DZ7q3nEWhzLs7nLb57N75EY4py_P7pI) [**Haskell**]
    - *Curry-Howard isomorphism* 

- [ ] [Category Theory - Bartosz Milewski](https://www.youtube.com/user/DrBartosz/playlists)
    - *Category theory playlist*
    
- [ ] [Why a monad is a monoid in the category of endofunctors](https://www.youtube.com/watch?v=pvTycwaAmLo)
    - *Functor, Natural transformation, bifunctor, monoidal category, monoid, monad*

- [ ] [A History of Computation, Logic and Algebra](https://www.youtube.com/watch?v=c_nPnURW6BU)
    - *Computation, Logic and Algebra*

<a name="articles-theory"></a>
### Articles

- [ ] [Anatomy of functors and category theory](http://geekocephale.com/blog/2019/02/16/functors-cat-theory)
    - *Functors and Category theory*

- [ ] [Category theory and programming](http://yogsototh.github.io/Category-Theory-Presentation/categories.html)
    - *Category theory*

- [ ] [A History of Computation, Logic and Algebra](https://pron.github.io/computation-logic-algebra)
    - *Category theory, logic and algebra*

- [ ] [Category theory material](https://www.logicmatters.net/categories/)
    - *Category theory*

- [ ] [Sequent calculus tutorial](http://logitext.mit.edu/logitext.fcgi/tutorial)
    - *Category theory*
    
- [ ] [Proof and types](http://www.paultaylor.eu/~pt/stable/prot.pdf)
    - *Type theory*

- [ ] [Why do monads matter ?](https://cdsmith.wordpress.com/2012/04/18/why-do-monads-matter/)
    - *Monad*

<a name="academic-papers"></a>
## Academic papers

- [ ] [Theorems for Free! - P. Wadler](http://ttic.uchicago.edu/~dreyer/course/papers/wadler.pdf)
    - *Polymorphic function, abstraction theorem*

- [ ] [Propositions as types - P. Wadler](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)
    - *[...]for each proposition in the logic there is a corresponding type in the programming language[...]*

- [ ] [Freer Monads, More Extensible Effects](http://okmij.org/ftp/Haskell/extensible/more.pdf) [**Haskell**]
    - *Extensible Effects*

- [ ] [Data types a la carte](http://www.cs.ru.nl/~W.Swierstra/Publications/DataTypesALaCarte.pdf) [**Haskell**]
    - *Asselbking Data Types and function*

- [ ] [Why Functional Programming Matters - John Hughes](https://www.cs.kent.ac.uk/people/staff/dat/miranda/whyfp90.pdf)
    - *High-Order functions and lazy evaluation*

<a name="lectures"></a>
## Letures

- [Goteborg university - Haskell advanced Functional Programming](https://chalmers.instructure.com/courses/3766/assignments/syllabus) [**Haskell**]

- [Typed tagless-final interpretations: Lecture notes](http://okmij.org/ftp/tagless-final/course/index.html)

<a name="blogs"></a>
## Blogs

- [The morning papers](https://blog.acolyer.org/)

- [Typelevel](https://typelevel.org/blog/)

- [SoftwareMill](https://softwaremill.com/blog/)

- [J. De Goes](http://degoes.net/)

- [Runar](http://blog.higher-order.com/)

- [Habla](https://blog.hablapps.com/)

- [Li Haoyi](http://www.lihaoyi.com/)

- [Kubuszok](https://kubuszok.com/#blog)

- [FP Complete](https://www.fpcomplete.com/blog) [**Haskell**]
    
- [Yann Esposito](http://yannesposito.com/Scratch/en/blog/)
 
- [Mine ! :D](https://github.com/mmenestret/fp-ressources/)

- [Blog: reasonably polymorphic](http://reasonablypolymorphic.com/)

<a name="books"></a>
## Books

- [ ] [Functional Programming in Scala](https://www.manning.com/books/functional-programming-in-scala)

- [ ] [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling) 

- [ ] [https://underscore.io/books/scala-with-cats/](https://underscore.io/books/scala-with-cats/)

- [ ] [Functional Programming for Mortals](https://leanpub.com/fpmortals/read)

- Category theory for programmers
    - [ ] [Haskell](http://www.blurb.com/b/9008339-category-theory-for-programmers) 
    - [ ] [Scala](https://github.com/typelevel/CT_from_Programmers.scala)

- [ ] [A History of Computation, Logic and Algebra](https://pron.github.io/computation-logic-algebra)

<a name="chat-rooms"></a>
## Chat rooms

- [Scala FR gitter](https://gitter.im/scala/fr)

- [Typevel General gitter](https://gitter.im/typelevel/general)

- [Cats gitter](https://gitter.im/typelevel/cats)

- [Functional programming Slack](https://functionalprogramming.slack.com/messages/C0436F0PY/)

<a name="newsletters"></a>
## Newsletters

- [Scalatimes](https://scalatimes.com/)

- [Awesome Scala](https://scala.libhunt.com/newsletter)

<a name="podcasts"></a>
## Podcasts

- [Functional Geekery](https://www.functionalgeekery.com/)

- [Co-recursive](https://corecursive.com/category/podcast/)

- [FP podcast list](https://www.fpcasts.com/)

<a name="repositories"></a>
## Repositories

- [Scala pet store](https://github.com/pauljamescleary/scala-pet-store)
    - *Http4s, Circe, Doobie, Cats, ScalaCheck, Circe Config, Tagless Final*

- [Befunge-93](https://github.com/SystemFw/Befunge-93)
    - *Tagless Final*

- [Scala typeclassopedia](https://github.com/lemastero/scala_typeclassopedia)
    - *Patterns from math (Category theory, Abstract algebra) in Scala*
