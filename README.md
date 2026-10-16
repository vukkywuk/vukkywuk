### vukh

I'm studying computer science and I build stuff, mostly Roblox games and things for the web. Lately I've been spending more time on the backend side of things: APIs, databases, getting things deployed and keeping them running.

My website is [vukh.net](https://vukh.net).

#### Some things I've made

**[Kyara.games-bot](https://github.com/vukkywuk/Kyara.games-bot)**
Started as a script to automate my Kyara.games account and turned into a desktop app, a web UI, a browser extension and a CLI. Kyara doesn't have a public API, so I worked out the endpoints from the site's own client. Since the bot can spend in-game currency, a lot of the work went into making sure it never does that by accident. Every purchase gets checked and logged, and if a request might have gone through but never got an answer, the bot leaves it for me to check instead of retrying.

**[website](https://github.com/vukkywuk/website)**
The code behind vukh.net. It runs in Docker on my own VPS and redeploys whenever I push to main. Blog posts are stored in Postgres, and I write them in a small editor I built into the site. It keeps every published version and won't publish a post that's broken.

**ImperiumOS** *(private)*
A Roblox clan combat game I'm working on. The interesting part is the gun system. The server decides everything that matters, like damage, fire rate and where a shot can come from, so exploiters can't just tell it they hit someone. It also has a deploy script that pushes one build to every map at once, and a small API and Discord bot for moderation.

#### What I use

Mostly Luau, C, C++, TypeScript, Node, React/Next.js, Postgres and Docker. I've also used Java, Python and PHP for school and side experiments.