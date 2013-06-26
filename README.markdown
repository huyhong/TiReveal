# Ti.Reveal #

Titanium module for [Reveal.app](http://revealapp.com) based on [this blog post](http://k0suke.be/post/52204680895/using-reveal-app-in-titanium-mobile)

## Usage ##
* Add `com.revealapp.ti-iphone-0.2.zip` into your `modules` folder
* Edit your `tiapp.xml` accordingly
* Build your Titanium project
* Load up Reveal.app and select your app in the dropdown

## Notes ##
* Assumes `Reveal.app` is installed in `/Applications`, as it looks for the `Reveal.framework` located inside the `Reveal.app` binary
* Only tested on my local install with Titanium 3.1.1.GA and Alloy 1.1.3, no guarantees it works elsewhere
* All credit goes to [k0sukey](https://github.com/k0sukey), I'm just packaging it per his instructions.