This file contains the different CSS blocks needed for the different Shopify themes. 

**Only copy the code block needed for the theme you are using.**

## Debut
NO CSS CHANGES REQUIRED FOR DEBUT!

## Boundless
```
/* START - GIFT CARD BOUNDLESS THEME */
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer, body.template-gift_card #shopify-section-announcement-bar, body.template-gift_card .site-header-wrapper { display: none; }
body.template-gift_card * .main-content:after { display: none; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; font-size: 17px; line-height: 1.7; font-family: inherit; font-weight: 400; font-style: normal; color: #000; -webkit-font-smoothing: antialiased; box-sizing: border-box; border-radius: 4px; border: 1px solid transparent; padding: 1em; animation: container-slide 0.8s ease-in-out; }
.giftcard { padding-top: 0; font-size: 17px; line-height: 1.7; font-family: inherit; font-weight: 400; font-style: normal; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: #fff; color: #999; border: 1px solid transparent; border-radius: 3px; animation: cardslide 0.8s ease-in-out; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: relative; margin: 25px; background-color: #e95e61; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }
.giftcard__header .site-header__logo { margin-bottom: 25px; }


@media only screen and (min-width: 480px) {
  
    .giftcard-wrapper { padding: 0 30px 30px; }
  
  }
/* END - GIFT CARD BOUNDLESS THEME */
```

## Brooklyn
```
/* START - GIFT CARD BROOKLYN THEME */
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer { display: none; }
body.template-gift_card * .main-content:after, body.template-gift_card * hr { display: none; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; font-size: 17px; line-height: 1.7; font-family: "PT Serif",serif; font-weight: 400; font-style: normal; color: #000; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: $colorPrimary; border-radius: 4px; border: 1px solid transparent; padding: 1em; animation: container-slide 0.8s ease-in-out; }
.giftcard { font-size: 17px; line-height: 1.7; font-family: inherit; font-weight: 400; font-style: normal; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: #fff; color: #999; border: 1px solid transparent; border-radius: 3px; animation: cardslide 0.8s ease-in-out; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: relative; margin: 25px; background-color: #e95e61; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; margin-left: 0; }
.giftcard__header .site-header__logo { margin-bottom: 25px; }


@media only screen and (min-width: 480px) {
  
    .giftcard-wrapper { padding: 30px; }
  
  }
/* END - GIFT CARD BROOKLYN THEME */
```

## Minimal
```
/* START - GIFT CARD MINIMAL THEME */
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer { display: none; }
body.template-gift_card * .main-content:after { display: none; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; font-size: 17px; line-height: 1.7; font-family: "PT Serif",serif; font-weight: 400; font-style: normal; color: #000; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: $colorPrimary; border-radius: 4px; border: 1px solid transparent; padding: 1em; animation: container-slide 0.8s ease-in-out; }
.giftcard { font-size: 17px; line-height: 1.7; font-family: "PT Serif",serif; font-weight: 400; font-style: normal; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: #fff; color: #999; border: 1px solid transparent; border-radius: 3px; animation: cardslide 0.8s ease-in-out; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: relative; margin: 25px; background-color: #e95e61; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }
.giftcard__header .site-header__logo { margin-bottom: 25px; }


@media only screen and (min-width: 480px) {
  
    .giftcard-wrapper { padding: 30px; }
  
  }
/* END - GIFT CARD MINIMAL THEME */
```

## Narrative
```
/* START - GIFT CARD NARRATIVE THEME */
html * .template-gift_card { background-color: #faf9f6 !important; }
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer { display: none; }
.giftcard-wrapper { width: 90%; margin: 0 auto; }
.giftcard__header { padding-top: 55px; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: relative; margin: 27.5px auto; background-color: #e95e61; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }
.critical-hide { display: none !important; }

@media only screen and (max-width: 749px) {
  
  .giftcard__amount { font-size: 8vw; }
  
  }
/* END - GIFT CARD NARRATIVE THEME */
```

