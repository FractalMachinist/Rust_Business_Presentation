# The Budget
* [x] Colombia Corporation completed seed funding based on promises of excellent reliability and disruptive value over the next 10 years, and budgeted $4.4M over the next 4 years to deliver it.

## Technical Debt
* [x] However, that budget may be leveraging technical debt: the growing, long-term penalty for making poor foundational design decisions with high short-term payoff. 
* [x] These 70% of vulnerabilities are interest paid on technical debt, borrowed from the foundational languages the industry relies on, diverting value away from shareholders and customers.
### Memory Safety
#### Microsoft's Vulnerabilities and the cost of C/C+
* [x] Microsoft found that “~70% of the vulnerabilities addressed through a security update each year continue to be memory safety issues” **#REFERENCE**, with similar stories from other software companies. 
* [x] These memory safety issues come from unchecked freedoms in C and C++, languages chosen decades ago for their high short-term payoff in the race to dominate the home PC market.
#### Rust's Memory System
* [x] ...including proven guarantees that Rust code will not compile with unnoticed memory safety issues **#REFERENCE**.
* [x] **TODO Explain the Memory System**

### Component Integration
#### Astoria's Value to Researchers
* [x] Astoria’s central value to researchers is bringing their experiment's infrastructure up to their level.
* [x] Researchers must be able to describe their experiment in a way they find intuitive.
* [x] As researchers configure their experiments, the interactions between each component need to be presented to them as simply as possible.
* [x] Astoria will need to manage interactions between microcontrollers, network protocols, local workstations, databases, cloud services, web pages, reports, dashboards, and analysis pipelines.
#### Paradigms and Type Systems
* [x] In software development, the underlying structure of how components integrate is the programming paradigm, and the enforcer that makes sure they integrate correctly is the type system.
* [ ] The metaphor underlying how researchers describe their experiments will be a paradigm.
* [ ] The organization and verification of how the components of an experiment fit together will be a type system.
##### Language Characteristics become Product Characteristics
* [x] This means Astoria’s functionality may rest squarely on the paradigms and type system of the language it will be written in.
###### Poor Characteristics Become Technical Debt
- [ ] **#TODO**
##### Rust's Paradigms and Type Systems
* [x] Rust uses a wide variety of paradigms, including functional, object oriented, and imperative programming.
* [x] Rust’s type system is robust and brief, avoiding many of the wrapper/reflection/proxy object types in favor of a system of traits - interfaces which can be declared for objects meeting certain conditions, even across package boundaries #REFERENCE. 
- [ ] **#TODO More about Traits**
* [x] This trait system fully supports generics; however, its inheritance system offers less support than some other languages, like Java. 
##### Rust on Every Platform
* [x] Rust's ecosystem provides support for Rust in the cloud, browser, server, desktop, and microcontroller **#REFERENCE**, meaning Rust can fearlessly take Astoria anywhere the laboratory needs.
* [x] Rust's traits and paradigms allow for all of these deployments to share a solid, interoperable system of types, protocols, and expectations.

## Hire Talent
### Hire Talent Efficiently
* [x] In addition to falling within budget, Columbia Corporation’s upcoming hiring window will need to capture a lot of talent.
### C/++ Is Not Loved
* [x] C is dreaded by 60% of those who did extensive development work in it last year
* [x] C++ is doing better at 51%
- [ ] 4.5% of developers want to start developing in C
- [ ] C++ is at 8.8% 
#### Rust Supports Hiring
* [x] Rust is well loved and fairly well adopted.
* [x] Developers are excited to learn Rust, and Rust is exciting to learn.
* [x] Colombia Corporation can use Rust as part of our developer culture to attract the talent and inventiveness needed to thrive.
##### Developers Love Rust
- [ ] Rust is used by 7% of Stack Overflow Developer Survey respondents.
* [x] Rust has won “most loved programming language” since 2016 [https://insights.stackoverflow.com/survey/2021].
* [x] Rust is loved by 87% of its users.
##### Developers Want to Learn Rust
* [x] 14% of developers are looking for an opportunity to learn Rust [https://insights.stackoverflow.com/survey/2021].
##### Rust's Learning Experience
* [x] Rust’s minor increase in syntax from C/C++ is more than outweighed by the robust tooling, package management, and ecosystem of the Rust community.
* [x] Rust got this way by supporting its learners [https://www.rust-lang.org/learn]
* [x] New hires who don’t know Rust will be able to take advantage of Rust's support community, and their familiarity with other languages.
* [x] Rust also has excellent tooling and community support **#REFERENCE**
* [x] ... including a native package manager, outstanding learning resources, and development tools focused on reliability and benchmarking [https://www.rust-lang.org/learn] **#REFERENCE Development Tools**.

# Bangers
* [x] So, how will Colombia Corporation leverage high short-term payoffs to deliver growth and reach customers, without taking on inescapable technical debt? I propose Rust.
* [x] This foundational reliability ensures Astoria’s growing codebase will be an asset, not a liability.

# About Rust
* [x] Rust started development in the 2010’s at Mozilla as a C/C++ replacement within Firefox, reaching 1.0/Stable in 2015.
* [x] Rust’s syntax and design focuses on “build[ing] reliable and efficient software” #REFERENCE, including proven guarantees that Rust code will not compile with unnoticed memory safety issues.
- [ ] **#TODO Fuzzers and Benchmarking**
* [x] Like C and C++, Rust is primarily a systems programming language, forgoing simplicity and perfect portability to get performance and stability [https://en.wikipedia.org/wiki/System_programming_language].
