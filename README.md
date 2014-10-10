# helpCSS

This repository is home to a single CSS file I will try to maintain. Eerrrr. Yeah, that's pretty much it for now. This is a work-in-progress so don't throw kilos of issues at me. At some point I'd love to have contributions and issues and pull-requests...

Of course you should add an issue whenever you find something in the CSS file that's plain wrong and by that not helpful at all. I want this to be helpful and not to destroy the UX for people.

## What's in this for me?

Well, basically I want to keep track of useful helpers and stuff I find while looking around the web, which I deem to be useful.

## Again, what?

For example I found it rather interesting when I first ran into an article explaining that I can not only define a placeholder for HTML5 input fields but also (on top of this crazy goodness that made me dance around my desk for a minute) I can style it to my own liking by writing the following CSS:

```
::placeholder {
  color: red;
  text-transform: uppercase;
}
```

## Ah, okay, what else?

I am also very interested in single-browser-bugs or -features and how I can fix/enable them with the power of CSS only. So I'm also trying to add as many as possible of those fixes/features in here as well. Talking about this little gem for example:

```
a:link {
  -webkit-tap-highlight-color: rgba(v, x, y, .z);
}
```

## So you are doing a normalize.css file?

Nope. Yes. Nope. Yes. But nope... this is really not about normalizing browsers but parts of the CSS file are meant to do exactly that, so yeah, parts are for normalization and resetting or to make browsers behave... but others are not. So, yeah but no but yeah but no but look at the CSS file and see for yourselves.

If it is in no way useful for you, that's cool. =)

## License (as if I needed one, heh)

Licensed under the terms of the WTFPL (Do What the Fuck You Want to Public License).

Please see the LICENSE.md included with this distribution for details.