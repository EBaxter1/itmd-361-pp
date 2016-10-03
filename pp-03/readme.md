  ## ITMD 361, Production Problem 3: Relative Units in CSS

For this production problem, you will be doing some math using the formula we talked about in class
on September 21. Specifically,

    target ÷ context = result

Remember that, by default, most browsers set 1em = 16px.

You’ll then use that to compute the values for the CSS styles below.

1. Convert the base font-size listed here from pixels to ems:

      html {
        font-size: 1.19em; /* 19px */
      }

2.  Convert the base font-size listed here to ems, and set the line-height in ems accordingly:

      html {
        font-size: 1.06em; /* 17px */
        line-height: 1.41em; /* 24px based on 17px font */
      }

3. Set the padding for this page to 12px on top and bottom, and 6px on left and right. Express in
ems:

      html {
        font-size: 1.125em; /* 18px */
        padding: .667em .33em; /* 12px top bottom, 6px left right based on 18px */
      }

4. Consider the following CSS. Assuming a browser with its base size at 1em = 16px, how big is h2,
in pixels?

      html {
        font-size: 1.125em;
      }
      figure {
        font-size: 0.888em;
      }
      figure h2 {
        font-size: 23px; /* 1.4375em */
      }
