# utl_create-png-and-pdf-matrix-barcodes-with-embedded-url-links-r-language-graphics-plot
You need the sas clasic editor to take full advantage of this post
    %let pgm=utl_create-png-and-pdf-matrix-barcodes-with-embedded-url-links-r-language-graphics-plot;

    You need the sas clasic editor to take full advantage of this post?

    PNG BARCODE
    https://tinyurl.com/y5xpej87
    https://github.com/rogerjdeangelis/utl_create-png-and-pdf-matrix-barcodes-with-embedded-url-links-r-language-graphics-plot/blob/main/rogergithub.png

    PDF BARCODE
    https://tinyurl.com/59njhunc
    https://github.com/rogerjdeangelis/utl_create-png-and-pdf-matrix-barcodes-with-embedded-url-links-r-language-graphics-plot/blob/main/rogergithub.pdf

    GITHUB
    https://tinyurl.com/46se2x9b
    https://github.com/rogerjdeangelis/utl_create-png-and-pdf-matrix-barcodes-with-embedded-url-links-r-language-graphics-plot

    HI RES COLOR ASCII IMMAGES
    https://tinyurl.com/yc6n6rtg
    https://github.com/rogerjdeangelis/utl-python-very-simple-interactive-sqllite-dashboard-to-query-roger-deangelis-repositories


    SOAPBOX ON
    I usually prefer python for image processing but I was unable to get the python barcode packages to work.
    Probably I am too dumb to get it the packages to work..
    SOAPBOX OFF


    /**************************************************************************************************************************/
    /*                                         |                                         |                                    */
    /*            INPUT                        |      PROCESS                            |      OUTPUT                        */
    /*            =====                        |  CLICK ON BARCODE TOP OPEN GITHUB       | YOU NEED THE CLASSIC               */
    /*                                         |  ================================       | SAS EDITOR TO SEE ASCII            */
    /*                                         |                                         | BARCODE BELOW                      */
    /*                                         |                                         | =======================            */
    /*                                         |                                         |                                    */
    /*                                         |                                         |     •˜— ˜““ —                      */
    /*  url_to_encode <-                       | MINOR ODDITIES                          |     •˜˜˜““— —                      */
    /*   "https://github.com/rogerjdeangelis"  |                                         |     ›˜œ™˜–œšŸ                      */
    /*                                         | WARNINGS AND ERROR IN LOG               |     ›˜œ™˜–œšŸ                      */
    /*                                         | BUT THE CODE WORKS                      |     ›˜œ™˜–œšŸ                      */
    /*       I DECIDED TO REMOVE TEXT          |                                         |                                    */
    /*       ABOVE THE BARCODE                 |                                         | FOR PDF and PNG BARCODES           */                                              |                                    */
    /*                                         | custom_create_PDF(                      | SEE                                */
    /*                                         |   Labels =                              |                                    */
    /*                                         |    "https://github.com/rogerjdeangelis",|                                    */
    /*                                         |   name = "d:/pdf/rogergithub",          | If you point your IPHONE camera    */
    /*                                         |   alt_text=" ",                         | on either barcode it will          */
    /*                                         |   type = "matrix",                      | open up my home github page        */
    /*                                         |   label_width = 8.5,                    |                                    */
    /*                                         |   label_height = 11,                    | PNG BARCODE                        */
    /*                                         |   width_margin = 0.5,                   | https://tinyurl.com/y5xpej87       */
    /*                                         |   replace_label=TRUE,                   |                                    */
    /*                                         |   denote = " "                          | PDF BARCODE                        */
    /*                                         |   )                                     | https://tinyurl.com/59njhunc       */
    /*                                         | convert_to_png(                         |                                    */
    /*                                         |   "d:/pdf/rogergithub.pdf"              |                                    */
    /*                                         |  ,dpi = 150)                            |                                    */
    /*                                         |                                         |                                    */
    /*                                         | If you point your IPHONE camera         |                                    */
    /*                                         | on either barcode it will               |                                    */
    /*                                         | open up my home github page             |                                    */
    /*                                         |                                         |                                    */
    /*                                         |                                         |                                    */
    /**************************************************************************************************************************/

    /*                   _
    (_)_ __  _ __  _   _| |_
    | | `_ \| `_ \| | | | __|
    | | | | | |_) | |_| | |_
    |_|_| |_| .__/ \__,_|\__|
            |_|
    */

    url_to_encode <-
     "https://github.com/rogerjdeangelis"


    /*
     _ __  _ __ ___   ___ ___  ___ ___
    | `_ \| `__/ _ \ / __/ _ \/ __/ __|
    | |_) | | | (_) | (_|  __/\__ \__ \
    | .__/|_|  \___/ \___\___||___/___/
    |_|
    */

    %utlfkil(d:/pdf/rogergithub.pdf);
    %utlfkil(d:/pdf/rogergithub.png);

    %utl_rbeginx;
    parmcards4;
    library(baRcodeR)
    library(texor)
    custom_create_PDF(
      Labels = "https://github.com/rogerjdeangelis",
      name = "d:/pdf/rogergithub",
      alt_text=" ",
      type = "matrix",
      label_width = 8.5,
      label_height = 11,
      width_margin = 0.5,
      replace_label=TRUE,
      denote = " "
      )
      convert_to_png(
         "d:/pdf/rogergithub.pdf"
        ,dpi = 150)
    ;;;;
    %utl_rendx;

    /*           _               _
      ___  _   _| |_ _ __  _   _| |_
     / _ \| | | | __| `_ \| | | | __|
    | (_) | |_| | |_| |_) | |_| | |_
     \___/ \__,_|\__| .__/ \__,_|\__|
                    |_|
    */

    PNG BARCODE
    https://tinyurl.com/y5xpej87

    PDF BARCODE
    https://tinyurl.com/59njhunc

      •˜— ˜““ —
      •˜˜˜““— —
      ›˜œ™˜–œšŸ
      ›˜œ™˜–œšŸ
      ›˜œ™˜–œšŸ

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */
