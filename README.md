## Info

Keynote Tweet is a simple AppleScript utility that allows you to send tweets from your Keynote presentations.

It was started by Ideo Labs (?) and hosted [on Google Code](http://code.google.com/p/keynotetweet/).

The Twitter OAuthpocalypse came, broke its posting method, and it wasn't updated.

Splatdot.com updated Keynote Tweet to use a [different posting technique](http://splatdot.com/the-oauthpocalypse-and-keynote-tweet/).

This is that, now modified by Toby Harris (tobyz.net) to be able to handle multiple tweets per slide and hosted on github. So now you can tweet the slide's text and the asides, links etc. to go with it.

Jeff Geerling forked the repository and updated the Keynote Tweet.app file with a signed app that may work better under Mountain Lion (with Gatekeeper). He also wrote detailed directions for [setting up Keynote Tweet](http://www.lifeisaprayer.com/blog/2012/tweet-your-keynote).

## Install

In order for the script to work, you'll need to install and configure twurl. You can find the twurl download and documentation here:

    http://github.com/marcel/twurl

To run the script, simply double-click the Keynote Tweet 2 icon. To edit it, open the same file in AppleScript Editor (formerly Script Editor). Note that you cannot run this or any 'Stay-Open' script from the editor, but must run it as an application instead.