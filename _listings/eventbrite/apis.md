---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite brings people together through live experiences. Discover
  events that match your passions, or create your own with online ticketing tools.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
x-kinRank: "9"
x-alexaRank: "643"
tags: Discounts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite - Get Discounts Discount
  x-api-slug: discountsdiscount-id-get
  description: Returns the cross_event_discount with the specified :discount_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Discounts
  x-api-slug: discounts-post
  description: Creates a discount. Returns the created cross_event_discount.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discounts-post-openapi.md
- name: Eventbrite - Post Discounts Discount
  x-api-slug: discountsdiscount-id-post
  description: Updates the discount with the specified :discount_id. Returns the updated
    cross_event_discount. The fields sent are the ones that are going to be updated,
    the fields that are not sent will be unchanged. The same conditions and notes
    for the discount creation apply.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Discounts Discount
  x-api-slug: discountsdiscount-id-delete
  description: |-
    Deletes the cross_event_discount with the specified :discount_id.
    Only unused discounts can be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/discountsdiscount-id-delete-openapi.md
- name: Eventbrite - Get Events Discounts
  x-api-slug: eventsiddiscounts-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscounts-get-openapi.md
- name: Eventbrite - Post Events Discounts
  x-api-slug: eventsiddiscounts-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscounts-post-openapi.md
- name: Eventbrite - Get Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-delete
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-openapi.md
- name: Eventbrite - Get Events Public Discounts
  x-api-slug: eventsidpublic-discounts-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discounts-get-openapi.md
- name: Eventbrite - Post Events Public Discounts
  x-api-slug: eventsidpublic-discounts-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discounts-post-openapi.md
- name: Eventbrite - Get Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-delete
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-openapi.md
- name: Eventbrite - Get Users User Discounts
  x-api-slug: usersuser-iddiscounts-get
  description: |-
    Returns a paginated response of cross_event_discount for the specified user.
    This operation is only supported for the currently authenticated user. The alias me (/users/me/) may be used.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/usersuser-iddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/usersuser-iddiscounts-get-openapi.md
- name: Eventbrite - Get Event List Discounts
  x-api-slug: event-list-discounts-get
  description: This method returns a list of discounts for a given event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/event-list-discounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discounts/master/_listings/eventbrite/event-list-discounts-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://europeana.api.gallery.streamdata.io
- type: x-api-stack
  url: http://eventbrite.stack.network
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-crunchbase
  url: https://crunchbase.com/organization/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-twitter
  url: https://twitter.com/eventbrite
- type: x-website
  url: http://eventbriteapi.com
- type: x-website
  url: http://developer.eventbrite.com/
- type: x-website
  url: http://eventbrite.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---