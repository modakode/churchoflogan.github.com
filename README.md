churchoflogan.github.com
========================

This is the code for the site at [churchoflogan.com](http://churchoflogan.com).  This site captures the threats made by the great bearded mammal beast to people that don't subscribe to [Tek Syndicate](http://teksyndicate.com)'s [YouTube channel](http://www.youtube.com/razethew0rld).  Which is fair dinkum to be honest.

## Contributing

To contribute to the site you can create a Github account if you don't already have one.  Then you can fork this repository, make changes and do a pull request. Or you can request that I add you as a collaborator.

### Editing the site yourself

Editing the site is pretty easy if you're just adding a new threat.  You can follow the format of the html that is already there or copy and paste this template and after putting the threat and video ID in there:

```html
<div class="jumbotron">
  <h1>PUT YOUR BIG WORDS HERE</h1>
  <p class="lead">PUT OTHER WORDS HERE (or delete this line if the threats fit above)</p>
  <div class="video">
    <iframe width="700" height="394" src="http://www.youtube.com/embed/VIDEO_ID_GOES_HERE" frameborder="0" allowfullscreen></iframe>
  </div>
</div>
```

If you follow that and it looks all good I will add your pull request.

### Get someone else to do it

Don't want to edit the site?  You can just make an issue with the threat and the video it is from and someone else (probably me) will add it.

I will also set up an email address soon that threats can be emailed to.