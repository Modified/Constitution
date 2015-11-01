Constitution: a Software Engineering Manifesto for Web Apps
==============================================================

Constitution is a high level platform for bleeding edge web applications development done right!
It's an opinionated framework and methodology built upon radical technologies: CoffeeScript, Socket.IO, LevelDB, Cake, Double Macchiato, Flexbox… Docker?

Constitution aims to… offer a technological solution to a key challenge startups face, namely, lack of software engineering insight… and technophobia?

Goals: Begin With End in Mind
-----------------------------------

1. Time to market: modifiability, release early and often
1. Performance: UX (MVP becomes MLP), high performance (HP)
1. Reliability: high availability (HA), web scale

Web: Bleeding Edge / State of The Art
---------------------------------------------

Features and their business impact.

1. Web as platform: HTTP & HTML are obsolete!
	1. [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application); cf [Reactive Manifesto](http://www.reactivemanifesto.org/), [Static Apps](http://www.staticapps.org/) manifesto
	1. Socket.IO
	1. Web components: failed tech; DHTML still works

2. Web vs "native"
	1. Closed proprietary platforms suck!
		1. Risky vendor dependence
		1. Discoverability/SEO lousy
		1. Rollouts excruciating/impractical on "native": re-publish, users manually re-install…; whereas web — just cache invalidation.
	1. Hybrid — WebView, RWD, CSS3 (SVG…): far richer than GUI libraries
	1. New APIs for device features — fast pace

3. Architecture: NoSQL and [12 Factor App Manifesto](http://12factor.net/)
	1. ACID vs BASE, CAP theorem, normalization and sharding
	1. Schemaless: no migrations, data modeling for dynamic languages; eg [Metrics 2.0](http://metrics20.org/)
	1. Async (non-blocking concurrency model): promises, streams
	1. localStorage, Appcache, CDN, remoteStorage ([noBackend](http://nobackend.org/) manifesto), mashups…
	1. REST

4. Continuous delivery, DevOps
	1. Asset pipeline: minification, selective combining, responsive images, content negotiation…
	1. Environments (continuous deployment), feature toggling
	1. Quality assurance, continuous integration (CI)
	1. [Gitflow](https://github.com/nvie/gitflow), SDLC

5. Domain specific languages and software engineering (goals, processes, principles)
	1. DSLs: CoffeeScript, Teacup (Double Macchiato), Stylus…
	1. Dreamcode; opinionated; good magic vs bad magic
	1. Scaffolding (skeletons)?
	1. Middleware

1. Ecosystem

…
WYSIWYG/contenteditable.

Evangelism / Politics
------------------------

1. Constitution is a defense system against the MVC/OOP idiocracy (or zombie infestation?) plaguing the web technologies ecosystem as of late. It joins a growing (counter-)movement — a resistance, avantgarde, awakening — documenting the horrors of this disaster and advocating solutions.

…

Roadmap?
-----------

1. Demo apps…
1. Express.IO (or Zappa?)…

Dependencies
----------------

- Node
- CoffeeScript
- Express
- Socket.IO
- LevelDB
- Teacup (until Double Macchiato released)
- Stylus
- Cake
- [Gitflow](https://github.com/nvie/gitflow)
- Docker

…