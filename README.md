> Link to my PHP cheatsheet : https://1idweb.com/doc/cheatsheet/php.php

----

# Lorem ipsum variables
Strings of _lorem ipsum_ text with *character count (bytes)*

## PHP file

    <?php
    /*
    * External links
    */
    $href_in = '#internal_link_example';
    $href_external = 'http://example.com/';
    $href_to_pdf_example = 'http://samplepdf.com/sample.pdf';

    /*
    * Lorem ipsum strings for placeholders
    */
    $lorem010 = '010 bytes';
    $lorem015 = '015 bytes lôrem';
    $lorem020 = '020 bytes lôrem ïpsu';
    $lorem022 = '022 bytes lôrem à deux';
    $lorem023 = '023 bytes lôrem triotxt';
    $lorem024 = '024 bytes lôrem et katre';
    $lorem025 = '025 bytes lôrem vingtcinq';
    $lorem026 = '026 bytes lôrem twenty six';
    $lorem027 = '027 bytes lôrem twenty sept';
    $lorem028 = '028 bytes lôrem wenty height';
    $lorem029 = '029 bytes lôrem vingt et neuf';
    $lorem030 = '030 bytes lôrem ïpsum dolor ça';
    $lorem034 = '034 bytes lôrem ïpsum du caractère';
    $lorem035 = '035 bytes lôrem no Lady Gaga is out';
    $lorem036 = '036 bytes lôrem ïpsum des caractères';
    $lorem038 = '038 bytes lôrem Madonna is old as mamy';
    $lorem040 = '040 bytes lôrem ïpsum dolor çaga posuère';
    $lorem044 = '044 bytes lôrem ïpsum dolor çaga pour quatre';
    $lorem050 = '050 bytes lôrem ïpsum dolor encore cinquante bytes';
    $lorem060 = '060 bytes lôrem ïpsum dolor sit àmety consectetur ça au âmet';
    $lorem064 = '064 bytes lôrem ïpsum dolor sit àmety consectetur adipis sixfour';
    $lorem066 = '066 bytes lôrem ïpsum dolor sit àmety consectetur adipis sixty-six';
    $lorem068 = '068 bytes bytes lôrem ïpsum dolor sit àmety consectetur adipis sixtyheight';
    $lorem070 = '070 bytes lôrem ïpsum dolor sit àmety consectetur adipicing dè seventy';
    $lorem075 = '075 bytes lôrem ïpsum dolor sit àmet au consectetur adipiscing elit atesque';
    $lorem080 = '080 bytes lôrem ïpsum dolor sit àmet au consectetur adipiscing elit pellentesque';
    $lorem085 = '085 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elity pellentesque raçàé';
    $lorem090 = '090 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elity pellentesque çras àmets';
    $lorem100 = '100 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elit étiam suscipit velit vel venenatis';

    $lorem120 = '120 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elit. Étiam suscipit velit velà venenatis accumsan volutpat';

    $lorem200 = '200 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Nam nec pretium nulla. Étiam sollicitudin, turpis ac rhoncus fermentum, ante justo iaculis ïpsum, ac elementum Ôdio arcu nec posueres';

    $lorem300 = '300 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Donec vel sagittis mi. Pellentesque mollis mauris in Ôdio congue dictum. Aenean ultricies ligula at dui condimentum aliquet. Donec adipiscing, magna eu vulputate mattis, risus erat fringilla leo, non malesuada elit libero ac posuere.';

    $lorem500 = '500 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Sed ut ornare enim, ac tempor velit. Pellentesque id Ôdio scelerisque, feugiat lectus non, tristique leo. Aenean tincidunt vel risus at imperdiet. Donec rutrum malesuada urna at lacinia. Praesent pharetra porttitor elit vitae varius. çras commodo magna quis erat ultrices, et ultrices erat cursus. Maecenas eget orci lôrem. Suspendisse at arcu ac nisl blandit pretium quis et elit. Quisque ultrices dolor rhoncus, feugiat nulla àmet.';

    $lorem900 = '900 bytes lôrem ïpsum plain text example dolor sit àmet, consectetur adipiscing elit. Ut lobortis malesuada quam ut pellentesque. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nunc ultricies egestas mauris quis ornare. Vestibulum non risus adipiscing, accumsan libero ac, vestibulum neque. Nam at nunc sed nulla varius pulvinar. Sed posuere metus velit. çras sodales nulla sit àmet feugiat dignissim. Aenean elementum dictum sapien, a iaculis augue euismod quis. Ut neque elit, pulvinar ut lectus id, adipiscing lobortis sapien. Nunc in massa elementum, dapibus dolor nec, luctus justo. Morbi eget lectus sed tortor consectetur condimentum vel quis neque. Morbi feugiat et nisl sed pretium. In bibendum vel eros id pulvinar. Nam vitae diam non lôrem sodales facilisis. Nam nunc augue, ullamcorper id eros vitae, aliquet ultricies ligula. Fusce sit àmet sem enim, nullamsed.';

    /*
    * Lorem ipsum strings with links
    */
    $lorem060link = '060 bytes lôrem ïpsum <a href="'. $href_in .'" title="'. $href_in .'">internal link</a> VS <a href="'. $href_external .'" title="'. $href_external .'" target="_blank">external link</a> à dolor';

    $lorem120link = '120 bytes lôrem ïpsum <a href="'. $href_in .'" title="'. $href_in .'">internal link</a> VS <a href="'. $href_external .'" title="'. $href_external .'" target="_blank">external link</a> dor sit àmety conse elit. Étiam suscipit velit velà enatis volutpat';

    $lorem300link = '300 bytes lôrem ïpsum <a href="'. $href_in .'" title="'. $href_in .'">internal link</a> VS <a href="'. $href_external .'" title="'. $href_external .'" target="_blank">external link</a> dolor sit àmet, consectetur adipiscing elit. Donec vel sagittis mi. Pellentesque mollis mauris in Ôdio congue dictum. Aenean ultricies ligula at dui condimentum aliquet. Donec adipiscing, magna eu vulputate mattis, rius erat, fringilla leonon mat.';

    $lorem500link = '500 bytes lôrem ïpsum <a href="'. $href_in .'" title="'. $href_in .'">internal link</a> VS <a href="'. $href_external .'" title="'. $href_external .'" target="_blank">external link</a> dolor sit àmet, consectetur adipiscing elit. Sed ut ornare enim, ac tempor velit. Pellentesque id Ôdio scelerisque, feugiat lectus non, tristique leo. Aenean tincidunt vel risus at imperdiet. Donec rutrum malesuada urna at lacinia. Praesent pharetra porttitor elit vitae varius. çras commodo magna quis erat ultrices, et ultrices rat cursus. Maecenas eg orci lôrem. Suspendisse at arcu ac nisl blandit pretium quis et elit. Quisque ultrices dolor.';
    ?>
