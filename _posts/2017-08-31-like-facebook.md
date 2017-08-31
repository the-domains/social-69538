---
inFeed: true
description: >-
  Similarly.. why not use the facebook like button next to your posts ? Again we
  head back to the developer section to get the next set of code.
dateModified: '2017-08-31T14:15:59.889Z'
datePublished: '2017-08-31T14:16:00.835Z'
title: like facebook ?
author: []
publisher: {}
via: {}
hasPage: true
starred: false
datePublishedOriginal: '2017-08-31T14:16:00.835Z'
sourcePath: _posts/2017-08-31-like-facebook.md
url: like-facebook/index.html
_type: Article

---
# like facebook ?

Similarly.. why not use the facebook like button next to your posts ? Again we head back to the [developer][0] section to get the next set of code.

It looks very similar to the comments set up :

    <div id="fb-root"></div>
    <script>(function(d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) return;
      js = d.createElement(s); js.id = id;
      js.src = "//connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v2.10";
      fjs.parentNode.insertBefore(js, fjs);
    }(document, 'script', 'facebook-jssdk'));</script>

and..

    <div class="fb-like" data-href="https://social.abc-xyz.us" data-layout="button_count" data-action="like" data-size="large" data-show-faces="true" data-share="true"></div>

The same rules apply as we used with the comments box, this time we can make the embedded html window a lot shorter, set it to 30\.

If this was useful... give us the 👍 !

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJxNUcFuwjAMvfMVUSeNVqIp7Li2HCpN0y6cdpsmlCYupJQExS4Dpv37XNZt3Oznp_fs58LYo7CmjJo6Dd5TtCwyhpaTAnWwB1rGTe80We9iMxM4Y24iPidCHFUQLfdNi6IURm6AnjrYgyOszq9qs1J7iDF5m7_nzLaNiG851fnFxCyViADUBzdwRiEdQBGMPFbIeSCt4Zk1PzSJQXMbZZn2zoEm2SgNtfc76YAycOvnKkOzky3enZp635WL-yME5CPK44NczKNBhxeXBxXYZOUNSOsQAlXQ-ADxeFiST75i43U_rDIT059Iplz9GqYtstE0SfIiGwObFEOkulOI11Q7u4NIGEUq3QZoymhLdMDHLEOvreqkqnV6Ol9kjyOrU2ffUxnVPZF3a-17R-NIXT9RRjeaaC_AgAqbP2TrP9JhQfan0P_DfOyIjE_-BjkWqh8" height="30" style=""></iframe>



[0]: https://developers.facebook.com/docs/plugins/like-button