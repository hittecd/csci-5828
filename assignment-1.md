### Assignment 1

**1. Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.**
    
  __Essential difficulties__ are those that arise directly from the process of software engineering itself. These include challenges like accounting for the multitude of states a program can exist in or have to deal with. 
  
  For example, a form in a simple web application has to account for every possible input a user might give. The range of input stretches from nonsensical entries (a birthdate in an email field) to deliberately malicious inputs like SQL injection. Failing to account for even one form of input can lead to the entire system being compromised.
  
**2. Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.**
  
  __Accidental difficulties__ are those which arrise circumstantially from the environments and tools being used to develop software. They are not necessarily difficulties resulting from accidents (someone accidentally deleting source code ..oops).
  
  For example, an accidental difficulty might be encountered when a piece of software is upgraded to a new language level, say migrating from Java 6 to Java 7. If there are conventions that are used in the previous language that do not communicate directly to the new language, and must therefore be refactored, this challenge represents an accidental difficulty.

**3. List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.**

  * Complexity:
  
  Software is more complex than many other engineering concerns for a variety of reasons. Software tends to become more complex as it scales. It must account for a multitude of states relative to physical systems like airplanes and buildings. Software systems are developed to eliminate all redundancy. Software systems are inherently unique.
  
  For example, a bridge may be comprised of many identical components (i.e. screws and beams). However, similar redundancy is deliberately avoided in software. If it is discovered that there are multiple classes in a system that are performing the same funciton, they will likely be refactored into one class. Every component of a Software system must be understood uniquely to understand the system as a whole.

  * Conformity:
  
  Much of the challenge in a software project derives from conforming the project to arbitraty conditions. These may be requirements devised by a customer or project manager that do not relate directly to the system itself. They may also relate to preexisting conditions and environments.
  
  For example, a customer may request that a new piece of software integrate with some other software they have recently purchased. Changes like these cannot be preempted and must be dealth with as they arrise.

  * Changeability:
  
  Because software does not have a physical manifestation, it is much more changable than other engineering concerns. While this is a strength of software, it also introduces many challenges.
  
  For example, the expense involved in an automobile recall means that changes to a line of cars will only be done if the avoided costs are greater than the significant sunk cost of performing the recall itself. Because of this, if a recall is done, there will be very explicit goals and directions for doing so. Software however is constantly being updated. It is often described as a living system, constantly changing and adapting to the needs of the moment. Each change might introduce vulnerabilities in the system, even where none existed prior. It also means that engineers must constantly study the syste to understand it.
  
  * Invisibility: 
  
  Software can be extracted into diagrams but its true form cannot be seen with the naked eye. It exists as electic charges within a computer. Other engineering concerns such as buildings and automobiles can be represented by models that are easy for the human mind to comprehend. 
  
  For example, a building might be represented as a scale model, allowing architects to compare their design concepts they imagined in their minds with its real world manifestation. The same cannot be done for software as it is inherently conceptual and therefore, more difficult to work with.

**4. Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.**

Brooks describes a 'silver bullet' as any single technique or development that will improve software development by an order of magnitude or more. He argues that no silver bullet exists by first breaking down the difficulties of software into two catagories: accidental and essential. While most developments have targeted accidental difficulties, yielding an order of magnitude increase would imply that such difficulties represent 90% of the burden in a given software project. Furthermore, such a 'silver bullet' would then have to reduce those difficulties to 0. Both are unlikely. Accidental difficulties, while a real consideration, are not the primary concern in software development. By their very nature, accidental difficulties can never be fully eliminated either. As for the essential difficulties, Brook argues that the inherant challenges of software development (complexity, conformity, changeability, and invisibility) cannot be directly solved. Improvements will be made on these, but software development will always involve some combination of these challenges. This is not to say however that the cumulative effects of many developments will not achieve an order of magnitude of improvement. But to hope for a single development to achieve this is, in Brooks' opinion, vain.

**5. In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.**

Sofware engineering involves the application of scientific principles to the development of software programs and their artifacts. While it is obviously based in aspects of Computer Science and other scientific disciplines, it differs from these pursuits in that Software Engineering is performed in the presence of practical constraints. While a chemist may seek to prove that a certain result can be achieved by a given process, a chemical engineer must achieve that same result in some practical manner. Those practical constraints may involve scaling the chemical process to produce the result on an instustrial scale, or within a cost effective manner, etc. Whatever the constraints may be, they are inherant in taking the science out of the lab and implementing it in the real world. The same is true of Computer Science and Software Engineering. Many concepts may be devised via Computer Science, but it is the responsibiltly of Software Engineers to create software systems from those concepts that can support users, ensure security, and any other real-world concerns within a reasonable budget.

**6. In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.**

  * Abstractions:

  __Abstraction__ is the process of breaking a complex problem down into smaller pieces thus making the problem understandable and solvable. It is perhaps the most important concept in software engineering. Every development uses abstraction, and many create new abstractions to be used in further development. For example, the file system is an abstraction for accessing data stored on a machine. An API which allows a user to remotely access the file system on a machine is itself an abstraction that sits on top of the file system abstraction and so on.

  * Conversations:

  __Conversations__ or communication is perhaps the most underrated concept in software development. Converstations are how we discover what customers want, how we learn to use an API, how we know which techonologies to use, and so on.

  * Specification:

  __Specification__ is a key organizational principle in software development. Specification enables developers to know what is required to use and add to software systems. For example, when a developer wishes to leverage an API, he/she must look to the API's specification to know determine what will be required. Without specification software development would be reduced to guess-work and trial-and-error.

  * Translation:

  __Translation__ is the ability to relate two or more distict constructs to one another so that they may be integrated or combined into a desired product. For example, understanding the specifications of an API and a web application so that they can be combined to perform some function is an act of translation.

  * Iteration:

  __Iteration__ in software development involves taking a step-by-step approach to implementing a solution. This is opposed to attempting to solve a problem all at once.
  
