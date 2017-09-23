# layout-lark
Experiments in html/css/js layouts

Not necessarily recommended for production usage...

Goal: Fixed "callout" on left side with fixed header.  Callout offset on centered content.
As window shrinks horizontally, side bar should remain visible. This experiment uses javascript and avoids media queries.
[PositionFixedSidebarOnCenteredContent1.html](https://rawgit.com/davisnw/layout-lark/master/PositionFixedSidebarOnCenteredContent1.html)
Doesn't work correctly in all browsers (especially bad in FireFox 55 - appears to be javascript error)

Goal: Fixed full-height sidebar with fixed full-width header.  Using css flexbox, no javascript, no media queries.
[flex_fixed_header_sidebar.html](https://rawgit.com/davisnw/layout-lark/master/flex_fixed_header_sidebar.html)
