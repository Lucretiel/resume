# Nathan Granbery West

## Summary

Fast-learning, NYC-based developer with extensive experience in Rust, C++, Python, and Javascript.

## Skills

- Programming Languages: Highly experienced in Rust, Javascript (including Typescript and ES2015+), C++ (including C++11, C++14, C++17), and Python (3 and 2). Also experienced in Ruby, Golang, C#, Erlang, bash, Tcl, and many other languages
- Frameworks: Experienced with many web frameworks, both front- and backend, including React & Redux, Angular, Django, Flask, and Bottle. Also experienced with game frameworks, including SFML and Unity3D.
- Platforms: Highly experienced in Linux development, including shell tools and techniques. Also experienced developing for Windows and OSX, and web platforms like Heroku.
- Methodologies: Test driven development, Continuous integration, git flow.
- Domains: Everything from low-level C++, to graphical applications & webapps, games, APIs, and general libraries and packages. Strongest in libraries and small, focused developer utilities and tools.

## Experience

### 1Password, Toronto, Ontario

Senior Developer (Rust specialist), Core Apps<br/>
September 2020–Present

- Worked predominantly on the "core", 1Password's common rust codebase underpinning all versions of the app (Windows, Mac, Linux, iOS, Android, and some of the web extension via WASM)
- Implemented and maintained a localization framework that verifies correctness for localizations at compile time. Used by all versions of 1Password 8.
- Designed and implemented the in-app purchase flow for 1Password on iOS. Worked closely with Swift developers for assistance on the SwiftUI portions of this work.
- Designed, and implemented much of, the app telemetry framework used by 1Password, including the patterns and helpers for compile-time-checked event types and the integration with Snowplow. Worked directly with Snowplow to open up their events API to third-party developers.
- Architected and implemented the rust side of the sign-in flow for 1Password, including integrations with platform credential sync like iCloud. Worked closely with platform developers (iOS, Android).
- Led the "localize everything" initiative, an organized effort to ensure that all user-facing text in the app is correctly localized.
- Continuously made a variety of small to medium changes to our Rust code with a specific eye towards more compile-time safety.
- Made a [series](https://www.youtube.com/playlist?list=PL3BITueGyOqzdMMQlJexd5Eqdx1ZhsVlo) of educational presentations on various Rust topics (macros, atomics, shared mutability, etc), most of which were later published to the official 1Password YouTube channel

### Open Source Contributor

July 2019–September 2020

- Contributed to numerous open-source projects, mostly in the Rust ecosystem, including to the Rust project itself. In particular, took ownership of Rust's 5-year-old stdout unconditional line-buffering issue. Created a massive refactor of standard library buffering as a first step to solving it.
- Joined <https://colonist.io>, a free web-based reimplementation of Settlers of Catan, as an official contributor.
- Ported Bobbin, a lightweight Twitter thread sharing app, to Rust from Python.
- Created batchloader, a type-safe Rust implementation of Facebook's dataloader pattern.
- Created or updated several smaller Rust crates, especially related to asynchronous and low-level utility needs, all with a focus on type-safety and 0-cost abstraction.

### Google LLC, Mountain View, CA

Developer Advocate for Google Analytics<br />
November 2017–June 2019

- Worked with engineering team to promote developer-friendly API design & create useful reference documentation. Helped launch Analytics Provisioning API, Individual User Reporting API, Client ID dimension reporting, and the next generation Web + App Analytics.
- Took ownership of the Analytics Developer Tools (<https://ga-dev-tools.appspot.com/>), which hosts many millions of unique visitors per month. This included feature development, open source engagement, bug ﬁxing, and internal process documenting.
- Owned partner relations during the launch of the Analytics Provisioning API. This included finding, onboarding, and supporting large Ads Partners interested in this API for the purpose of scaling their own Analytics Account management.
- Worked directly with Bitly engineers to migrate the URL shortener in our Developer Tools from goo.gl to bit.ly during the goo.gl deprecation. Identified missing functionality in their API, and helped them fill those gaps to better meet our own needs and Bitly's preferred customer engagement experience when using our tool.
- Migrated the Dimensions & Metrics Explorer- our most popular developer web tool- to the Dev Tools site. This included a full rewrite away from jquery to React.

### Dropbox Inc., New York, NY

Software Engineer<br />
January 2016–February 2017

- Deployment & Infrastructure Engineer for Dropbox services.
- Worked on our Dropbox’s internal package management, code deploy, and cluster management tools.
- Helped with total rewrite of our package deployment web frontend using React.
- Originated several small but widely-used improvements to our deployment frontend, including api access to log ﬁles and a global banner/notiﬁcation system.
- Worked primarily with Go & Python 2. Also worked with various web frameworks (including jquery, handlebars, and React) for our internal tool frontends.

### Fidessa plc, New York, NY

Developer<br />
June 2014–January 2016

- C++ Developer for Fidessa’s US Core Trading Platform.
- Developed numerous enhancements and features for the Core Trading Platform, an immense base of nearly 2 million lines of code.
- Interpreted and implemented new post-recession ﬁnancial regulations into the trading platform.
- As part of a company-wide transition to BMC Remedy for support issue tracking, created a company-wide desktop notiﬁcation tool used by development managers to receive incoming support escalations.
- Became trusted resource on the team for technical expertise outside of Fidessa speciﬁc technologies, such as recent C++11 techniques, shell scripting, and shell tools like tmux.

### Mimedia Inc., Brooklyn, NY

Software Engineer, Research and Development<br />
May 2012–August 2013

- Reported directly to the Mimedia CTO.
- Researched potential new technologies to bring to Mimedia, with special focus on developer productivity tools.
- Found and implemented Jenkins CI; oversaw transition of company software development to CI, and transition of Mimedia source code to git from SVN. Trained other developers in the use of git, including commands, GitHub, and development patterns like git-ﬂow.
- Worked closely with systems administrators to develop numerous small administrative scripts for development infrastructure, especially in Bash, Python, Ruby, and Puppet

### RPI Help Desk, Troy, NY

Help Desk Consultant<br />
September 2010–May 2014 (excepting Mimedia, above)

- Front line point-of-contact support for RPI student body computing needs.
- Commonly facilitated laptop re-images, licenses for RPI software installs, and on-campus printing.
- Troubleshooted problems a wide variety of technology platforms, including Windows, Max OSX, Linux, iOS, and Android.
- Gained experience working with clients of all levels of technical expertise to and solutions to problems.

## Education

RENSSELAER POLYTECHNIC INSTITUTE, Troy, NY<br />
B.S. Computer Science, May 2014

## Portfolio

- <https://github.com/Lucretiel>
- <https://crates.io/users/Lucretiel>

<sub>Ask me why generators are the most important control ﬂow abstraction since the automatic call stack</sub>
