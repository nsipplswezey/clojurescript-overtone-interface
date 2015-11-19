# clojurescript-overtone-interface
Buttons(clojurescript) to control an overtone(clojure+supercollider) server

The app requires clojure and leiningen, the package manager for the clojure community.
If you're new to these tools see:
https://gist.github.com/technomancy/2395913
http://leiningen.org/

To run:
```lein run```

Then point your browser at localhost:8000.

Then to get it up and running on your ipad, connect your ipad to the same network as your computer.
Then find your machines IP address, and point your ipad at your computers localhost server by replacing 'localhost' with your machines IP (ex 1.0.0.1:8000).
This works on most small networks (home, small office), but is trickier on larger or public wifi networks.

This was first demoed in 2012. That's ancient in internet time, but it's still a cool demo.
It uses the microframework 'noir'(depricated) and its associated library 'fetch'(no longer in development, and probably similarly depricated), the clojurescript jquery wrapper 'jayq' and the clojurescript implementation of the templating library hiccup called 'crate'.

Here's the reference blog: http://www.chris-granger.com/2012/02/20/overtone-and-clojurescript/
You can watch Chris Granger silently build it here: https://www.youtube.com/watch?v=lcRQFGtFiyE&feature=youtu.be
