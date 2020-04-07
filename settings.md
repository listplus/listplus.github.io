> You can find listing settings in `Admin -> Listings -> Settings`

## General Settings
### General
![](../images/settings-general.png)
 
- Listing Page: The page to display listing acchives (such as categories, regions, search, filter,...).
- Submit page: The page which displays the listing form.
- Listing per page: Number listing items display per page.
- Distance unit: Kilomet(km) or Mile(mi).
- Default listing status: Default listing status when users submit a new listing item.

### Permalinks
![](../images/settings-permalinks.png)

- Single Listing Slug: Permalink slug for single listing. Example: https&#58;//example.com/`{slug}`/listing-name.
- Listing Category: Permalink slug for listing category. Example: https&#58;//example.com/`{cat}`/cat-name.
- Listing Type: Permalink slug for listing category. Example: https&#58;//example.com/`{type}`/type-name.
- Listing Region: Permalink slug for listing category. Example: https&#58;//example.com/`{region}`/region-name.


### Google Map
To use google map, Just put your google map API key into settings below.
![](../images/settings-gmap.png)

Click [here](https://developers.google.com/maps/documentation/javascript/get-api-key) to learn how to get a Google Map API key.


### reCAPTCHA
**ListPlus** Support [reCaptcha v3](https://developers.google.com/recaptcha/docs/v3)
![](../images/settings-captcha.png)
- Enable?: Check this to enable reCAPTCHA.
- Recaptcha key: Recaptcha key.
- Recaptcha secret: Recaptcha secret.


When you register new reCAPTCHA site, you should select reCAPTCHA type as `reCAPTCHA v3`
![](../images/recaptcha-v3-new.png)


Click [here](https://www.google.com/recaptcha/admin/create) to register reCAPTCHA site.  
Click [here](https://developers.google.com/recaptcha/docs/v3) see more details about `reCAPTCHA v3`


## Listing Settings
### Single Listing
![](../images/settings-listing-single.png)

- Toggle description: Strip listing description if it is too long with a read more/readless button.
- Show enquiry form title: Show enquiry form title from enquiry item.
- Disable listing thumbnail?: Show/Hide featured image in single listing?.
- Disable listing comments?: Show/Hide listings comments (like posts).

### Reviews
![](../images/settings-listing-reviews.png)

- Max rating score: Max rating score, default: 5 starts.
- Reviews per page: Number review per page to show.
- Default review status: Default status when new review submitted.
- Hide form title?: Hide review form title.

## Email Settings (Premium Only)
### Email General
![](../images/email-general.png)

- Admin email: Email will receive email notifications.
- Email from: Send email from this email.

### Email Enquiry
![](../images/email-enquiry.png)

- Send message to admin: Send a copy to admin.
- Send message to listing owner: Send message to listing owner.
- Subject: Email subject.
- Body: Email body.


### Email Claim
![](../images/email-claim.png)

- Admin Email: Email to receive notifications.
- Email Subject: Email claim subject.
- Email Body: Email claim body.

### Email Review
![](../images/email-review.png)

- Admin Email: Email to receive notifications.
- Email Subject: mail review subject.
- Email Body: Email review body.

### Email Report
![](../images/email-report.png)

- Admin Email: Email to receive notifications.
- Email Subject: mail report subject.
- Email Body: Email rereportiew body.

## Account Settings (Premium Only)
![](../images/settings-account.png)

### Account
 - Account page: The page displaying user dashboard.

> If the `WooCommerce` plugin is activated this section will hide automaticity..

### WooCommerce Integration
> This section is available only when the `WooCommerce` plugin is activated.

- Purchase to claim?: User must purchase listing packages to claim a new listing.
- Purchase to submit?: User must purchase listing packages to submit a new listing.
- Pricing page: The page to display pricing table.