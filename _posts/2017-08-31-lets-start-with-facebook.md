---
inFeed: true
description: >-
  At the end of this post, you’ll see that we have the facebook comments box
  embedded into our grid site.. You can get the code for the plugin here, but
  once you have it you can basically reuse it again and again on your sites..
dateModified: '2017-08-31T12:34:34.850Z'
datePublished: '2017-08-31T12:34:35.539Z'
title: lets start with facebook..
author: []
publisher: {}
via: {}
hasPage: true
starred: false
datePublishedOriginal: '2017-08-31T12:34:35.539Z'
sourcePath: _posts/2017-08-31-lets-start-with-facebook.md
url: lets-start-with-facebook/index.html
_type: Article

---
# lets start with facebook..

At the end of this post, you'll see that we have the facebook comments box embedded into our grid site.. You can get the code for the plugin [here][0], but once you have it you can basically reuse it again and again on your sites..

The code that facebook gave me is :

    <div id="fb-root"></div>
    <script>(function(d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) return;
      js = d.createElement(s); js.id = id;
      js.src = "//connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v2.10";
      fjs.parentNode.insertBefore(js, fjs);
    }(document, 'script', 'facebook-jssdk'));</script>

and..

    <div class="fb-comments" data-href="https://social.abc-xyz.us" data-width="800" data-numposts="5"></div>

They say to add the larger code block once on your page just after the <body\> tag, and the single line of code can be placed anywhere on your website that you want the comments box to appear.

We don't have access to the <body\> tag but each embedded html window that we add to the site reacts as tho it's an own page anyway. So we'll add it everytime we want the comments box.

On the single line of code, facebook wanted to know in pixels how wide the plugin should be. Because we want it to work on the Homepage, maybe on it's own page, and also for visitors that maybe on a mobile phone, we can change that "800" to "100%".

Also note the data-href. It's ok for the first comments box on a page, but if you add a second comments box, you need to change the url. I normally just change it to the posts url. Otherwise we'll end up just replicating the same comments through out the site on every comments box we have. ie they won't be unique. Lastly the size of the comments area is upto you, but we'ed suggest setting the embedded window to about 400\.

So here is the actual code we pasted in the embedded html window, and the result below.

    <div id="fb-root"></div>
    <script>(function(d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) return;
      js = d.createElement(s); js.id = id;
      js.src = "//connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v2.10";
      fjs.parentNode.insertBefore(js, fjs);
    }(document, 'script', 'facebook-jssdk'));</script>
      <div class="fb-comments" data-href="https://social.abc-xyz.us" data-width="100%" data-numposts="5"></div>

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJxNkUFPwzAMhe_7FVERrJXWtEPiQtsdKiHEZSduCKE0cbZ0bVLFadlA_He80UncYvvTe_ZLqczEjKoi3aTeuRBtyoxam0WJ0pshbGI9WhmMs7FaMVwRm7DvBWOT8KylWrfIKqb4DsJTBz3YgPXpVey2oocYk7f8vSDaaBb_Z-rTi4pJKmEewujtmZmFpAcRYOZIoaABN4pmRv1hHL2kMsoy6awFGbgWEhrnDtxCyMB-PNcZqgNv8eaom76r1ncTeKQjqumer_PorEOL80F4Mtk6BdxYBB9q0M5DPB-WFIufWDk5nldZseVfJEt6XQ3TFslomSRFmc2BkXR5DlV2AvGSq3T9JZeIKRFEuvegq2gfwoCPWYZOGtFx0cj0ePri45X6NCrsq2id57dzx4794DCQ5sP1l34BrAiSTg" height="400" style=""></iframe>



[0]: https://developers.facebook.com/docs/plugins/comments