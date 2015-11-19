# clojurescript-overtone-interface
Buttons(clojurescript) to control an overtone(clojure+supercollider) server

The app requires clojure, leiningen and overtone.
If you're new to these tools like I was when I started this project see the following resources to get ideas for how to get started. Clojure and it's related projects are a fun, inspiring and often beautiful ecosystem.

https://gist.github.com/technomancy/2395913

http://leiningen.org/

https://github.com/overtone/overtone/wiki/Getting-Started

To run:
```lein run```

Then point your browser at localhost:8080.
Click start to start the dub, and then play around with the buttons.

Then to get it up and running on your ipad, connect your ipad to the same network as your computer.
Then find your machines IP address, and point your ipad at your computers localhost server by replacing 'localhost' with your machines IP (YOUR-MACHINES-IP-ADDRESS:8080 ex: 10.0.0.1:8080).
This works on most small networks (home, small office), but is trickier on larger or public wifi networks.

This was first demoed in 2012. That's ancient in internet time, but it's still a cool demo. And it works.
It uses the microframework '[noir](https://github.com/noir-clojure/noir)'(depricated) and its associated library '[fetch](https://github.com/LightTable/fetch)'(also depricated), the clojurescript jquery wrapper [jayq](https://github.com/ibdknox/jayq) and the clojurescript implementation of the templating library hiccup called '[crate](https://github.com/ibdknox/crate)'.
And of course the spectular [overtone](http://overtone.github.io/)!

Here's the reference blog I used when building this: http://www.chris-granger.com/2012/02/20/overtone-and-clojurescript/
You can watch Chris Granger silently build it here: https://www.youtube.com/watch?v=lcRQFGtFiyE&feature=youtu.be

If you're interested in seeing more overtone or clojure, you might like this more recent live-coding overtone project where I step-by-step reimplemented Chris Staple's '[Wurlitzer](https://www.youtube.com/watch?v=edhvr72ZJ_s)' using overtone.

https://github.com/nsipplswezey/clojure-overtone-livecoding-wurlitzer
