# CSS3 Cool Banner Micro FWK

Quick transform booooooooring links into colorful banners.

## Currently Tested Browsers

- Safari 5
- Google Chrome 19
- IE 8+ (IE 7 works just fine --if you don't mind not to have rounded corners, shadows and/or gradients at all--)

## Demo and Documentation

- TODO (sorry)

BUT... here we go with a quickstart tip and a quick CSS classes' overview :)

Example:

    <a href="your-link.html" title="Bannerized Link!" class="shadowed orange banner">
        <span class="title">Look, Mom! I'm Bannerized Now!</span>
        <span class="subtitle">Babe...</span>
        <span>I'm really <strong>loving</strong> it! :D</span>
    </a>

Classes:

    Base:
        .banner (base class, required)
            .title (big stuff class, optional)
            .subtitle (medium stuff class, optional)
    Beautifiers:
        .rounded (applies rounded corners, optional)
        .shadowed (applies a nice shadow, optional)
        .plain (avoids gradient background, optional)
    Available colors:
        .grey (optional, default)
        .orange (optional)
        .green (optional)
        .blue (optional)
        .black (optional)
        .red (optional)


## Authors

Originaly developed by Nicolás Fantino ([@ala_747](http://twitter.com/ala_747/))