# hnvuer
A Vue-based Viewer for Hacker News (aka News.YC)

This is an app I'm writing to experiment with [Vue](https://vuejs.org/v2/guide/index.html) and some other mostly front-end technologies.  Eventually, it should be a smooth and mobile-friendly way of browsing Hacker News.  It is still in early development, so don't blame me if your eyes bleed when looking at it (and it's not currently mobile-friendly).

It's a static site with no backend (if you consider client-side JavaScript static).  It uses [VueResource](https://github.com/pagekit/vue-resource) to talk to the Hacker News API, and Vue components to load the list of links asynchronously.  That's currently about it.  The plan is to redirect you to [HN itself](https://news.ycombinator.com/) if you want to comment, submit, or vote (unless they implement those in the API).

[Go here for the app demo](http://hnvuer.herokuapp.com/index.html) or open index.html locally to try it out on your own machine.  
