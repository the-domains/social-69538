---
inFeed: true
description: >-
  There are literally hundreds of ways that you can add your latest instagram
  photos to your grid site, but one of the easiest - and nicest - is from a site
  called Intush.
dateModified: '2017-09-01T13:29:53.214Z'
datePublished: '2017-09-01T13:29:53.806Z'
title: instagram..
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2017-09-01-instagram.md
starred: false
datePublishedOriginal: '2017-09-01T13:28:11.910Z'
url: instagram/index.html
_type: Article

---
# instagram..

There are literally hundreds of ways that you can add your latest instagram photos to your grid site, but one of the easiest - and nicest - is from a site called [Intush][0].

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJw9UD1vwjAQ_SuRh2whoaWUJJgu0AqBqiLK0gU59iW51rGD7QDpr68JUm846d5J72uOpWENBNZwSuK4s2DsCJV1na1HXDdxHVmJAkz8wrW0dBIa3SlBnekg5Gi4BFoyaSFsUd3RG8cRBX1Mk2Tq12xAlFehyASMeGj9NxqH9h_3h2PVgLm-BdqggtDRdJhiyd_5l_gUk1O93l1eT6mI0uVxtVv2m-7BtOPz7xqj8i05tk9W7vbP34fD3sGH3F73VVSvDsU2LSHZJM2KBExKfXGGKdsyA4r3lNxMk2CoodDGR6UkIYHlRkuJqqJEaRIE3piPSgTaVrI-K6TmP_kFhauz6Sxpr3kNWNUuG6e3406UKa0g12cwpVfNzmixkJCTYDGP770v_gA2z4WW" height="244" style=""></iframe>

They have many different layouts, but the one above is just nice and simple.

The code from Intush to embed was :

    <iframe src="//users.instush.com/h-slider/?cols=4&round=true&circle=false&pin=true&user_id=390063908&username=iade.c&sid=-1&susername=-1&tag=-1&stype=mine&t=999999bDcNcZdTd4qhIQwFq9d-9D_EQDyKu2rp1vzIi-fG0_p5slQS7jUUStePlLxSg-hEUbL9fe0K0mE" allowtransparency="true" frameborder="0" scrolling="no"  style="display:block;width:680px;height:190px;border:none;overflow:visible;" ></iframe>

They set the width at 680px and height at 190px.. We're going to remove that part, and just make the width:100% ..that way it will work on the Homepage, it's own page, and a mobile phone if your visitor happens to be using one.. new code :

    <iframe src="//users.instush.com/h-slider/?cols=4&round=true&circle=false&pin=true&user_id=390063908&username=iade.c&sid=-1&susername=-1&tag=-1&stype=mine&t=999999bDcNcZdTd4qhIQwFq9d-9D_EQDyKu2rp1vzIi-fG0_p5slQS7jUUStePlLxSg-hEUbL9fe0K0mE" allowtransparency="true" frameborder="0" scrolling="no"  style="display:block;width:100%;border:none;overflow:visible;" ></iframe>

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJw9UMtuwjAQ_BXLUnMLMS19JMH0Aq0QqCqiXHpBjr1J3Dp2sB1o-vU1idQ9rHZnpZmdmcvSsgaQs5ziJOkcWDeR2vnO1RNumqSOnZICbPLMjXJ0FlnTaUG97SDi0nIFtGTKQdRKPaJXjqMU9C4l5CG0pwHRQYVKJmDCIxeu8TRy_3hYPKsGzPct0EZqiDxNhyqW_I1_ig8xO9Xr3eXllIo4XR5Xu2W_6W5tOz3_rmVcvpJje-_Ubv_4dTjsPbyr7c--iuvVodimJZANaVYYMaXMxVumXcssaN5TfH0aoyGGwthglWKCkePWKCV1RbE2GKHwWLCKhXStYn1WKMO_84sUvs6mhNzkNciq9uM80mTaaMjNGWwZNLOzdLJQkGO0mCdj6os_AHOD-g" height="244" style=""></iframe>



[0]: http://www.intush.com/