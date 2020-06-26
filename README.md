<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
# Table of Contents

- [Professional Programming - about this list](#professional-programming---about-this-list)
  - [Contributing to this list](#contributing-to-this-list)
  - [Must-read books](#must-read-books)
  - [Must-read articles](#must-read-articles)
  - [Other general material and list of resources](#other-general-material-and-list-of-resources)
    - [Courses](#courses)
  - [Topics](#topics)
    - [Algorithm and data structures](#algorithm-and-data-structures)
    - [API design & development](#api-design--development)
    - [Attitude, habits, mindset](#attitude-habits-mindset)
    - [Automation](#automation)
    - [Biases](#biases)
    - [Career growth](#career-growth)
    - [Characters sets](#characters-sets)
    - [Code reviews](#code-reviews)
    - [Coding & code quality](#coding--code-quality)
    - [Computer science](#computer-science)
    - [Configuration](#configuration)
    - [Databases](#databases)
    - [Data formats](#data-formats)
    - [Data science](#data-science)
    - [Debugging](#debugging)
    - [Design (visual, UX, UI)](#design-visual-ux-ui)
    - [Design (OO modeling, architecture, patterns, anti-patterns, etc.)](#design-oo-modeling-architecture-patterns-anti-patterns-etc)
      - [Design: database schema](#design-database-schema)
      - [Design: patterns](#design-patterns)
      - [Design: simplicity](#design-simplicity)
    - [Dev environment & tools](#dev-environment--tools)
    - [Diversity & inclusion](#diversity--inclusion)
    - [Documentation](#documentation)
    - [Dotfiles](#dotfiles)
    - [Editors & IDE](#editors--ide)
    - [Engineering management](#engineering-management)
    - [Exercises](#exercises)
    - [Incident response (oncall, alerting, outages, firefighting, postmortem)](#incident-response-oncall-alerting-outages-firefighting-postmortem)
      - [Postmortem](#postmortem)
    - [Internet](#internet)
    - [Interviewing](#interviewing)
    - [Learning & memorizing](#learning--memorizing)
    - [Low-level](#low-level)
    - [Network](#network)
    - [Observability (monitoring, logging, exception handling)](#observability-monitoring-logging-exception-handling)
      - [Logging](#logging)
      - [Error/exception handling](#errorexception-handling)
      - [Monitoring](#monitoring)
    - [Problem solving](#problem-solving)
    - [Project management](#project-management)
    - [Programming languages](#programming-languages)
      - [Python](#python)
      - [JavaScript](#javascript)
      - [Functional programming](#functional-programming)
    - [Programming paradigm](#programming-paradigm)
    - [Over-engineering](#over-engineering)
    - [Reading](#reading)
    - [Refactoring](#refactoring)
    - [Releasing & deploying](#releasing--deploying)
    - [Security](#security)
    - [Shell](#shell)
    - [System architecture](#system-architecture)
      - [Scalability](#scalability)
      - [Stability](#stability)
      - [Resiliency](#resiliency)
    - [Site Reliability Engineering (SRE)](#site-reliability-engineering-sre)
    - [Technical debt](#technical-debt)
    - [Testing](#testing)
    - [Tools](#tools)
    - [Version control (Git)](#version-control-git)
    - [Work ethics, productivity & work/life balance](#work-ethics-productivity--worklife-balance)
    - [Web development](#web-development)
    - [Writing](#writing)
    - [Writing for performance](#writing-for-performance)
  - [Resources & inspiration for presentations](#resources--inspiration-for-presentations)
  - [Concepts](#concepts)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Professional Programming - about this list

> Give me six hours to chop down a tree and I will spend the first four sharpening the axe. (Abraham Lincoln)

A collection of full-stack resources for programmers.

The goal of this page is to make you a more proficient developer. You'll find only resources that I've found truly inspiring, or that have become timeless classics.

This page is not meant to be comprehensive. I am trying to keep it light and not too overwhelming. The selection of articles is opinionated.

Items:

* 🧰: list of resources
* 📖: book
* 🎞: video/movie extract/movie
* 🎤: slides/presentation

## Contributing to this list

Feel free to open a PR to contribute! I will not be adding everything: as stated above, I am trying to keep the list concise.

## Must-read books

I've found these books incredibly inspiring:

* [The Pragmatic Programmer: From Journeyman to
  Master](http://www.amazon.com/The-Pragmatic-Programmer-Journeyman-Master/dp/020161622X) 📖: hands-on the most inspiring and useful book I've read about programming.
* [Code Complete: A Practical Handbook of Software
  Construction](http://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670) 📖: a nice addition to The Pragmatic Programmer, gives you the necessary framework to talk about code.
* [Release It!](https://smile.amazon.com/Release-Design-Deploy-Production-Ready-Software/dp/1680502395) 📖: this books goes beyond code and gives you best practices for building production-ready software. It will give you about 3 years worth of real-world experience.
* [Scalability Rules: 50 Principles for Scaling Web
  Sites](https://smile.amazon.com/Scalability-Rules-Principles-Scaling-Sites/dp/013443160X) 📖
* [The Linux Programming Interface: A Linux and UNIX System Programming Handbook](http://www.amazon.com/The-Linux-Programming-Interface-Handbook/dp/1593272200) 📖: outside of teaching you almost everything you need to know about Linux, this book will give you insights into how software evolves, and the value of having simple & elegant interfaces.
* [Structure and interpretation of Computer Programs](https://web.mit.edu/alexmv/6.037/sicp.pdf) (free) 📖: One of the most influential textbooks in Computer Science (written and used at MIT), SICP has been influential in CS education. [Byte](https://en.wikipedia.org/wiki/Byte_(magazine)) recommended SICP "for professional programmers who are really interested in their profession".

There are some free books available, including:

* [Professional software development](http://mixmastamyk.bitbucket.io/pro_soft_dev/) 📖: pretty complete and a good companion to this page. The free chapters are mostly focused on software development processes: design, testing, code writing, etc. - and not so much about tech itself.
* [List of free programming books](https://github.com/vhf/free-programming-books)

## Must-read articles

* [Practical Advice for New Software Engineers](http://product.hubspot.com/blog/practical-advice-for-new-software-engineers)
* [On Being A Senior Engineer](http://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
* [Lessons Learned in Software Development](http://henrikwarne.com/2015/04/16/lessons-learned-in-software-development/): one of those articles that give you years of hard-earned lessons, all in one short article. Must read.
* [Things I Learnt The Hard Way](https://blog.juliobiason.me/thoughts/things-i-learnt-the-hard-way/)
	* Spec first, then code
	* Tests make better APIs
	* Future thinking is future trashing
	* Documentation is a love letter to your future self
	* Sometimes, it's better to let the application crash than do nothing
	* Understand and stay away of cargo cult
	* "Right tool for the job" is just to push an agenda
	* Learn the basics functional programming
	* ALWAYS use timezones with your dates
	* ALWAYS use UTF-8
	* Create libraries
	* Learn to monitor
	* Explicit is better than implicit
	* Companies look for specialists but keep generalists longer
	* The best secure way to deal with user data is not to capture it
	* When it's time to stop, it's time to stop
	* You're responsible for the use of your code
	* Don't tell "It's done" when it's not
	* Pay attention on how people react to you
	* Beware of micro-aggressions
	* Keep a list of "Things I Don't Know"
* [Signs that you're a good programmer](http://www.yacoset.com/Home/signs-that-you-re-a-good-programmer)
* [Signs that you're a bad programmer](http://www.yacoset.com/Home/signs-that-you-re-a-bad-programmer)
* [7 absolute truths I unlearned as junior developer](https://monicalent.com/blog/2019/06/03/absolute-truths-unlearned-as-junior-developer/)
	* Early in your career, you can learn 10x more in a supportive team in 1 year, than coding on your own
	* Every company has problems, every company has technical debt.
	* Being overly opinionated on topics you lack real-world experience with is pretty arrogant.
	* Many conference talks cover proof of concepts rather than real-world scenarios.
	* Dealing with legacy is completely normal.
	* Architecture is more important than nitpicking.
	* Focus on automation over documentation where appropriate.
	* Having some technical debt is healthy.
	* Senior engineers must develop many skills besides programming.
	* We’re all still junior in some areas.
* [How to Build Good Software](https://www.csc.gov.sg/articles/how-to-build-good-software)
	* A good high-level summary of fundamental engineering practices.
	* The root cause of bad software has less to do with specific engineering choices, and more to do with how development projects are managed.
	* There is no such thing as platonically good engineering: it depends on your needs and the practical problems you encounter.
	* Software should be treated not as a static product, but as a living manifestation of the development team’s collective understanding.
	* Software projects rarely fail because they are too small; they fail because they get too big.
	* Beware of bureaucratic goals masquerading as problem statements. If our end goal is to make citizens’ lives better, we need to explicitly acknowledge the things that are making their lives worse.
	* Building software is not about avoiding failure; it is about strategically failing as fast as possible to get the information you need to build something good.

## Other general material and list of resources

* [The Imposter's Handbook](https://bigmachine.io/products/the-imposters-handbook) - $30. From the author: "Don't have a CS Degree? Neither do I - That's why I wrote this book."
* [mr-mig/every-programmer-should-know: a collection of (mostly) technical things every software developer should know](https://github.com/mr-mig/every-programmer-should-know)
* [Famous Laws Of Software Development](https://www.timsommer.be/famous-laws-of-software-development/)
* [The Amazon Builders' Library](https://aws.amazon.com/builders-library/?cards-body.sort-by=item.additionalFields.customSort&cards-body.sort-order=asc)

List of axioms:

* [Precepts - Urbit](https://urbit.org/blog/precepts/)
	* Data is better than code.
	* Correctness is more important than performance.
	* Deterministic beats heuristic.
	* One hundred lines of simplicity is better than twenty lines of complexity.
	* If your abstractions are leaking, it's not due to some law of the universe; you just suck at abstracting. Usually, you didn't specify the abstraction narrowly enough.
	* If you avoid changing a section of code for fear of awakening the demons therein, you are living in fear. If you stay in the comfortable confines of the small section of the code you wrote or know well, you will never write legendary code. All code was written by humans and can be mastered by humans.
	* If there's clearly a right way to do something and a wrong way, do it the right way. Coding requires incredible discipline.
	* The best way to get the right answer is to try it the wrong way.
	* Practice tells you that things are good or bad; theory tells you why.
	* Not being qualified to solve a problem is no reason not to solve it.
	* If you don't understand a system you're using, you don't control it. If nobody understands the system, the system is in control.

### Courses

* [Google Tech Dev Guide](https://techdevguide.withgoogle.com/)
* [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/), MIT. Includes lectures about the shell, editors, data wrangling, git, debugging and profiling, meta programming, security and cryptography.
* [Mathematics for the adventurous self-learner](https://www.neilwithdata.com/mathematics-self-learner), Neil Sainsbury

## Topics

### Algorithm and data structures

* Read the [CLRS](https://mitpress.mit.edu/books/introduction-algorithms). You can watch and download the course on [OCW](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-introduction-to-algorithms-sma-5503-fall-2005/) - there are newer courses as well.
* Or [The Algorithm Design Manual](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202?ie=UTF8&qid=1297127794&ref_=sr_1_1&sr=8-1)
* Try out some algorithms on [Project Euler](https://projecteuler.net/)

Let's be honest: algorithms can be a pretty dry topic. [This quora question](https://www.quora.com/Is-there-a-book-that-teaches-algorithms-data-structures-and-other-computer-science-basics-in-a-fun-way) lists some funnier learning alternative, including:

* [Grokking Algorithms](https://www.amazon.com/dp/1617292230/ref=cm_sw_su_dp)
* [Essential Algorithms](https://www.amazon.com/Essential-Algorithms-Practical-Approach-Computer/dp/1118612108?ie=UTF8&*Version*=1&*entries*=0)

Example implementations:

* [trekhleb/javascript-algorithms: Algorithms and data structures implemented in JavaScript](https://github.com/trekhleb/javascript-algorithms)

### API design & development

* [Why you should use links, not keys, to represent relationships in APIs](https://cloud.google.com/blog/products/application-development/api-design-why-you-should-use-links-not-keys-to-represent-relationships-in-apis), Martin Nally, Google
	* "Using links instead of foreign keys to express relationships in APIs reduces the amount of information a client needs to know to use an API, and reduces the ways in which clients and servers are coupled to each other."
* [A collection of useful resources for building RESTful HTTP+JSON APIs.](https://github.com/yosriady/api-development-tools)

### Attitude, habits, mindset

* [Mastering Programming](https://www.prod.facebook.com/notes/kent-beck/mastering-programming/1184427814923414#), Kent Beck.
* [The traits of a proficient programmer](https://www.oreilly.com/ideas/the-traits-of-a-proficient-programmer)
* [The tao of programming](http://www.mit.edu/~xela/tao.html): a set of parables about programming.
* [Taking Ownership Is The Most Effective Way to Get What You Want](http://www.theeffectiveengineer.com/blog/take-ownership-of-your-goals)
* [Finding Time to Become a Better Developer](https://medium.freecodecamp.org/finding-time-to-become-a-better-developer-eebc154881b2)
* [Ten minutes a day](https://blog.usejournal.com/ten-minutes-a-day-e2fa1084f924): how Alex Allain wrote a book in less than 200 hours, by writing 10 minutes *every* day.
* [The care and feeding of software engineers (or, why engineers are grumpy)](https://humanwhocodes.com/blog/2012/06/12/the-care-and-feeding-of-software-engineers-or-why-engineers-are-grumpy/)
  * In the triumvirate of software, product managers, designers, and software engineers, only the engineers are expected to turn off their creative minds and just produce.
  * Both engineers and product managers tend to think, incorrectly, that product specifications or requirements are equivalent to the furniture manual from Ikea.
  * This is one of the top things that make engineers grumpy: constantly shifting priorities.
  * Even though many engineers will complain that product managers change their minds, almost none will account for that in their time estimates.
  * Computer science programs aren’t about preparing you for the tasks you’ll face in industry.
  * When there are more engineers than can be used, engineering time ends up going away from developing and towards planning, synchronization, and coordination.
  * Involve engineers in the creative process
  * Give engineers opportunities to be creative.
  * Encourage time off.
  * Let 'em code
  * Express appreciation
* [The Product-Minded Software Engineer](https://blog.pragmaticengineer.com/the-product-minded-engineer/), Gergely Orosz
  * Great product engineers know that minimum lovable products need the right depth
  * Product-minded engineers quickly map out edge cases and think of ways to reduce work on them: often bringing solutions that require no engineering work
  * Engage in user research and customer support
  * Bring well-backed product suggestions to the table
  * Offer product/engineering tradeoffs
* [40 Lessons From 40 Years](https://medium.com/@schlaf/40-lessons-from-40-years-de39d2c622d6), Steve Schlafman
	* If you want to make progress on the things that matter most, you need to decide who you’re going to disappoint. It’s inevitable.
	* The best investment you can make is your own education. Never stop learning. The second best investment you can make is building your network through authentic and meaningful interactions. It is what you know and who you know.
	* You’ll never get what you don’t ask for or actively seek out. Go for it!
	* It’s not about the light at the end of the tunnel. It’s the tunnel. Show up every day and enjoy the process.
	* A great teammate always puts the organization and its purpose ahead of their own self interests.
	* Pick your spots. We have limited time and our brains can only process so much. Focus is key. Choose wisely.
	* Every person is likely struggling with something. Be kind. Be helpful.
* [On Coding, Ego and Attention](https://josebrowne.com/on-coding-ego-and-attention/)
  * Beginner’s mind accepts the fact that absolute knowledge is infinite and thus keeping score is a waste of time.
  * Mastery is simply the accumulation of momentum, not the accumulation of knowledge.
  * Dealing with ego distraction has taught me to love the problem solving process. It’s taught me to love and respect the learning process. As a result I’m more productive. I’m less anxious. I’m a better teammate. I’m a better friend and a better thinker.

### Automation

* [Automation Should Be Like Iron Man, Not Ultron](http://queue.acm.org/detail.cfm?id=2841313)

### Biases

Biases don't only apply to hiring. For instance, the fundamental attribution bias also applies when criticizing somebody's code written a long time ago, in a totally different context.

* [Cognitive bias cheat sheet](https://betterhumans.coach.me/cognitive-bias-cheat-sheet-55a472476b18#.6temb6hyg). #hiring

### Career growth

* [The Conjoined Triangles of Senior-Level Development](http://frontside.io/blog/2016/07/07/the-conjoined-triangles-of-senior-level-development.html) looks into how to define a senior engineer.
* [Ten Principles for Growth as an Engineer](https://medium.com/@daniel.heller/ten-principles-for-growth-69015e08c35b), Dan Heller.
* [Don't Call Yourself a Programmer](https://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/), Patrick McKenzie.
* [On being an Engineering Manager](https://nickmchardy.com/2019/02/on-being-an-engineering-manager.html)
* [The career advice I wish I had at 25](https://www.linkedin.com/pulse/career-advice-i-wish-had-25-shane-rodgers/?trk=hp-feed-article-title-like)
	* A career is a marathon, not a sprint
	* Most success comes from repetition, not new things
	* If work was really so great all the rich people would have the jobs
	* Management is about people, not things
	* Genuinely listen to others
	* Recognise that staff are people with finite emotional capacity
	* Don’t just network with people your own age
	* Never sacrifice personal ethics for a work reason
	* Recognise that failure is learning
* [Career advice I wish I’d been given when I was young](https://80000hours.org/2019/04/career-advice-i-wish-id-been-given-when-i-was-young/)
	* Don’t focus too much on long-term plans.
	* Find good thinkers and cold-call the ones you most admire.
	* Assign a high value to productivity over your whole lifespan.
	* Don’t over-optimise things that aren’t your top priority.
	* Read a lot, and read things that people around you aren’t reading.
	* Reflect seriously on what problem to prioritise solving.
	* Read more history.
* [Why Good Developers are Promoted into Unhappiness](https://robwalling.com/2007/06/27/why-good-developers-are-promoted-into-unhappiness/), Rob Walling. Or why management might not be for you.
* [A guide to using your career to help solve the world’s most pressing problems](https://80000hours.org/key-ideas/)


### Characters sets

* [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](http://www.joelonsoftware.com/articles/Unicode.html)

### Code reviews

* [How to do a code review](https://google.github.io/eng-practices/review/reviewer/), Google's engineering practices documentation.

### Coding & code quality

* [Write code that is easy to delete, not easy to extend](http://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)
* [The Ten Commandments of Egoless Programming](http://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/)
* [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.goodreads.com/book/show/3735293-clean-code) 📖, Robert C. Martin. Describes numerous useful best practices. A bit long. There's also a [clean code cheatsheet](cheatsheets/Clean-Code-V2.4.pdf).
* [What Software Craftsmanship is about](https://blog.cleancoder.com/uncle-bob/2011/01/17/software-craftsmanship-is-about.html)
	* We’re tired of writing crap.
	* We will not accept the stupid old lie about cleaning things up later.
	* We will not believe the claim that quick means dirty.
	* We will not allow anyone to force us to behave unprofessionally.
* [Tips on naming boolean variables](https://dev.to/michi/tips-on-naming-boolean-variables-cleaner-code-35ig)
  * There is a convention to prefix boolean variables and function names with "is" or "has".
  * Try to always use is, even for plurals (`isEachUserLoggedIn` is better than `areUsersLoggedIn` or `isUsersLoggedIn`)
  * Avoid custom prefixes (`isPaidFor` is better than `wasPaidFor`)
  * Avoid negatives (`isEnabled` is better than `isDisabled`)

### Computer science

* [What every computer science major should know](http://matt.might.net/articles/what-cs-majors-should-know/)
* [Teach Yourself Computer Science](https://teachyourselfcs.com/): an opinionated set of the best CS resources.

### Configuration

* [The downsides of JSON for config files](https://arp242.net/weblog/JSON_as_configuration_files-_please_dont.html), Martin Tournoij.
	* Can't add comments
	* Excessive quotation and syntax noise
	* Using DC (declarative configuration) to control logic is often not a good idea.
* [Your configs suck? Try a real programming language](https://beepb00p.xyz/configs-suck.html)
  * Most modern config formats suck
  * Use a real programming language

### Databases

* [A plain english introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem/)
* [NOSQL Patterns](http://horicky.blogspot.nl/2009/11/nosql-patterns.html)
* [NoSQL Databases: a Survey and Decision Guidance](https://medium.baqend.com/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.9fe79qr90)
* [Safe Operations For High Volume PostgreSQL](https://www.braintreepayments.com/blog/safe-operations-for-high-volume-postgresql/) (this is for PostgreSQL but works great for other DBs as well).
* [Zero downtime database migrations](https://blog.rainforestqa.com/2014-06-27-zero-downtime-database-migrations/) (code examples are using Rails but this works great for any programming language)
* [SQL styleguide](http://www.sqlstyle.guide/)
* [Algorithms Behind Modern Storage Systems](https://queue.acm.org/detail.cfm?id=3220266), ACM Queue
* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)

### Data formats

* [Falsehoods Programmers Believe About Phone Numbers](https://github.com/googlei18n/libphonenumber/blob/master/FALSEHOODS.md), Google's `libphonenumber`.
* [Rules for Autocomplete](http://jeremymikkola.com/posts/2019_03_19_rules_for_autocomplete.html): rough specifications for autocomplete fields

### Data science

* [A dirty dozen: twelve common metric interpretation pitfalls in online controlled experiments](https://blog.acolyer.org/2017/09/25/a-dirty-dozen-twelve-common-metric-interpretation-pitfalls-in-online-controlled-experiments/)

### Debugging

* [Rubber Duck Problem Solving](http://blog.codinghorror.com/rubber-duck-problem-solving/)
* [Rubber Ducking](http://c2.com/cgi/wiki?RubberDucking)
* [Five Whys](https://en.wikipedia.org/wiki/5_Whys)
* [The Infinite Hows](http://www.kitchensoap.com/2014/11/14/the-infinite-hows-or-the-dangers-of-the-five-whys/): this provides a strong criticism of the five whys method.
* [Linux Performance Analysis in 60,000 Milliseconds](http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html)

### Design (visual, UX, UI)

I highly recommend reading [The Non-Designer's Design Book](http://www.amazon.com/gp/product/0133966151/ref=pd_lpo_sbs_dp_ss_1?pf_rd_p=1944687602&pf_rd_s=lpo-top-stripe-1&pf_rd_t=201&pf_rd_i=0321534042&pf_rd_m=ATVPDKIKX0DER&pf_rd_r=1R7MVQP0BCP7GP9VZGYX). This is a pretty short book that will give you some very actionable design advices.

* If you're working on data, Edward Tufte's [The Visual Display of Quantitative Information](http://www.amazon.com/Visual-Display-Quantitative-Information/dp/0961392142/ref=sr_1_1?ie=UTF8&qid=1458046603&sr=8-1&keywords=tufte) is considered a classic.
* The [Universal Principles of Design](http://www.amazon.com/Universal-Principles-Design-Revised-Updated/dp/1592535879/ref=sr_1_1?ie=UTF8&qid=1458046663&sr=8-1&keywords=universal+principles+of+design) will give you enough vocabulary and concepts to describe design challenges into words.
* [Microsoft's Rest API guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)
* [Book recommendations from HackerNews](https://news.ycombinator.com/item?id=12711060)

Articles :

* [10 Usability Heuristics Every Designer Should Know](https://uxdesign.cc/10-usability-heuristics-every-designer-should-know-129b9779ac53)
	* Visibility of System Status
	* The Match Between The System And The Real World
	* Every system should have a clear emergency exit
	* Don't forget that people spend 90% of their time interacting with other apps
	* Recognition Rather Than Recall (recognition = shallow form of retrieval from memory, e.g. a familiar person, recall = deeper retrieval)
	* ”Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.” – Antoine de Saint-Exupery
	* Help Users Recognize, Diagnose, And Recover From Errors

### Design (OO modeling, architecture, patterns, anti-patterns, etc.)

Here's a list of good books:

* 📖 [Design Patterns: Elements of Reusable Object-Oriented Software](http://www.amazon.com/dp/0201633612/): dubbed "the gang of four", this is almost a required reading for any developer. A lot of those are a bit overkill for Python (because everything is an object, and dynamic typing), but the main idea (composition is better than inheritance) definitely is a good philosophy.
* 📖 [Patterns of Enterprise Application Architecture](http://www.amazon.com/dp/0321127420/?tag=stackoverfl08-20): learn about how database are used in real world applications. Mike Bayer's SQLAlchemy has been heavily influenced by this book.
* 📖 [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215), Eric Evans
* 📖 [Clean Architecture](https://www.goodreads.com/book/show/18043011-clean-architecture), Robert C. Martin. Uncle Bob proposes an architecture that leverages the Single Responsibility Principle to its fullest. A great way to start a new codebase. Also checkout the [clean architecture cheatsheet](cheatsheets/Clean-Architecture-V1.0.pdf).

One of the absolute references on architecture is Martin Fowler: checkout his [Software Architecture Guide](https://martinfowler.com/architecture/).

Articles:

* O'Reilly's [How to make mistakes in Python](http://www.oreilly.com/programming/free/files/how-to-make-mistakes-in-python.pdf)
* [Education of a Programmer](https://hackernoon.com/education-of-a-programmer-aaecf2d35312): a developer's thoughts after 35 years in the industry. There's a particularly good section about design & complexity (see "the end to end argument", "layering and componentization").
* Google's [API Design Guide](https://cloud.google.com/apis/design/): a general guide to design networked API.
* [Domain-driven design](https://en.wikipedia.org/wiki/Domain-driven_design), Wikipedia.
* [On the Spectrum of Abstraction](https://www.youtube.com/watch?v=mVVNJKv9esE) 🎞, Cheng Lou
* [The “Bug-O” Notation](https://overreacted.io/the-bug-o-notation/), Dan Abramov

I maintain a [list of antipatterns](https://github.com/charlax/antipatterns) on another repo. This is a highly recommended read.

* [Inheritance vs. composition](http://learnpythonthehardway.org/book/ex44.html): a concrete example in Python. [Another slightly longer one here](http://python-textbok.readthedocs.io/en/latest/Object_Oriented_Programming.html). [One last one, in Python 3](http://blog.thedigitalcatonline.com/blog/2014/08/20/python-3-oop-part-3-delegation-composition-and-inheritance/#.V7SZ4tB96Rs).
* [Composition Instead Of Inheritance](http://c2.com/cgi/wiki?CompositionInsteadOfInheritance)
* [Complexity and Strategy](https://hackernoon.com/complexity-and-strategy-325cd7f59a92): interesting perspective on complexity and flexibility with really good examples (e.g. Google Apps Suite vs. Microsoft Office).

> You can use an eraser on the drafting table or a sledge hammer on the construction site. (Frank Lloyd Wright)

#### Design: database schema

* [A humble guide to database schema design](https://www.mikealche.com/software-development/a-humble-guide-to-database-schema-design), Mike Alche
	* Use at least third normal form
	* Create a last line of defense with constraints
	* Never store full addresses in a single field
	* Never store firstname and lastname in the same field
	* Establish conventions for table and field names.

#### Design: patterns

* [KeystoneInterface](https://martinfowler.com/bliki/KeystoneInterface.html), Martin Fowler.
	* Build all the back-end code, integrate, but don't build the user-interface
* [101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)
* [Python Design Patterns: For Sleek And Fashionable Code](https://www.toptal.com/python/python-design-patterns): a pretty simple introduction to common design patterns (Facade, Adapter, Decorator). A more complete list of design patterns implementation in Python on [Github](https://github.com/faif/python-patterns). [Also a book here](http://python-3-patterns-idioms-test.readthedocs.io/en/latest/PatternConcept.html).
* SourceMaking's [Design Patterns](https://sourcemaking.com/design_patterns) seems to be a good web resource too.
* [Anti-If: The missing patterns](https://code.joejag.com/2016/anti-if-the-missing-patterns.html)

#### Design: simplicity

* [Simple Made Easy](https://www.infoq.com/presentations/Simple-Made-Easy) 🎞, Rich Hickey. This is an incredibly inspiring talk redefining simplicity, ease and complexity, and showing that solutions that look easy may actually harm your design.

### Dev environment & tools

* [Awesome Dev Env](https://github.com/jondot/awesome-devenv)

Tools

* [Glances: An eye on your system](https://github.com/nicolargo/glances)
* [HTTPie: a CLI, cURL-like tool for humans](https://github.com/jkbrzt/httpie)
* [jq: command-line JSON processor](https://stedolan.github.io/jq/)
* [tmux: terminal multiplexer](http://tmux.github.io/)
* [htop: an interactive process viewer for Linux](http://hisham.hm/htop/)
* [htop explained](https://peteris.rocks/blog/htop/)

### Diversity & inclusion

Check out my [list of management
resources](https://github.com/charlax/engineering-management).

### Documentation

* [Documentation-Driven Development](https://gist.github.com/zsup/9434452)
* [Writing automated tests for your documentation](https://krausefx.com/blog/writing-automated-tests-for-your-documentation): this should be required, IMO. Testing code samples in your documentation ensures they never get outdated.
* 🎤 [Documentation is king](https://speakerdeck.com/kennethreitz/documentation-is-king), Kenneth Reitz
* [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
* [Architectural Decision Records](https://adr.github.io/): a way to document architecture decision.

### Dotfiles

* [Awesome dotfiles](https://github.com/webpro/awesome-dotfiles): lots of great dotfiles.
* [My dotfiles](https://github.com/charlax/dotfiles)

Articles

* [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449)

### Editors & IDE

* [Sublime Text essential plugins and resources](https://github.com/dreikanter/sublime-bookmarks)
* [vim-awesome](http://vimawesome.com/)
* Bram Moolenaar (Vim author), [Seven habits of effective text editing](http://www.moolenaar.net/habits.html) ([presentation](http://www.moolenaar.net/habits_2007.pdf)). This is about Vim but it contains good lessons about why investing time in learning how to be productive with your text editors pays off.
* [VScode](https://code.visualstudio.com/) is one of the most popular text editors as of writing. [Visual Studio Code Can Do That?](https://www.smashingmagazine.com/2018/01/visual-studio-code/), Smashing Magazine.

### Engineering management

Checkout my [list of management
resources](https://github.com/charlax/engineering-management).

### Exercises

The best way to learn is to learn by doing.

* [danistefanovic/build-your-own-x: build your own (insert technology here)](https://github.com/danistefanovic/build-your-own-x)
* [The elevator programming game](http://play.elevatorsaga.com/)
* [Challenging projects every programmer should try](http://web.eecs.utk.edu/~azh/blog/challengingprojects.html): text editor, space invaders, compiler (Tiny Basic), mini OS, spreadsheet, video game console emulator.

### Incident response (oncall, alerting, outages, firefighting, postmortem)

* [Incident Response at Heroku](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)
* [My Philosophy On Alerting](https://linuxczar.net/sysadmin/philosophy-on-alerting/)
  * Pages should be urgent, important, actionable, and real.
  * Err on the side of removing noisy alerts – over-monitoring is a harder problem to solve than under-monitoring.
  * Symptoms are a better way to capture more problems more comprehensively and robustly with less effort.
  * Include cause-based information in symptom-based pages or on dashboards, but avoid alerting directly on causes.
  * The further up your serving stack you go, the more distinct problems you catch in a single rule. But don’t go so far you can’t sufficiently distinguish what’s going on.
  * If you want a quiet oncall rotation, it’s imperative to have a system for dealing with things that need timely response, but are not imminently critical.
* The Google SRE book's [chapter about oncall](https://landing.google.com/sre/workbook/chapters/on-call/)
* [Writing Runbook Documentation When You’re An SRE](https://www.transposit.com/blog/2020.01.30-writing-runbook-documentation-when-youre-an-sre/)
  * Playbooks “reduce stress, the mean time to repair (MTTR), and the risk of human error.”
  * Using a template can be beneficial because starting from a blank document is incredibly hard.
  * The Curse of Knowledge is a cognitive bias that occurs when someone is communicating with others and unknowingly assumes the level of knowledge of the people they are communicating with.
  * Make your content easy to glance over.
  * If a script is longer than a single line, treat it like code, and check it into a repository to be source control and potentially tested.

#### Postmortem

* A great example of a [postmortem from Gitlab (01/31/2017)](https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/) for an outage during which an engineer's action caused the irremediable loss of 6 hours of data.
* [Blameless PostMortems and a Just Culture](https://codeascraft.com/2012/05/22/blameless-postmortems/)
* [A list of postmortems on Github](https://github.com/danluu/post-mortems)
* Google's SRE book, [Postmortem chapter](https://landing.google.com/sre/workbook/chapters/postmortem-culture/) is excellent and includes many examples.

Dan Milstein, “Let’s plan for a future where we’re all as stupid as we are today.”

### Internet

* [How Does the Internet Work?](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
* [How the web works](https://github.com/vasanthk/how-web-works)

### Interviewing

Note: this is about you as an interviewee, **not** as an interviewer. To check out my list of resources for interviewers, go to my [engineering-management repository](https://github.com/charlax/engineering-management#hiring-interviews).

* [System design interview for IT company](https://github.com/checkcheckzz/system-design-interview)
* [Technical Interview Megarepo](https://github.com/jdsutton/Technical-Interview-Megarepo): study materials for SE/CS technical interviews
* [How to Win the Coding Interview](https://medium.com/on-writing-code/how-to-win-the-coding-interview-71ae7102d685)
* [I spent 3 months applying to jobs after a coding bootcamp. Here’s what I learned.](https://medium.freecodecamp.com/5-key-learnings-from-the-post-bootcamp-job-search-9a07468d2331#.uq7vbbjfx)
* [Top 10 algorithms in Interview Questions](http://www.geeksforgeeks.org/top-10-algorithms-in-interview-questions/)
* [Questions to ask your interviewer](https://rkoutnik.com/articles/Questions-to-ask-your-interviewer.html)
* [Interactive Python coding interview challenges](https://github.com/donnemartin/interactive-coding-challenges)
* [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/introduction/)
* [Questions to ask the company during your interview](https://github.com/viraptor/reverse-interview)
* [A complete computer science study plan to become a software engineer](https://github.com/jwasham/coding-interview-university), jwasham/coding-interview-university

See also the exercises section in this document.

### Learning & memorizing

Learn how to learn!

* [How I Rewired My Brain to Become Fluent in Math](http://nautil.us/issue/40/learning/how-i-rewired-my-brain-to-become-fluent-in-math-rp): subtitled *the building blocks of understanding are memorization and repetition*.
* [One Sure-Fire Way to Improve Your Coding](https://changelog.com/posts/one-sure-fire-way-to-improve-your-coding): reading code!
* [Tips for learning programming](http://blog.hiphipjorge.com/tips-for-learning-programming/)
* [You can increase your intelligence: 5 ways to maximize your cognitive potential](https://blogs.scientificamerican.com/guest-blog/you-can-increase-your-intelligence-5-ways-to-maximize-your-cognitive-potential/): forgive the clickbait title, it’s actually a good article.
* [How to ask good questions](https://jvns.ca/blog/good-questions/), Julia Evans.
* [Stop Learning Frameworks](https://sizovs.net/2018/12/17/stop-learning-frameworks/)
* [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn): powerful mental tools to help you master tough subjects
* [Why books don’t work](https://andymatuschak.org/books/), Andy Matuschak.
	* "As a medium, books are surprisingly bad at conveying knowledge, and readers mostly don’t realize it."
	* "In learning sciences, we call this model “transmissionism.” It’s the notion that knowledge can be directly transmitted from teacher to student, like transcribing text from one page onto another. If only!"
	* "By re-testing yourself on material you’ve learned over expanding intervals, you can cheaply and reliably commit huge volumes of information to long-term memory."
* [Strategies, Tips, and Tricks for Anki](https://senrigan.io/blog/everything-i-know-strategies-tips-and-tricks-for-spaced-repetition-anki/): those advices work for any tool actually
	* Add images. Our brains are wired visually, so this helps retention.
	* Don't add things you don't understand.
	* Don't add cards memorizing entire lists.
	* Write it out. For wrong answers, I'll write it on paper. The act of writing is meditative. I really enjoy this.
	* Keep on asking yourself why? why does this work? why does it work this way? Force yourself to understand the root of a topic.
	* Cornell Method: when reading a topic, write out questions on the margins to quiz yourself.
	* Pretend you have to teach it
	* Use mnemonics phrases like PEMDAS for lists and other hard-to-remember topics.
	* Delete cards that don't make sense or you don't want to remember anymore.
* [Effective learning: Twenty rules of formulating knowledge](https://www.supermemo.com/en/archives1990-2015/articles/20rules)
	* Build upon the basics
	* Stick to the minimum information principle: the material you learn must be formulated in as simple way as it is
	* Cloze deletion is easy and effective: Kaleida's mission was to create a ... It finally produced one, called Script X. But it took three years
	* Graphic deletion is as good as cloze deletion
	* Avoid sets
	* Avoid enumerations
	* Combat interference - even the simplest items can be completely intractable if they are similar to other items. Use examples, context cues, vivid illustrations, refer to emotions, and to your personal life
	* Personalize and provide examples - personalization might be the most effective way of building upon other memories. Your personal life is a gold mine of facts and events to refer to. As long as you build a collection for yourself, use personalization richly to build upon well established memories
	* Provide sources - sources help you manage the learning process, updating your knowledge, judging its reliability, or importance
	* Prioritize - effective learning is all about prioritizing.
* [How to Remember Anything You Really Want to Remember, Backed by Science](https://www.inc.com/jeff-haden/how-to-remember-anything-you-really-want-to-remember-backed-by-science.html)
	* Quiz yourself
	* Summarize and share with someone else.
	* Connect what you just learned to experiences you previously had.

Richard Feynman's Learning Strategy:

1. Step 1: Continually ask "Why?”
2. Step 2: When you learn something, learn it to where you can explain it to a child.
3. Step 3: Instead of arbitrarily memorizing things, look for the explanation that makes it obvious.

> Most people overestimate what they can do in 1 year and underestimate what they can do in a decade.
> – Bill Gates

> Frankly, though, I think most people can learn a lot more than they think they can. They sell themselves short without trying.
> One bit of advice: it is important to view knowledge as sort of a semantic tree — make sure you understand the fundamental principles, ie the trunk and big branches, before you get into the details/leaves or there is nothing for them to hang on to.
> — Elon Musk

> "Experience is something you don't get until just after you need it."
> ― Steven Wright

### Low-level

* [Back to Basics](https://www.joelonsoftware.com/2001/12/11/back-to-basics/), Joel Spolsky. Explains why learning low level programming is important.
	* I think that some of the biggest mistakes people make even at the highest architectural levels come from having a weak or broken understanding of a few simple things at the very lowest levels.

### Network

* [The Great Confusion About URIs](https://benbernardblog.com/the-great-confusion-about-uris/)
	* A URI is a string of characters that identifies a resource. Its syntax is `<scheme>:<authority><path>?<query>#<fragment>`, where only `<scheme>` and `<path>` are mandatory. URL and URN are URIs.
	* A URL is a string of characters that identifies a resource located on a computer network. Its syntax depends on its scheme. E.g. `mailto:billg@microsoft.com`.
	* A URN is a string of characters that uniquely identifies a resource. Its syntax is `urn:<namespace identifier>:<namespace specific string>`. E.g. `urn:isbn:9780062301239`

### Observability (monitoring, logging, exception handling)

#### Logging

* [Do not log](https://sobolevn.me/2020/03/do-not-log) dwells on some logging antipatterns.
	* Logging does not make much sense in monitoring and error tracking. Use better tools instead: error and business monitorings with alerts, versioning, event sourcing.
	* Logging adds significant complexity to your architecture. And it requires more testing. Use architecture patterns that will make logging an explicit part of your contracts
	* Logging is a whole infrastructure subsystem on its own. And quite a complex one. You will have to maintain it or to outsource this job to existing logging services

#### Error/exception handling

* [Error handling antipattners](https://github.com/charlax/antipatterns/blob/master/error-handling-antipatterns.md) in my antipatterns repo.

#### Monitoring

* Google, [Site Reliability Engineering, Monitoring Distributed Systems](https://landing.google.com/sre/sre-book/chapters/monitoring-distributed-systems/)
* PagerDuty, [Monitoring Business Metrics and Refining Outage Response](https://www.pagerduty.com/blog/monitoring-business-metrics/)

### Problem solving

* [Dealing with Hard Problems](https://artofproblemsolving.com/articles/hard-problems)

### Project management

See [Project management section on my engineering-management list of resources](https://github.com/charlax/engineering-management#project-management).

### Programming languages

I would recommend learning:

* JavaScript and maybe another interpreted language (Python, Ruby, etc.). Interpreted languages are useful for quick one-off automation scripts, and fastest to write for interviews. JavaScript is ubiquitous.
* A compiled language (Java, C, C++...).
* A more recent language to see where the industry is going (as of writing, Go, Swift, Rust, Elixir...).
* A language that has first-class support for functional programming (Haskell, Scala, Clojure...).

A bit more reading:

* [A brief, incomplete, mostly wrong history of programming languages](http://james-iry.blogspot.fr/2009/05/brief-incomplete-and-mostly-wrong.html)
* [Types](https://gist.github.com/garybernhardt/122909856b570c5c457a6cd674795a9c)
* [Resources To Help You To Create Programming Languages](https://tomassetti.me/resources-create-programming-languages/)
* [Effective Programs - 10 Years of Clojure](https://www.youtube.com/watch?v=2V1FtfBDsLU) 🎞, Rich Hickey. The author of Clojure reflects on his programming experience and explains the rationale behind some of Clojure's key design decisions.
* [Learn more programming languages, even if you won't use them](https://thorstenball.com/blog/2019/04/09/learn-more-programming-languages/), Thorsten Ball
	* These new perspectives, these ideas and patterns — they linger, they stay with you, even if you end up in another language. And that is powerful enough to keep on learning new languages, because one of the best things that can happen to you when you’re trying to solve a problem is a change of perspective.
* [Programming Language Checklist](https://famicol.in/language_checklist.html):
  a fun take on "so you want to build your own language?"

> There are only two kinds of languages: the ones people complain about and the ones nobody uses.

-- Bjarne Stroustrup (C++ creator)

#### Python

For Python feel free to checkout my [professional Python education repository](https://github.com/charlax/python-education).

#### JavaScript

JavaScript is such a pervasive language that it's almost required learning.

* [mbeaudru/modern-js-cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet): cheatsheet for the JavaScript knowledge you will frequently encounter in modern projects.

#### Functional programming

* [Jargon from the functional programming world](https://github.com/hemanth/functional-programming-jargon)
* [Goodbye, Object Oriented Programming](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53#.39ax09e4k)
* [Functional Programming & Haskell](https://www.youtube.com/watch?v=LnX3B9oaKzw): some good reasons to learn FP!
* [Functional Programming Fundamentals](https://www.matthewgerstman.com/functional-programming-fundamentals/): short introduction to FP and its advantages.
* [OO vs FP](https://blog.cleancoder.com/uncle-bob/2014/11/24/FPvsOO.html), Robert C. Martin, The Clean Code Blog. A pretty interesting take on the differences between OOP and FP from an expert in OOP.
	* OO is not about state. Objects are bags of functions, not bags of data.
	* Functional Programs, like OO Programs, are composed of functions that operate on data.
	* FP imposes discipline upon assignment.
	* OO imposes discipline on function pointers.
	* The principles of software design still apply, regardless of your programming style. The fact that you’ve decided to use a language that doesn’t have an assignment operator does not mean that you can ignore the Single Responsibility Principle.
* [Parse, don’t validate](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)
  * Use a data structure that makes illegal states unrepresentable
  * Push the burden of proof upward as far as possible, but no further
  * Let your datatypes inform your code, don’t let your code control your datatypes
  * Don’t be afraid to parse data in multiple passes
  * Avoid denormalized representations of data, especially if it’s mutable
  * Use abstract datatypes to make validators “look like” parsers

### Programming paradigm

* [Imperative vs Declarative Programming](https://tylermcginnis.com/imperative-vs-declarative-programming/), Tyler McGinnis.
	* I draw the line between declarative and non-declarative at whether you can trace the code as it runs. Regex is 100% declarative, as it’s untraceable while the pattern is being executed.

### Over-engineering

* [10 modern software over-engineering mistakes](https://medium.com/@rdsubhas/10-modern-software-engineering-mistakes-bc67fbef4fc8#.da6dvzyne)
* [A good example of over-engineering: the Juicero press](https://blog.bolt.io/heres-why-juicero-s-press-is-so-expensive-6add74594e50) (April 2017)

> “A complex system that works is invariably found to have evolved from a simple system that worked. A complex system designed from scratch never works and cannot be patched up to make it work. You have to start over, beginning with a working simple system.”

John Gall, General systemantics, an essay on how systems work, and especially how they fail..., 1975 (this quote is sometime referred as "Galls' law")

> "Software engineering is what happens to programming
> when you add time and other programmers."

Rob Pike, [Go at Google: Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article)

### Reading

* [Papers we love](https://github.com/papers-we-love/papers-we-love): papers from the computer science community to read and discuss. Can be a good source of inspiration of solving your design problems.
* [The morning paper](https://blog.acolyer.org/): one CS research paper explained every morning.

### Refactoring

* [The Rule of Three](https://blog.codinghorror.com/rule-of-three/), Coding Horror
	* Every programmer ever born thinks whatever idea just popped out of their head into their editor is the most generalized, most flexible, most one-size-fits all solution that has ever been conceived.
	* It is three times as difficult to build reusable components as single use components.
	* A reusable component should be tried out in three different applications before it will be sufficiently general to accept into a reuse library.

### Releasing & deploying

* [How We Release So Frequently](http://engineering.skybettingandgaming.com/2016/02/02/how-we-release-so-frequently/)
* [How to deploy software](https://zachholman.com/posts/deploying-software), Zach Holman
* [BlueGreenDeployment](http://martinfowler.com/bliki/BlueGreenDeployment.html), Martin Fowler
* [Move fast and break nothing](https://zachholman.com/talk/move-fast-break-nothing/), Zach Holman
* [Flipping out](http://code.flickr.net/2009/12/02/flipping-out/), flickr. One of the first articles about feature flags.
* [Production Readiness Checklist](https://gruntwork.io/devops-checklist/), Gruntwork
* [Checklist: what had to be done before deploying microservices to production](https://habr.com/en/post/438186/)
* [Things end users care about but programmers
  don't](https://instadeq.com/blog/posts/things-end-users-care-about-but-programmers-dont/): includes colors, formatting, themes, integrations, UX, compatibility, operations.
* [Feature Flags, Toggles, Controls](https://featureflags.io/), a website documenting feature flags, from Launch Darkly.
* [Feature Toggles (aka Feature Flags)](https://martinfowler.com/articles/feature-toggles.html), Pete Hodgson, martinFowler.com. Comprehensive article on the topic.
	* Deliver new functionality to users rapidly but safely
	* Release Toggles allow incomplete and un-tested codepaths to be shipped to production as latent code which may never be turned on.
	* Experiment Toggles are used to perform multivariate or A/B testing.
	* Ops Toggles control operational aspects of our system's behavior.
	* Permissioning Toggles change the features or product experience that certain users receive.
	* Static vs dynamic toggles
	* Long-lived toggles vs transient toggles
	* Savvy teams view their Feature Toggles as inventory which comes with a carrying cost, and work to keep that inventory as low as possible.
* [Feature Flags Best Practices: Release Management](https://launchdarkly.com/blog/release-management-flags-best-practices/), LaunchDarkly
* [Developing in Production](https://tersesystems.com/blog/2020/01/22/developing-in-production/)
	* Complex systems have emergent behavior, producing epiphenomenon that only appears with sufficient scale.
	* Wood's theorem: As the complexity of a system increases, the accuracy of any single agent’s own model of that system decreases rapidly.
	* The more tools and code that you add to create elements in a system, the harder it is to replicate an environment encompassing those tools and code.
	* At the core of testing in production is the idea of splitting deployments (of artifacts) from releases (of features).

### Security

* [Penetration Testing Tools Cheat Sheet](https://highon.coffee/blog/penetration-testing-tools-cheat-sheet/#http--https-webserver-enumeration)
* [My First 10 Minutes On a Server - Primer for Securing Ubuntu](http://www.codelitt.com/blog/my-first-10-minutes-on-a-server-primer-for-securing-ubuntu/)
* [A practical guide to securing macOS](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
* [Web Developer Security Checklist](https://www.powerdown.io/blog/posts/stories/web-developer-security-checklist.html)
* [Reckon you've seen some stupid security things?](https://www.troyhunt.com/reckon-youve-seen-some-stupid-security-things-here-hold-my-beer/): everything *not* to do.
* [Checklist of the most important security countermeasures when designing, testing, and releasing your API](https://github.com/shieldfy/API-Security-Checklist)
* [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/): a series of
  cheat sheets about various security topics.
* [Secure by Design](https://henrikwarne.com/2020/03/22/secure-by-design/), a book review by Henrik Warne.
	* There is a big overlap between secure code and good software design
	* Every domain value should instead be represented by a domain primitive.
	* External input needs to be validated before it is used in the system, in the following order: origin, size, lexical content, syntax, semantics.
	* Entities should be consistent at creation, have limited operation, shouldn't be sharing mutable objects.
	* Three Rs to do every few hours: rotate secrets automatically, repave servers and applications (redeploy on clean footprint), repair vulnerable.
	* Don’t use exceptions for the control flow.

### Shell

* [Awesome Shell](https://github.com/alebcay/awesome-shell)
* [Bash Hackers Wiki](http://wiki.bash-hackers.org/)
* [dylanaraps/pure-bash-bible: a collection of pure bash alternatives to external processes.](https://github.com/dylanaraps/pure-bash-bible)
* [Master the command line, in one page](https://github.com/jlevy/the-art-of-command-line) **must read**
* [The Bash Hackers Wiki](https://wiki.bash-hackers.org/) provides a gentler way to learn about bash than its manages.

### System architecture

* [High Scalability](http://highscalability.com/): great blog about system architecture, its weekly review article are packed with numerous insights and interesting technology reviews. Checkout the [all-times favorites](http://highscalability.com/all-time-favorites/).
* [6 Rules of thumb to build blazing fast web server applications](http://loige.co/6-rules-of-thumb-to-build-blazing-fast-web-applications/)
* [Deep Lessons From Google And EBay On Building Ecosystems Of Microservices](http://highscalability.com/blog/2015/12/1/deep-lessons-from-google-and-ebay-on-building-ecosystems-of.html)
* [Service oriented architecture: scaling the Uber engineering codebase as we grow](https://eng.uber.com/soa/)
* [The twelve-factor app](http://12factor.net/)
* [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html)
* [Introduction to Architecting Systems for Scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
* [A Distributed Systems Reading List](http://dancres.github.io/Pages/)
* [Services Engineering Reading List](https://github.com/mmcgrana/services-engineering)
* [System Design Cheatsheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f)
* [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying): one of those classical articles that everyone should read.
* [Learn how to design large scale systems. Prep for the system design interview](https://github.com/donnemartin/system-design-primer) (Github repo)
* [Turning the database outside-out with Apache Samza](https://www.confluent.io/blog/turning-the-database-inside-out-with-apache-samza/)
* 📖 [Building Microservices](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358), Sam Newman (quite complete discussion of microservices)
* [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
* [Monoliths are the future](https://changelog.com/posts/monoliths-are-the-future)
	* "We’re gonna break it up and somehow find the engineering discipline we never had in the first place."
* [Scaling to 100k Users](https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html), Alex Pareto. The basics of getting from 1 to 100k users.
* [Systems that defy detailed understanding - Made of Bugs](https://blog.nelhage.com/post/systems-that-defy-understanding/)
	* Focus effort on systems-level failure, instead of the individual component failure.
	* Invest in sophisticated observability tools, aiming to increase the number of questions we can ask without deploying custom code

#### Scalability

* I already mentioned the book Scalability rules above, but there's also a [presentation](http://www.slideshare.net/cyrilwang/scalability-rules) about it.

#### Stability

* I already mentioned the book Release it! above. There's also a [presentation](http://www.slideshare.net/justindorfman/stability-patterns-presentation) from the author.

#### Resiliency

* 🎤 [The Walking Dead - A Survival Guide to Resilient Applications](https://speakerdeck.com/daschl/the-walking-dead-a-survival-guide-to-resilient-applications)
* 🎤 [Defensive Programming & Resilient systems in Real World (TM)](https://speakerdeck.com/tuenti/defensive-programming-and-resilient-systems-in-real-world-tm)
* 🎤 [Full Stack Fest: Architectural Patterns of Resilient Distributed Systems](https://speakerdeck.com/randommood/full-stack-fest-architectural-patterns-of-resilient-distributed-systems)
* [Resilience Engineering Notes](http://resiliencepapers.club/): comprehensive list of resources on resilience engineering

### Site Reliability Engineering (SRE)

Books:

* [Site Reliability Engineering](https://landing.google.com/sre/books/) 📖
	* Written by members of Google's SRE team, with a comprehensive analysis of the entire software lifecycle - how to build, deploy, monitor, and maintain large scale systems.

Articles:

* [Graduating from Bootcamp and interested in becoming a Site Reliability Engineer?](https://medium.com/@tammybutow/graduating-from-bootcamp-and-interested-in-becoming-a-site-reliability-engineer-b69a38ce858b): a great collection of resources to learn about SRE.
* [Operating a Large, Distributed System in a Reliable Way: Practices I Learned](https://blog.pragmaticengineer.com/operating-a-high-scale-distributed-system/), Gergely Orosz.
	* A good summary of processes to implement.
* [Production Oriented Development](https://paulosman.me/2019/12/30/production-oriented-development.html)
	* Code in production is the only code that matters
	* Engineers are the subject matter experts for the code they write and should be responsible for operating it in production.
	* Buy Almost Always Beats Build
	* Make Deploys Easy
	* Trust the People Closest to the Knives
	* QA Gates Make Quality Worse
	* Boring Technology is Great.
	* Non-Production Environments Have Diminishing Returns
	* Things Will Always Break
* [Meaningful availability](https://blog.acolyer.org/2020/02/26/meaningful-availability/)
	* A good availability metric should be meaningful, proportional, and actionable. By "meaningful" we mean that it should capture what users experience. By "proportional" we mean that a change in the metric should be proportional to the change in user-perceived availability. By "actionable" we mean that the metric should give system owners insight into why availability for a period was low. This paper shows that none of the commonly used metrics satisfy these requirements…
* 🎤 [High Reliability Infrastructure migrations](https://speakerdeck.com/jvns/high-reliability-infrastructure-migrations), Julia Evans.

> Reliability is the one feature every customer users. -- An auth0 SRE.

### Technical debt

* [TechnicalDebt](https://martinfowler.com/bliki/TechnicalDebt.html), Martin Fowler.

### Testing

* [Why bother writing tests at all?](https://dave.cheney.net/2019/05/14/why-bother-writing-tests-at-all), Dave Cheney. A good intro to the topic.
	* Even if you don’t, someone will test your software
	* The majority of testing should be performed by development teams
	* Manual testing should not be the majority of your testing because manual testing is O(n)
	* Tests are the critical component that ensure you can always ship your master branch
	* Tests lock in behaviour
	* Tests give you confidence to change someone else’s code
* [Testing Strategies in a Microservices Architecture](http://martinfowler.com/articles/microservice-testing/) (Martin Fowler) is an awesome resources explaining how to test a service properly.
* [The Practical Test
    Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
    (also on Martin Fowler's blog).
  * Be clear about the different types of tests that you want to write. Agree on the naming in your team and find consensus on the scope of each type of test.
  * Every single test in your test suite is additional baggage and doesn't come for free.
  * Test code is as important as production code.
* [A Quick Puzzle to Test Your Problem Solving](http://www.nytimes.com/interactive/2015/07/03/upshot/a-quick-puzzle-to-test-your-problem-solving.html?_r=0)... and a great way to learn about confirmation bias and why you're mostly writing positive test cases.
* [The test pyramid](http://martinfowler.com/bliki/TestPyramid.html), Martin
  Fowler
* [Just Say No to More End-to-End Tests](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html)
* [End-To-End Testing Considered Harmful](https://dzone.com/articles/end-to-end-testing-considered-harmful)
* [Move fast and don't break things](https://docs.google.com/presentation/d/15gNk21rjer3xo-b1ZqyQVGebOp_aPvHU3YH7YnOMxtE/edit#slide=id.g437663ce1_53_591) (presentation)
* [Eradicating Non-Determinism in Tests](http://www.martinfowler.com/articles/nonDeterminism.html), Martin Fowler
* ["I get paid for code that works, not for tests"](https://istacee.wordpress.com/2013/09/18/kent-beck-i-get-paid-for-code-that-works-not-for-tests/)
* [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html), Kostis Kapelonis.
* [Write tests. Not too many. Mostly integration.](https://blog.kentcdodds.com/write-tests-not-too-many-mostly-integration-5e8c7fff591c) for a contrarian take about unit testing...
* [Testing is Not for Beginners](https://www.calhoun.io/testing-is-not-for-beginners/): why learning to test is hard. This shouldn't demotivate you though!

### Tools

* [DevDocs API Documentation](https://devdocs.io/): a repository for multiple API docs (see also [Dash for macOS](https://kapeli.com/dash)).
* [DevChecklist](https://devchecklists.com/): a collaborative space for sharing checklists that help ensure software quality


### Version control (Git)

* [Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet)
* [git-tips](https://github.com/git-tips/tips)
* [Git from the inside out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)

### Work ethics, productivity & work/life balance

* [Your non-linear problem of 90% utilization](https://blog.asmartbear.com/utilization.html), Jason Cohen: why constantly running at 90% utilization is actually counter-productive.
* [Evidence-based advice on how to be successful in any jobs](https://80000hours.org/career-guide/how-to-be-successful/): most self-help advices are not research-based. The ones listed in this article are.
* [The Complete Guide to Deep Work](https://doist.com/blog/complete-guide-to-deep-work/)
	* The ability to perform deep work is becoming increasingly rare at exactly the same time it is becoming increasingly valuable in our economy.
	* Choose Your Deep Work Strategy
	* Build a Deep Work Routine
	* Discipline #1: Focus on the Wildly Important
	* Discipline #2: Act on the Lead Measures
	* Discipline #4: Create a Cadence of Accountability
	* Our Ability for Deep Work is Finite
	* The Craftsman Approach to Tool Selection
	* Stop Using Social Media
	* Get Your Boss on Board With Deep Work
* [Every productivity thought I've ever had, as concisely as possible](https://guzey.com/productivity/)
	* Context intentionality as the key difference between home and every other place on planet earth
	* Rules are about exceptions
* [Makers, Don't Let Yourself Be Forced Into the 'Manager Schedule'](https://blog.nuclino.com/makers-don-t-let-yourself-be-forced-into-the-manager-schedule)
  * Research shows that it takes as long as 30 minutes for makers to get into the flow
  * Use maker-manager office hours
  * Communication can happen at a quieter asynchronous frequency in the form of thoughtful, written discussions rather than soul-sucking meetings or erratic one-line-at-a-time chat messages
  * Build a team knowledge base to minimize repetitive questions and allow self-onboarding.

### Web development

* [grab/front-end-guide](https://github.com/grab/front-end-guide): a study guide and introduction to the modern front end stack.
* [Maintainable CSS](http://maintainablecss.com/)
* [Front-End Developer Handbook 2019](https://frontendmasters.com/books/front-end-handbook/2019/), Cody Lindley
* [A Directory of design and front-end resources](http://uigoodies.com/index.html)

### Writing

➡️ See also my [engineering-management list](https://github.com/charlax/engineering-management#writing)

* [Undervalued Software Engineering Skills: Writing Well](https://blog.pragmaticengineer.com/on-writing-well/)
	* From the HN discussion: "Writing a couple of pages of design docs or an Amazon-style 6 pager or whatever might take a few days of work, but can save weeks or more of wasted implementation time when you realise your system design was flawed or it doesn't address any real user needs."

![Write like an Amazonian](./images/amazon_writing_rules.jpeg)

### Writing for performance

* [Numbers Everyone Should Know](https://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
* [Latency numbers every programmer should know](https://gist.github.com/hellerbarde/2843375)
* [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)

## Resources & inspiration for presentations

* https://twitter.com/devops_borat
* https://speakerdeck.com/
* Dilbert
* Calvin & Hobbes

## Concepts

[Glossary](glossary.md)

* [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
* [TDD](https://en.wikipedia.org/wiki/Test-driven_development)
* [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development)
* [CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem)
* [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming)
* [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
* [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
* [KISS](https://en.wikipedia.org/wiki/KISS_principle)
* [SOLID](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design))
* [GRASP](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
* [Make it run, make it right, make it fast](http://c2.com/cgi/wiki?MakeItWorkMakeItRightMakeItFast)
