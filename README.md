# Learning Ruby: a resource list

Hi! As a second-career developer who didn't go through a bootcamp, I've found it helpful to keep notes on learning resources—building my own curriculum, in a way. If you have a favorite resource that's missing below, let me know by [opening an issue](https://github.com/fpsvogel/learn-ruby-and-cs/issues/new/choose)!

## Overview

- [Preliminaries](#preliminaries) ✅
- [Frontend basics](#frontend-basics) ✅
- [Ruby](#ruby) ✅
- [Rails basics](#rails-basics) ✅
- [Rails codebases to study](#rails-codebases-to-study)
- [Ruby blogs, podcasts, screencasts](#ruby-blogs-podcasts-screencasts)
- [Miscellaneous essentials](#miscellaneous-essentials)
- [Advanced Rails](#advanced-rails)
- [Performance optimization](#performance-optimization)
- [Hotwire and StimulusReflex](#hotwire-and-stimulusreflex)
- [JavaScript](#javascript)
- [Meanwhile, computer science](#meanwhile-computer-science) *(~30% finished)*
- [Other programming and CS resource lists](#other-programming-and-cs-resource-lists)

## Preliminaries

- If you're wondering why I chose Ruby and not full-stack JS, [I explain why on my blog](https://fpsvogel.com/posts/2021/why-learn-ruby). Or if you want a second opinion, [read this](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) or [watch this](https://youtu.be/IlVfHG-pAag?t=1534).
- I list *a lot* of books and courses below, and hardly any hands-on projects. Let me be clear: you should be spending more time coding than reading about coding. But starting a project and getting into a coding routine is easy (if you can't think of any project ideas, just ["build your own X"](https://build-your-own-x.vercel.app/)), whereas knowing what to read is not at all obvious at the beginning. Hence the focus on books and courses here.
- If you've never written a line of code in your life, you may want to start with the free tutorials at [BigBinary Academy](https://academy.bigbinary.com/learn-ruby) and/or [Learn to Program](https://pine.fm/LearnToProgram/) (or buy [the updated book version](https://pragprog.com/titles/ltp3/learn-to-program-third-edition/)). I studied some computer science in high school, so I had a bit of a head start.
- If you are a working adult looking to transition into software development, make sure your day job is conducive to part-time studying. I used to be a teacher and spent hours grading in the evenings and on weekends, which would have made studying very difficult. So I switched to a remote tech support job, which freed up my schedule.
- Find a system for keeping *organized* notes, code snippets, and articles/videos saved for later. I use [a simple text file](https://fpsvogel.com/posts/2021/plain-text-knowledge-base), which is more effortless than any knowledge base app that I've tried.
- Last but not least, take care of yourself! Studying (especially while working) can easily be overdone. Exercise and get plenty of sleep. If you develop wrist pain from heavy computer use, act swiftly: get an ergonomic keyboard ([the one I use](https://fpsvogel.com/posts/2021/keyboardio-atreus) is effective and affordable), [do daily RSI stretches](https://youtu.be/fdD7CgN5FGg), and start using a break app such as [Workrave](https://workrave.org/).

So without further ado, here is my learning path. Resources that cost money are marked with 💲. If you need more free resources, see the links to other lists at the bottom. You may be able to find the books for free (from your local library, interlibrary loan, or more dubious sources) but be sure to buy them when you can, to support the authors. 🙂

## Frontend basics

- [x] **Learn some HTML, CSS, and JavaScript:** The Odin Project's [Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations) path is great, but there are [a plethora of other tutorials out there](https://www.google.com/search?q=html+css+js+tutorial).
- [x] **Build a blog from scratch:** I've rebuilt it by now, but [here is the first iteration](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). Building a blog is not only a good exercise in itself, but it might also give you extra motivation to write about what you learn. There are other ways to do that too: I also post some of my learnings on Twitter, where—confession—[I sometimes talk to myself](https://twitter.com/fpsvogel/status/1389915714098802692).

## Ruby

- [x] **Basics:** There a few good options here.
  - [The Ruby Programming course on The Odin Project](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby)
  - [Ruby Is For Fun](https://github.com/ro31337/rubyisforfun)
  - 💲[The Well-Grounded Rubyist](https://www.manning.com/books/the-well-grounded-rubyist-third-edition) (worth re-reading later, as it covers some advanced Ruby)
- [x] **Guided practice:** [Exercism](https://exercism.org/tracks/ruby), then [CodeWars](https://www.codewars.com) if you want more. Be sure to take notes each time you learn something new in an exercise, and write up a reflection at the end ([here is mine](https://fpsvogel.com/posts/2020/exercism-ruby)).
- [x] **OOP:** 💲[Practical Object-Oriented Design: An Agile Primer Using Ruby](https://www.poodr.com) (a.k.a. POODR), then 💲[99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby). More than any other Ruby books, these are worth the price tag.
- [x] **Build a Ruby app:** Apply those OOP lessons. I made a CLI (command-line interface) [app that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). Along the way I also [published a Ruby gem](https://fpsvogel.com/posts/2020/ruby-functional-programming), though in the end I abandoned it because I realized it did more harm than good. All part of the learning process…
- [x] **Build a site with Bridgetown:** I [remade my blog](https://fpsvogel.com/posts/2021/build-a-blog-with-bridgetown) with [Bridgetown](https://github.com/bridgetownrb/bridgetown) (an updated Jekyll), and built a Ruby component for [a reading list](https://fpsvogel.com/reading/). Be sure to [join their Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies.
- [x] **Keep up with the community:** You can learn a lot by listening in on what the Ruby community is talking about.
  - [Ruby subreddit](https://www.reddit.com/r/ruby)
  - [Ruby Weekly newsletter](https://rubyweekly.com/)
  - [Ruby Radar newsletter](https://rubyradar.dev/)

## Rails basics

Only courses are listed below, but be sure to *build stuff* as you learn. [Here's how I started building my first Rails app right from the beginning.](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) Another invaluable form of practice is to [start contributing to open source](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails).

- **Community:**
  - [Rails subreddit](https://www.reddit.com/r/rails)
  - [Ruby on Rails Link community on Slack](https://www.rubyonrails.link/)
  - [StimulusReflex on Discord](https://discord.com/invite/stimulus-reflex): you don't need to wait until you start using StimulusReflex to join, because these folks are very helpful to beginners struggling with Rails frontend issues in general.
- **General:**
  - [x] [GoRails - Rails for Beginners](https://gorails.com/series/rails-for-beginners) is great for getting started quickly. If you'd like a slightly longer follow-up, try [Ruby on Rails: A Beginner's Guide](https://www.udemy.com/course/ruby-on-rails-a-beginners-guide-free/).
  - [x] 💲[Ruby on Rails Tutorial](https://www.railstutorial.org) will teach you Rails testing, good Git habits, and how to build an authentication (user login) system from scratch.
  - [x] If you need a review, or if you skipped the Ruby on Rails Tutorial: [Full Stack Ruby on Rails at The Odin Project](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) or (if you prefer videos and/or you're interested in Rails + React) [App Academy Open](https://open.appacademy.io/learn/full-stack-online).
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec
  - [x] [Rails Guides](https://guides.rubyonrails.org/)
- **Testing:** Minitest is familiar at this point. Now it's time to learn RSpec and Rails-specific testing techniques.
  - [x] 💲[The Complete Guide to Rails Testing](https://www.codewithjason.com/complete-guide-to-rails-testing/)
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/)
- **SQL:**
  - [x] Interactive tutorials: [SQL Teaching](https://www.sqlteaching.com), [SQLBolt](https://sqlbolt.com), [SQL Tutorial](https://www.sqltutorial.org/), [Select Star SQL](https://selectstarsql.com), [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial)
  - [x] Extra practice: [Wikibooks](https://en.wikibooks.org/wiki/SQL_Exercises), [w3resource](https://www.w3resource.com/sql-exercises/), [HackerRank](https://www.hackerrank.com/domains/sql)

## Rails codebases to study

These are Rails projects that I've seen mentioned more than once as good examples to learn from. For lots more open-source Rails projects, see [Real World Rails](https://github.com/eliotsykes/real-world-rails) (and [how to search through it](https://www.hexdevs.com/posts/massive-list-of-open-source-ruby-on-rails-applications-you-can-use-as-a-reference/)) and [Awesome Ruby and Rails Open Source Apps](https://github.com/asyraffff/Open-Source-Ruby-and-Rails-Apps).

  - [ ] [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase)
  - [ ] [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall)
  - [ ] [github.com/houndci/hound](https://github.com/houndci/hound)
  - [ ] [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage)
  - [ ] [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon)
  - [ ] [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org)
  - [ ] [github.com/forem/forem](https://github.com/forem/forem)
  - [ ] [github.com/solidusio/solidus](https://github.com/solidusio/solidus)

## Ruby blogs, podcasts, screencasts

Checking one of these off means "I've read/watched/listened to all the posts/episodes that interest me from the past few years, and I'm keeping an eye out for new posts/episodes that would help me, or old posts/episodes when they become relevant to me."

- **Blogs:**
  - [x] [Fullstack Ruby](https://www.fullstackruby.dev/articles)
  - [x] [Code with Jason](https://www.codewithjason.com/articles/)
  - [ ] [Thoughtbot](https://thoughtbot.com/blog)
- **Screencasts:**
  - [ ] [Naming Things](https://www.namingthings.org/)
  - [ ] [DHH - On Writing Software Well](https://youtube.com/playlist?list=PL9wALaIpe0Py6E_oHCgTrD6FvFETwJLlx)
  - [ ] [Rails Code Along](https://www.railscodealong.com/)
  - [ ] [SupeRails](https://www.youtube.com/c/SupeRails/playlists)
  - [ ] Web-Crunch collections ([1](https://web-crunch.com/collections/ruby-on-rails), [2](https://web-crunch.com/collections/lets-build-with-ruby-on-rails), [3](https://web-crunch.com/collections/lets-build-for-ruby-and-rails-developers))
  - [ ] [Phil Smy - Ruby on Rails](https://youtube.com/playlist?list=PLiJC12qFqVo3DrqGZn80DvdT8qGsQT9wh)
  - [ ] [CJ Avilla](https://www.youtube.com/c/CJAvilla/playlists)
  - [x] 💲[GoRails](https://gorails.com)
  - [x] 💲[Drifting Ruby](https://www.driftingruby.com)
  - [ ] 💲[Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog)
- **Podcasts:**
  - [x] [Ruby for All](https://www.rubyforall.com/)
  - [x] [Fullstack Ruby](https://www.fullstackruby.dev/topics/podcast)
  - [ ] [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [x] [Ruby Rogues](https://topenddevs.com/podcasts/ruby-rogues)
  - [ ] [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/), especially starting at [episode 372](https://www.therubyonrailspodcast.com/372) went they went independent, brought on co-hosts, and hired an editor.
  - [ ] [Code with Jason](https://www.codewithjason.com/podcast)
  - [ ] [Maintainable](https://www.maintainable.fm/) (not Ruby-specific)
  - [ ] [DevDiscuss](https://devpods.dev/podcasts/devdiscuss) (not Ruby-specific)
  - [ ] [The Bike Shed](https://www.bikeshed.fm/)
  - [ ] [Running in Production – Rails](https://runninginproduction.com/tags/rails)

## Miscellaneous essentials

- **Mentorship**
  - [ ] [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor.
  - [ ] The [Rails subreddit](https://www.reddit.com/r/rails) is also a good place to find a mentor.
- **Open source:**
  - [x] Contribute to open source projects. I've written [a short guide on how to get started](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails).
  - [ ] 💲[How to Open Source](https://howtoopensource.dev/)
- **Git:**
  - [ ] [Oh My Git!](https://ohmygit.org/)
  - [ ] [Oh Shit, Git!?!](https://ohshitgit.com/)
  - [ ] [Introduction to Git and GitHub](https://github.com/bobbyiliev/introduction-to-git-and-github-ebook/) (and [here's another good one by the same name](https://launchschool.com/books/git))
  - [ ] [Goal-oriented Git](https://github.com/thoughtbot/goal-oriented-git)
  - [ ] [Mastering Git](https://thoughtbot.com/upcase/mastering-git)
  - [ ] [Pro Git](https://git-scm.com/book/en/v2)
  - Lots more resources [are listed here](https://dev.to/anaveecodes/how-to-get-better-with-git-25d1)
- **Linux:**
  - [ ] [Mastering the Shell](https://thoughtbot.com/upcase/mastering-the-shell)
  - [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- **HTTP:**
  - [ ] [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP). See also "Networks" under [the computer science section](#meanwhile-computer-science).
- **Security:**
  - [ ] 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V)
- **Design patterns:** They didn't revolutionize my coding, but they're worth knowing for those times when people refer to them in design discussions.
  - [x] 💲[Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/)
  - [x] [Refactoring.Guru](https://refactoring.guru/)
- **Learn other app frameworks:** Jobs in Ruby are mostly in Rails, but it's still valuable to broaden my horizons and learn different approaches.
  - [ ] [Roda](https://roda.jeremyevans.net/) which will soon be easier than ever to get started with [via Bridgetown](https://www.bridgetownrb.com/docs/routes)
  - [ ] [Hanami](https://hanamirb.org/)
  - [ ] [Lucky](https://luckyframework.org/), a web framework for [Crystal](https://crystal-lang.org/)… which is not Ruby but it's close 😉
- **The arcane arts of getting hired:**
  - [x] [How to find your first Rails job](https://fpsvogel.com/posts/2022/how-to-find-ruby-rails-job), notes from my own job search.
  - [x] 💲[Get Your First Developer Job](https://learnetto.com/users/hrishio/courses/get-your-first-developer-job)
  - [x] Attend some [Ruby meetups](https://www.meetup.com/find/?keywords=ruby), where you might find job leads.
  - [ ] 💲[The Tech Resume Inside Out](https://thetechresume.com/)
  - I didn't read any of the popular books on interview prep because I wanted to avoid that type of algorithm/whiteboarding interview, which in any case is not very common in the Ruby world. But if you want to be ready for that: 💲[Cracking the Coding Interview](https://www.crackingthecodinginterview.com/) and/or 💲[Elements of Programming Interviews](https://elementsofprogramminginterviews.com/)

## Advanced Rails

- **Authentication:**
  - [ ] [Rails Authentication from Scratch](https://github.com/stevepolitodesign/rails-authentication-from-scratch) and the derived [Rails MVP Authentication](https://github.com/stevepolitodesign/rails_mvp_authentication)
  - [ ] Study the similar [Authentication Zero](https://github.com/lazaronixon/authentication-zero))
- **Advanced Ruby:**
  - [ ] 💲[Metaprogramming Ruby](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2/)
  - [ ] 💲[Ruby Under a Microscope](https://patshaughnessy.net/ruby-under-a-microscope)
- **Rails internals:**
  - [ ] [Demystifying Rails](https://launchschool.com/books/demystifying_rails)
  - [ ] 💲[Dissecting Ruby on Rails](https://www.udemy.com/course/professional-rails-5-development-course/)
  - [ ] 💲[Rebuilding Rails](http://rebuilding-rails.com/)
- **Rails deployment/DevOps:**
  - [ ] 💲[Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Deploying Rails Applications](https://leanpub.com/deploying_rails_applications)
  - [ ] 💲[Efficient Rails DevOps](https://efficientrailsdevops.com/)
  - [ ] Guides to deploying Rails on AWS: [1](https://www.theelastic.guru/lee/how-to-build-a-ruby-on-rails-host-on-aws-for-beginners-232l), [2](https://www.honeybadger.io/blog/rails-6-aws-elastic-beanstalk/), [3](https://www.codewithjason.com/how-to-deploy-a-ruby-on-rails-application-to-aws/)

## Performance optimization

- **Advanced SQL**
  - [ ] [Use the Index, Luke!](https://use-the-index-luke.com/sql/preface)
  - [ ] [Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql) course from Stanford
- **Rails and Active Record:**
  - [x] [Advanced ActiveRecord Querying](https://thoughtbot.com/upcase/advanced-activerecord-querying)
  - [ ] 💲[Next Level Active Record](https://courses.jasoncharnes.com/next-level-active-record)
  - [ ] 💲[The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] 💲[Maintainable Rails](https://leanpub.com/maintain-rails)
- **PostgreSQL**
  - [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
  - [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at Thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
  - [ ] [The Art of PostgreSQL](https://theartofpostgresql.com/)
  - [ ] [PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)

## Hotwire and StimulusReflex

If you ever get stuck, the [StimulusReflex community on Discord](https://discord.com/invite/stimulus-reflex) is an amazing resource, even for Hotwire.

- **Hotwire:**
  - [ ] [Read the docs](https://hotwired.dev/)
  - [ ] Sign up for newsletters: [Hotwire dev newsletter](https://masilotti.com/hotwire/) and [Hotwiring Rails](https://www.getrevue.co/profile/hotwiringrails)
  - [ ] Evil Martians [talk](https://www.youtube.com/watch?v=sIxvxp7E0xg) and [blog post](https://evilmartians.com/chronicles/hotwire-reactive-rails-with-no-javascript)
  - [ ] [Turbo Rails Tutorial](https://www.hotrails.dev/)
  - [ ] [Mix & Go screencasts on Hotwire](https://www.youtube.com/playlist?list=PLBhH0uX92r6oiwiLBjdE-3NNsyRqyLAV9)
  - [ ] [SupeRails screencasts on Hotwire](https://www.youtube.com/playlist?list=PLdTytUiloS16epXsqHswpCUMND_rksjr4)
  - [ ] [SupeRails blog](https://blog.corsego.com) which includes even more Hotwire tips.
  - [ ] [David Colby's blog](https://www.colby.so), starting with the post [Turbo Rails 101](https://www.colby.so/posts/turbo-rails-101-todo-list)
  - [ ] [Hotwire Handbook, Part 1](https://philreynolds.dev/posts/2022/hotwire-handbook-part-1)
  - [ ] [Hotwire examples](https://github.com/thoughtbot/hotwire-example-template/branches/active) from Thoughtbot
  - [ ] [Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire)
  - [ ] 💲[Hotwired ATS: Modern, full-stack Rails development](https://davidcolby.gumroad.com/l/hotwired-ats/68y8c5c)
- **StimulusReflex:**
  - [ ] [Read the docs](https://docs.stimulusreflex.com/)
  - [ ] [Videos by the StimulusReflex creator](https://www.youtube.com/channel/UCP7FO_cPZKI2v1XqrAVosqw)
  - [ ] [StimulusReflex lifecycle chart](https://lucid.app/lucidchart/e83d2cac-d2b1-4a05-8a2f-d55ea5e40bc9/view?page=0_0#)
  - [ ] [Hotwire with StimulusReflex](https://www.youtube.com/watch?v=fdqOHazPdmA) presentation, in case you're wondering how the two can fit together.
  - [ ] [Mix & Go screencasts on StimulusReflex](https://www.youtube.com/playlist?list=PLBhH0uX92r6rjVGaXipwGzzJ_d1Z-J7LX)
  - [ ] 💲[Interactive Rails with StimulusReflex](https://courses.jasoncharnes.com/stimulus-reflex)
  - [ ] 💲[StimulusReflex Patterns](https://www.stimulusreflexpatterns.com/)

## JavaScript

Because try as you might, you can't avoid it. Note: there are *so* many JS books out there and I haven't surveyed the landscape yet. These are just books that have been personally recommended to me.

- [ ] [The Modern JavaScript Tutorial](https://javascript.info/)
- [ ] 💲[You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)

## Meanwhile, computer science

- **How computers work:**
  - [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.informit.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100)
  - [ ] [NandGame](https://nandgame.com)
  - [x] *From Nand to Tetris* course ([Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2)) along with the textbook 💲[The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition)
  - [ ] 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
- **Algorithms:**
  - [x] 💲[Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539)
  - [ ] for reinforcement: *Algorithms* course by Sedgewick & Wayne ([Part 1](https://www.coursera.org/learn/algorithms-part1), [Part 2](https://www.coursera.org/learn/algorithms-part2)) along with the textbook 💲[Algorithms](https://algs4.cs.princeton.edu/home/)
  - [ ] going deeper: 💲[The Algorithm Design Manual (Skiena)](https://www.algorist.com/)
  - [ ] and deeper again: 💲[Algorithm Design (Kleinberg & Tardos)](https://www.cs.princeton.edu/~wayne/kleinberg-tardos/)
  - [ ] for practice: [Project Euler](https://projecteuler.net/)
- **Usability and UI:**
  - [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/)
  - [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)
  - [x] [Victor Ponamariov - 50 UI Tips](https://fifty.user-interface.io/50_ui_tips.pdf)
  - [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips) (or on [the landing page](https://hundred.user-interface.io/))
  - [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)
- **Operating systems:**
  - [x] 💲[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- **Networks:**
  - [ ] [Computer Networks from Scratch](https://www.networksfromscratch.com)
  - [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)
  - [ ] for a fun review: [How DNS Works](https://howdns.works/ep1/)
  - [ ] [books by Jesse Storimer](https://workingwithruby.com/) on network and system programming—with Ruby!
- **Software architecture:** [ ] 💲[Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- **Program design:** different from software architecture in ways that I don't yet fully understand.
  - [ ] [How to Design Programs](https://htdp.org/2022-6-7/Book/index.html) and courses based on it ([here's one](https://www.youtube.com/channel/UC7dEjIUwSxSNcW4PqNRQW8w/playlists) + [extra content](https://edge.edx.org/courses/course-v1:UBC+CPSC110+2021W2/77860a93562d40bda45e452ea064998b/), and [here's another](https://legacy.cs.indiana.edu/classes/c211/index.html))
  - [ ] [Design of Computer Programs](https://www.udacity.com/course/design-of-computer-programs--cs212)
  - [ ] [Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/html/index.xhtml) (and [video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)). So far I've had trouble figuring out exactly what this book is about. It is an often-recommended introductory text on "programming", funnily enough.
- **Databases:**
  - [ ] [Readings in Database Systems](http://www.redbook.io/)
- **Compilers:**
  - [ ] [Crafting Interpreters](https://craftinginterpreters.com/)
- **Math:**
  - [ ] [Concrete Mathematics: A Foundation for Computer Science](https://www-cs-faculty.stanford.edu/~knuth/gkp.html). The math review that I'm doing leading up to this is proving to be a journey in itself, which I will outline separately in the future.

## Other programming and CS resource lists

- [Backend (Ruby) track at Turing School](https://backend.turing.edu/module1/)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [p1xt Computer Science and Programming](https://github.com/P1xt/p1xt-guides)
- [Open Source Society University](https://github.com/ossu/computer-science)
