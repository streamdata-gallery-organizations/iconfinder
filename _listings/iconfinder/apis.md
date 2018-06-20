---
name: Iconfinder
x-slug: iconfinder
description: Iconfinder is the leading search engine and market place for vector icons
  in SVG, PNG, CSH and AI format..
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
x-kinRank: "7"
x-alexaRank: "4089"
tags: Iconfinder
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/apis.md
specificationVersion: "0.14"
apis:
- name: Icon Finder Get author details
  x-api-slug: icon-finder
  description: Get details about a specific author identified by a unique ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///authors/{authorID}
  tags: Authors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/authorsauthorid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/authorsauthorid-get-openapi.md
- name: Icon Finder List all categories
  x-api-slug: icon-finder
  description: List all categories sorted ascendingly by their identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///categories
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/categories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/categories-get-openapi.md
- name: Icon Finder Search for icons
  x-api-slug: icon-finder
  description: Search through icons by various criteria. The returned list of icons
    is ordered descendingly by popularit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///icons/search
  tags: Icons,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/iconssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/iconssearch-get-openapi.md
- name: Icon Finder Get license details
  x-api-slug: icon-finder
  description: Get details about a specific license by its unique ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///licenses/{licenseID}
  tags: Licenses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/licenseslicenseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/licenseslicenseid-get-openapi.md
- name: Icon Finder Get style details
  x-api-slug: icon-finder
  description: Get details about a specific style identified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///styles/{styleID}
  tags: Styles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/stylesstyleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/stylesstyleid-get-openapi.md
- name: Icon Finder Get Authentication User.
  x-api-slug: icon-finder
  description: Gets an authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///user
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/user-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/user-get-openapi.md
- name: Icon Finder Get category details
  x-api-slug: icon-finder
  description: Get details about a specific category identified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///v2/categories/{categoryID}
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2categoriescategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2categoriescategoryid-get-openapi.md
- name: Icon Finder Get icon details
  x-api-slug: icon-finder
  description: Get details about a specific ico
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///v2/icons/{iconID}
  tags: Icons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2iconsiconid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2iconsiconid-get-openapi.md
- name: Icon Finder List all icons in an icon set
  x-api-slug: icon-finder
  description: Provides a list of all icons in an icon set sorted descendingly by
    the popularity of the icons.List all icons in an icon set
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///v2/iconsets/{iconID}/icons
  tags: Icons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2iconsetsiconidicons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2iconsetsiconidicons-get-openapi.md
- name: Icon Finder List all styles
  x-api-slug: icon-finder
  description: List all styles sorted ascendingly by their identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2///v2/styles
  tags: Styles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2styles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/v2styles-get-openapi.md
- name: Icon Finder Get user details
  x-api-slug: icon-finder
  description: Get details about a specific user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2//GET /v2/users/{userID}
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/get-v2usersuserid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/get-v2usersuserid-get-openapi.md
- name: Icon Finder Get user details
  x-api-slug: icon-finder
  description: Get details about a specific user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2//GET /v2/users/{username}
  tags: ',Users,Username'
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/get-v2usersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/get-v2usersusername-get-openapi.md
- name: Icon Finder
  x-api-slug: icon-finder
  description: Iconfinder is the leading search engine and market place for vector
    icons in SVG, PNG, CSH and AI format..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1538-iconfinder.jpg
  humanURL: http://iconfinder.com
  baseURL: https://api.iconfinder.com//v2/
  tags: Iconfinder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/iconfinder/master/_listings/iconfinder/openapi.md
x-common:
- type: x-base
  url: https://www.iconfinder.com/xml/
- type: x-blog
  url: http://www.iconfinder.com/blog
- type: x-blog-rss
  url: http://blog.iconfinder.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/iconfinder
- type: x-crunchbase
  url: https://crunchbase.com/organization/iconfinder
- type: x-developer
  url: http://www.iconfinder.com/about/api
- type: x-email
  url: support@iconfinder.com
- type: x-email
  url: contact@iconfinder.com
- type: x-github
  url: https://github.com/iconfinder
- type: x-pricing
  url: https://www.iconfinder.com/pro
- type: x-privacy
  url: https://www.iconfinder.com/about/privacypolicy
- type: x-terms-of-service
  url: https://developer.iconfinder.com/api/2.0/terms.html
- type: x-twitter
  url: https://twitter.com/iconfinder
- type: x-website
  url: http://iconfinder.com
- type: x-website
  url: http://www.iconfinder.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---