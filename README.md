# multi-colored-column-cta
If you need to highlight multiple pieces of information within a CTA, you can do so by breaking each column up so that it utilizes a different background color.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Multi-Colored Column CTA Section to Help Drive Conversions](http://www.solodev.com/blog/how-to-create-a-multi-colored-column-cta-section-to-help-drive-conversions.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/aqcvhp9o/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="row m-0 text-white align-items-center cta-container">
  <div class="col-lg h-xs-200p bg-blue d-flex align-items-center">
    <div class="w-xl-300p mx-auto ml-lg-auto text-center center-block">
      <img src="https://raw.githubusercontent.com/solodev/multi-colored-column-cta/master/images/facebook_logo.png" class="w-xs-150p" alt="Facebook Logo">
      <p class="mt-3 mb-0">Join our community for special deals and events –
        <a class="text-white" target="_blank" href="https://www.facebook.com/">follow us!</a></p>
    </div>
  </div>
  <div class="col-lg-4 col-xl-3 bg-medium-blue d-flex align-items-center h-xs-200p">
    <div class="w-xl-300p mx-auto text-center center-block">
      <img src="https://raw.githubusercontent.com/solodev/multi-colored-column-cta/master/images/eBay_logo.png" class="w-xs-150p px-3" alt="eBay Logo">
      <p class="mt-2 mb-0">Get incredible deals on our exclusive auction site –
        <a class="text-white" target="_blank" href="https://www.ebay.com/">shop now!</a></p>
    </div>
  </div>
  <div class="col-lg bg-dark-blue d-flex align-items-center h-xs-200p">
    <div class="w-xl-300p mx-auto mr-lg-auto text-center center-block">
      <h3>Need Help?</h3>
      <p class="mt-2 mb-0">Our friendly staff is here to answer your questions –
        <a class="text-white" href="mailto:contact@lunarxp.com">email us!</a></p>
    </div>
  </div>
</div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```
