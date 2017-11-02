### Editing guide

#### Update homepage intro phrase

To change the little phrase below the slideshow on the homepage edit [this file](https://github.com/toybreaker/deumah/blob/master/_includes/editables/intro.md)


#### Update promotion text

You will need to edit 2 files:

To change the promotion text block, edit [this file](https://github.com/toybreaker/deumah/blob/master/_includes/editables/promotion.md)

To turn on the promotion block, set ``` promotion: on ``` at line 6 in [the index.md file](https://github.com/toybreaker/deumah/blob/master/index.md)

Then edit the other promotion details at lines 6, 7, 8, 9,

``` promotion_title: Special Promotion ```

``` promotion_subtitle: Just for the current month! ```

Then put the promotion image somewhere in the assets folder and write the path to it as this:
``` promotion_image: /assets/p/products/promo/spa.jpg ```
and if you need to enable the "book now" button, which will send an email to you, set
``` promotion_button: true ```


#### Update contact infos, tel. and any other site wide informations.

Change [lines 17>38 in config file](https://github.com/toybreaker/deumah/blob/master/_config.yml)

#### Adding products

Add a  ```new_page_title.md ``` into [the products folder](https://github.com/toybreaker/deumah/tree/master/_products)

The easiest way is to copy an existing file and edit it. Fill the necessary ["YAML Front Matter"](https://jekyllrb.com/docs/frontmatter/) section variables properly.

Note that photos need to be [uploaded here](https://github.com/toybreaker/deumah/tree/master/assets/p/products) and need to have the same name as the .md file, as this: ``` new_page_title.jpg``` , ``` new_page_title-01.jpg``` , ``` new_page_title-02.jpg```  etc...

If you upload more than one image set ```many_pictures: true ``` and it will be coming out as a slideshow.

The ```image:``` part of the YAML front matter is used only in the SEO section of the page.

If the product is new set ```tag: new ``` so it will be displayed with a "new" little flag.

If you want the product to appear into the home page set ```featured: true```

If you want a product to appear only in the [complete offer page](https://deumahbali.com/offer/) set
```publish: notyet``` this will turn on "coming soon" little flag too.

## Warning:

Despite this repo being public, it doesn't mean that all these assets are open-source and/or copyright free, or even that you may use any of them. Please, ask for permission first by contacting us: info@junglestar.org  

All photos are © by the photographers, all rights are reserved.  

Thanks, the [Junglestar](http://junglestar.org) team.
