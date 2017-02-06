Constitution: Make the Web Great Again
==============================================================

Constitution is web applications development done right. It encompasses ideology, methodology, and technology choices.

It's an opinionated, uncompromizing, platform (or stack) and methodology (curated best practices) built upon radical technologies: Progressive Web App features, CoffeeScript, LevelDB, WebSocket, Double Macchiato, Stylus…

Constitution aims to… offer a technological solution to a key challenge startups face, namely, lack of software engineering insight… and technophobia?

(This is still a draft, work-in-progress…)

Web Technologies: Bleeding Edge / State of The Art
-----------------------------------------------------

Features and business impact.

1. *The WWW is the platform*
	1. Progressive Web Apps (PWA): progressive networking (ServiceWorker), "offline first", localStorage…
	1. [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application); cf [Reactive Manifesto](http://www.reactivemanifesto.org/), [Static Apps](http://www.staticapps.org/) manifesto
	1. WebSocket (or HTTP/2?): bidirectional, realtime; WebRTC for P2P
	1. (Web components is failed tech; "DHTML" still works; HTTP & HTML are obsolete — replace with WebSocket and DOM)
	1. WYSIWYG (contenteditable)

	2. Web trumps "native" in every way
		1. Progressive Web Apps: announced to become "native" in Android…
		1. Hybrid — WebView, RWD, CSS3 (SVG, WebGL…): far richer/versatile than GUI libraries
		1. Closed proprietary platforms suck!
			1. Rollouts: excruciating/impractical on "native" — re-publish, re-install… whereas web — just cache invalidation.
			1. Marketing: discoverability/SEO poorer than web; no mashups
			1. Risky vendor dependence
		1. (If you're still missing anything, *hold* your breath: standardized APIs for device features adopted at fast pace.)

3. Architecture: NoSQL and [12 Factor App Manifesto](http://12factor.net/)
	1. ACID vs BASE, CAP theorem, normalization and sharding
	1. Schemaless: no migrations, data modeling for dynamic languages; eg [Metrics 2.0](http://metrics20.org/)
	1. Async (non-blocking concurrency model): promises, streams
	1. localStorage, Appcache, CDN, remoteStorage ([noBackend](http://nobackend.org/) manifesto), mashups…
	1. REST, at scale (GraphQL seems interesting?)

4. Continuous Deployment (CD, DevOps insights)
	1. Asset pipeline: pre/post-processing, minification, selective combining, responsive images, content negotiation…
	1. SDLC, [Gitflow](https://github.com/nvie/gitflow)
	1. Environments (continuous deployment), feature toggling (A/B testing)
	1. Quality assurance, continuous integration

5. Domain specific languages and software engineering (goals, processes, principles)
	1. DSLs: CoffeeScript, Double Macchiato (was Teacup), Stylus… (DSL for Continuous?)
	1. Dreamcode; opinionated; good magic vs bad magic
	1. Scaffolding (skeletons)?
	1. Middleware?

1. Ecosystem
	1. NPM

…

Evangelism / Politics
------------------------

1. Constitution is a defense system against the MVC/OOP idiocracy (aka zombie apocalypse, post-truth age…) plaguing the web technologies ecosystem as of late. It joins a growing (counter-)movement — a resistance, avantgarde, awakening — documenting the horrors of this disaster and advocating solutions.

…

Roadmap
-----------

1. Skeleton(s)
1. Demo apps
1. (Express.IO, Zappa…?)

…

Dependencies
----------------

- Node & NPM
- CoffeeScript
- LevelDB (LevelUP ecosystem)
- Socket.IO (no, replace with other WebSocket lib)
- Double Macchiato (DOM templating (SS); was Teacup)
- Filldom (DOM interpolation (CS); forthcoming)
- Stylus
- [Gitflow](https://github.com/nvie/gitflow)
- Cake, or Bash (towards DSL for Continuous)
- Express, etc

…

[Helpers](https://github.com/Modified/Helpers) are Constitution oriented extensions — bundles of DOM (DM) helper functions, and/or Stylus includes, and/or jQuery plugins, for example.