## Plain text
The same strings displayed as pure text (within `<li>` tags):
- 010 bytes
- 015 bytes lôrem
- 020 bytes lôrem ïpsu
- 022 bytes lôrem à deux
- 023 bytes lôrem triotxt
- 024 bytes lôrem et katre
- 025 bytes lôrem vingtcinq
- 026 bytes lôrem twenty six
- 027 bytes lôrem twenty sept
- 028 bytes lôrem wenty height
- 029 bytes lôrem vingt et neuf
- 030 bytes lôrem ïpsum dolor ça
- 034 bytes lôrem ïpsum du caractère
- 035 bytes lôrem no Lady Gaga is out
- 036 bytes lôrem ïpsum des caractères
- 038 bytes lôrem Madonna is old as mamy
- 040 bytes lôrem ïpsum dolor çaga posuère
- 044 bytes lôrem ïpsum dolor çaga pour quatre
- 050 bytes lôrem ïpsum dolor encore cinquante bytes
- 060 bytes lôrem ïpsum dolor sit àmety consectetur ça au âmet
- 064 bytes lôrem ïpsum dolor sit àmety consectetur adipis sixfour
- 066 bytes lôrem ïpsum dolor sit àmety consectetur adipis sixty-six
- 068 bytes bytes lôrem ïpsum dolor sit àmety consectetur adipis sixtyheight
- 070 bytes lôrem ïpsum dolor sit àmety consectetur adipicing dè seventy
- 075 bytes lôrem ïpsum dolor sit àmet au consectetur adipiscing elit atesque
- 080 bytes lôrem ïpsum dolor sit àmet au consectetur adipiscing elit pellentesque
- 085 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elity pellentesque raçàé
- 090 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elity pellentesque çras àmets
- 100 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elit étiam suscipit velit vel venenatis
- 120 bytes lôrem ïpsum dolor sit àmety consectetur adipiscing elit. Étiam suscipit velit velà venenatis accumsan volutpat
- 200 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Nam nec pretium nulla. Étiam sollicitudin, turpis ac rhoncus fermentum, ante justo iaculis ïpsum, ac elementum Ôdio arcu nec posueres
- 300 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Donec vel sagittis mi. Pellentesque mollis mauris in Ôdio congue dictum. Aenean ultricies ligula at dui condimentum aliquet. Donec adipiscing, magna eu vulputate mattis, risus erat fringilla leo, non malesuada elit libero ac posuere.
- 500 bytes lôrem ïpsum dolor sit àmet, consectetur adipiscing elit. Sed ut ornare enim, ac tempor velit. Pellentesque id Ôdio scelerisque, feugiat lectus non, tristique leo. Aenean tincidunt vel risus at imperdiet. Donec rutrum malesuada urna at lacinia. Praesent pharetra porttitor elit vitae varius. çras commodo magna quis erat ultrices, et ultrices erat cursus. Maecenas eget orci lôrem. Suspendisse at arcu ac nisl blandit pretium quis et elit. Quisque ultrices dolor rhoncus, feugiat nulla àmet.
- 900 bytes lôrem ïpsum plain text example dolor sit àmet, consectetur adipiscing elit. Ut lobortis malesuada quam ut pellentesque. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nunc ultricies egestas mauris quis ornare. Vestibulum non risus adipiscing, accumsan libero ac, vestibulum neque. Nam at nunc sed nulla varius pulvinar. Sed posuere metus velit. çras sodales nulla sit àmet feugiat dignissim. Aenean elementum dictum sapien, a iaculis augue euismod quis. Ut neque elit, pulvinar ut lectus id, adipiscing lobortis sapien. Nunc in massa elementum, dapibus dolor nec, luctus justo. Morbi eget lectus sed tortor consectetur condimentum vel quis neque. Morbi feugiat et nisl sed pretium. In bibendum vel eros id pulvinar. Nam vitae diam non lôrem sodales facilisis. Nam nunc augue, ullamcorper id eros vitae, aliquet ultricies ligula. Fusce sit àmet sem enim, nullamsed.
