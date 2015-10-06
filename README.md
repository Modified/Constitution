Constitution: a Software Engineering Manifesto for Web Apps
==============================================================

Constitution is a high level platform for bleeding edge web applications development done right!
It's an opinionated framework and methodology built upon radical technologies: CoffeeScript, Socket.IO, LevelDB, Cake, Double Macchiato, Flexbox… Docker?

Constitution aims to… offer a technological solution to a key challenge startups face, namely, lack of software engineering insight… and technophobia?

In other words, Constitution is a defense system against the MVC/OOP idiocracy plaguing the web technologies ecosystem as of late. It joins a growing (counter-)movement — a resistance, avantgarde, awakening — documenting the horrors of this disaster and advocating solutions.

Web: The State of The Art
--------------------------

1. Web as platform: HTTP &amp; HTML are obsolete!
	1. [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application); cf [Reactive Manifesto](http://www.reactivemanifesto.org/), [Static Apps](http://www.staticapps.org/) manifesto
	1. Socket.IO
	1. Web components: failed tech; DHTML still works
	1. localStorage, Appcache, CDN, remoteStorage (noBackend), mashups…

1. Web vs “native”
	1. Closed proprietary platforms suck!
		1. Risky vendor dependence
		1. Discoverability/SEO lousy
		1. Rollouts excruciating
	1. Hybrid
	1. RWD, CSS3 (SVG…): far better UI capabilities.
	1. New APIs for device features, vs hybrid

1. Architecture: NoSQL and [12 Factor App Manifesto](http://12factor.net/)
	1. ACID vs BASE, CAP theorem, normalization and sharding
	1. Migrations, data modeling for dynamic languages; eg [Metrics 2.0](http://metrics20.org/)
	1. Async (non-blocking concurrency model): promises, streams

1. Continuous delivery, DevOps
	1. Asset pipeline
	1. Environments (continuous deployment)
	1. Quality assurance, continuous integration (CI)
	1. SDLC

1. Domain specific languages and software engineering (goals, processes, principles)
	1. DSLs: CoffeeScript, Stylus, Teacup (Double Macchiato)…
	1. Dreamcode; opinionated; good magic vs bad magic
	1. Scaffolding (skeletons)?

1. Gitflow (SDLC)
1. Ecosystem

…
feature toggling, auth, WYSIWYG/contenteditable.

Roadmap?
-----------

1. Demo apps…
1. Express.IO (or Zappa?)…
