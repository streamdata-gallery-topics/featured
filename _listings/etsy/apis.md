---
name: Etsy
x-slug: etsy
description: Find handmade, vintage, and unique goods that express who you are.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
x-kinRank: "9"
x-alexaRank: "187"
tags: Featured
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/apis.md
specificationVersion: "0.14"
apis:
- name: Etsy Get Homepages Pickers Featured Listing Picker
  x-api-slug: etsy
  description: Retrieves a FeaturedListingPicker by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}
  tags: Home Pages,Pickers,Featured,Listing,Picker
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepagespickersfeatured-listing-picker-id-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Featured
  x-api-slug: etsy
  description: Retrieves a set of FeaturedListing objects associated to a FeaturedListingPicker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/featured
  tags: Home Pages,Pickers,Featured,Listing,Picker,Featured
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepagespickersfeatured-listing-picker-idfeatured-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Listings
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListingPicker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/listings
  tags: Home Pages,Pickers,Featured,Listing,Picker,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepagespickersfeatured-listing-picker-idlistings-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Listings Active
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListingPicker
    in scope active.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/listings/active
  tags: Home Pages,Pickers,Featured,Listing,Picker,Listings,Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepagespickersfeatured-listing-picker-idlistingsactive-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing
  x-api-slug: etsy
  description: Retrieves a FeaturedListing by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}
  tags: Home Pages,Listings,Featured,Listing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepageslistingsfeatured-listing-id-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing Picker
  x-api-slug: etsy
  description: Retrieves a set of FeaturedListingPicker objects associated to a FeaturedListing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}/picker
  tags: Home Pages,Listings,Featured,Listing,Picker
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepageslistingsfeatured-listing-idpicker-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing Listing
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}/listing
  tags: Home Pages,Listings,Featured,Listing,Listing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/homepageslistingsfeatured-listing-idlisting-get-openapi.md
- name: Etsy Get Shops Shop Listings Featured
  x-api-slug: etsy
  description: Retrieves Listings associated to a Shop that are featured
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/featured
  tags: Shops,Shop,Listings,Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/shopsshop-idlistingsfeatured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/shopsshop-idlistingsfeatured-get-openapi.md
- name: Etsy Get Featured Users
  x-api-slug: etsy
  description: Finds all FeaturedUser.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///featured/users
  tags: Featured,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/featuredusers-get-openapi.md
- name: Etsy Get Featured Users Featured User
  x-api-slug: etsy
  description: Retrieves a FeaturedUser by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///featured/users/{featured_user_id}
  tags: Featured,Users,Featured,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/featuredusersfeatured-user-id-get-openapi.md
- name: Etsy
  x-api-slug: etsy
  description: Etsy is a handmade marketplace. The Etsy API lets developers tap into
    the Etsy community, building their own Etsy-powered applications for the web,
    desktop and mobile devices. Applications built on the API will connect buyers
    with sellers, promote the handmade lifestyle, and support the craftspeople who
    sell on Etsy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private/
  tags: Featured
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/featured/master/_listings/etsy/openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/etsy.json
- type: x-application-gallery
  url: https://www.etsy.com/apps/
- type: x-base
  url: https://openapi.etsy.com/
- type: x-blog
  url: http://www.etsy.com/blog/en/
- type: x-blog-rss
  url: https://blog.etsy.com/en/feed/
- type: x-copyright
  url: https://www.etsy.com/help/article/482/?ref=ftr
- type: x-crunchbase
  url: https://crunchbase.com/organization/etsy
- type: x-crunchbase
  url: http://www.crunchbase.com/company/etsy
- type: x-developer
  url: https://www.etsy.com/developers/
- type: x-email
  url: enaffiliates@etsy.com
- type: x-email
  url: selleraffiliate@etsy.com
- type: x-email
  url: developer@etsy.com
- type: x-email
  url: legal@etsy.com
- type: x-email
  url: dpo@etsy.com
- type: x-email
  url: dispute-resolution@etsy.com
- type: x-forum
  url: https://www.etsy.com/developers/discussion
- type: x-github
  url: https://github.com/etsy
- type: x-privacy
  url: https://www.etsy.com/help/article/480/?ref=ftr
- type: x-terms-of-service
  url: https://www.etsy.com/help/article/479/?ref=ftr
- type: x-transparency-report
  url: http://blog.etsy.com/news/files/2015/07/Etsy_TransparencyReport_2014.pdf
- type: x-twitter
  url: https://twitter.com/Etsy
- type: x-website
  url: http://www.etsy.com/
- type: x-website
  url: http://etsy.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---