## Simple
```
/* START - GIFT CARD SIMPLE THEME */
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer, body.template-gift_card #shopify-section-sidebar, body.template-gift_card .breadcrumb-nav, body.template-gift_card .hr--border-top, body.template-gift_card hr { display: none; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; font-size: 17px; line-height: 1.7; font-family: inherit; font-weight: 400; font-style: normal; color: #000; -webkit-font-smoothing: antialiased; box-sizing: border-box; border-radius: 4px; border: 1px solid transparent; padding: 1em; animation: container-slide 0.8s ease-in-out; }
.giftcard { padding-top: 0; font-size: 17px; line-height: 1.7; font-family: inherit; font-weight: 400; font-style: normal; -webkit-font-smoothing: antialiased; box-sizing: border-box; background-color: #fff; color: #999; border: 1px solid transparent; border-radius: 3px; animation: cardslide 0.8s ease-in-out; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: relative; margin: 25px; background-color: #e95e61; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: Helvetica,"Helvetica Neue",Arial,"Lucida Grande",sans-serif; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }
.giftcard__header .site-header__logo { margin-bottom: 25px; }


@media only screen and (min-width: 750px) {
  
    body.template-gift_card .medium-up--four-fifths { width: 100%; }
  
  }
/* END - GIFT CARD SIMPLE THEME */
```

## Supply
```
/* START - GIFT CARD SUPPLY THEME */
body.template-gift_card { background: #fafafa !important; }
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer { display: none; }
.giftcard__header h1, .giftcard__header h2 { font-family: "Montserrat", sans-serif; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: inherit; font-style: normal; font-weight: 400; color: inherit; line-height: 1.5; box-sizing: border-box; position: relative; margin: 27.5px auto; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: inherit; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }

@media only screen and (max-width: 749px) {
  
  .giftcard__amount { font-size: 8vw; }
  .giftcard-wrapper { width: 90%; }
  
  }
/* END - GIFT CARD SUPPLY THEME */
```

## Venture
```
/* START - GIFT CARD VENTURE THEME */
body.template-gift_card .page-container { background: #000; }
body.template-gift_card #shopify-section-header, body.template-gift_card #shopify-section-footer { display: none; }
.giftcard__header, .giftcard__header h2 { background: #000; color: #fff; }
.giftcard__header h2 { font-size: 1.3em; }
.giftcard-wrapper { max-width: 588px; margin: 0 auto; background: #fff; padding: 15px 20px; }
.giftcard__wrap { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: inherit; font-style: normal; font-weight: 400; color: inherit; line-height: 1.5; box-sizing: border-box; position: relative; margin: 27.5px auto; border-radius: 10px; }
.giftcard__amount { -webkit-font-smoothing: antialiased; box-sizing: border-box; margin: 0 0 17.5px; font-family: inherit; font-style: normal; font-weight: 700; overflow-wrap: break-word; word-wrap: break-word; text-transform: none; letter-spacing: 0; position: absolute; top: 0; right: 0; color: #fff; font-size: 5vw; line-height: 1.2; padding: 10px; z-index: 5; }
.giftcard__wrap img { -webkit-font-smoothing: antialiased; font-size: 15px; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; max-width: 100%; border: 0; position: relative; display: block; border-radius: 10px; z-index: 2; }
.giftcard__code { -webkit-font-smoothing: antialiased; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; box-sizing: border-box; position: absolute; text-align: center; width: 90%; z-index: 5; bottom: 8%; left: 50%; transform: translateX(-50%); font-size: 0.75em; }
.giftcard__code__inner { -webkit-font-smoothing: antialiased; font-family: inherit; font-style: normal; font-weight: 400; color: #3a3a3a; line-height: 1.5; text-align: center; font-size: 1.2em; box-sizing: border-box; width: 100%; display: inline-block; vertical-align: baseline; background-color: #fff; padding: 0.5em; border-radius: 4px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1); }
.giftcard__product-title { font-size: 2.5rem; font-weight: 600; }
.giftcard li { list-style-type: none; }
ul.giftcard-action-list { padding-left: 0; }

@media only screen and (max-width: 749px) {
  
  .giftcard__amount { font-size: 8vw; }
  .giftcard-wrapper { width: 90%; }
  
  }
/* END - GIFT CARD VENTURE THEME */
```

