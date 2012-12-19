# Metroappsite-HTML5
MetroAppSite for HTML5 is an off-the-shelf static HTML5 and JavaScript project that leverages [Twitter Bootstrap][6] and [BootMetro][1] to help Windows Store developers craft customizeable, Metro-style websites to help promote their application and meet Windows Store certification requirements.

MetroAppSite is developed and maintained by the engineering team from [MarkedUp Analytics][8].

### What's Included
MetroAppSite includes:

* Metro UI, branding, and Microsoft SurfaceTM smooth screenshot slider.
* Fully configurable branding and content.
* Customizeable and extensible UI built with [Twitter Bootstrap][6] and [BootMetro][1].
* Includes privacy policy template, which is required to publish in the Windows Store.
* Integration points with [UserVoice][4] and [Google Analytics][2] to help you better manage your app's presence online.

### Example MetroAppSites
Here are some sample sites that are currently using MetroAppSite

* [Relay App][9]
* [Default MetroAppSite Configuration][10]

## Configuration Instructions

Fork and clone this repostiory, and then:

1. Edit the marketing text (features, testimonials, headers, etc...) on `index.html`.
1. Add your own carousel pictures to `index.html`. MetroAppSite uses the [Twitter Bootstrap photo carousel][3].
1. Embed your own [Twitter timeline widget] [5] on `index.html`.
1. Add your own [UserVoice] [4] information to `index.html` and `privacy.html`.
1. Add your own [Google Analytics] [2] information to `index.html` and `privacy.html`.
1. Change the `<title>` tag for both `index.html` and `privacy.html`.
1. Change the App Download Urls on both `index.html` and `privacy.html` to be equal to your app's url in the Windows Store.
1. Add your own marketing terms to meta tags at `index.html`.
1. Create your own privacy policy for your app at [PrivacyChoice.org][7] and replace the contents of the privacy policy on `privacy.html`.

This template is based on [BootMetro][1]. 

[1]: http://aozora.github.com/bootmetro/
[2]: http://www.google.com/analytics/
[3]: http://twitter.github.com/bootstrap/javascript.html#carousel
[4]: http://www.uservoice.com/
[5]: https://dev.twitter.com/docs/embedded-timelines
[6]: http://twitter.github.com/bootstrap/
[7]: http://www.privacychoice.org/policymaker/
[8]: https://markedup.com/
[9]: http://relay-3.apphb.com/
[10]: http://metroappsite.apphb.com/