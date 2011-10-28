# How to get started

## P

## Setting Environment Variables

In order to start the application you need to set the following environment variables:

* `DATA_FACEBOOK` - Contains information about the page, app credentials and administrators.

* `DATA_GOOGLE` - Contains Google Analytics ID.

* `REDISTOGO_URL` - Only for production. Will be set __automatically__ by Heroku. :)

Example for setting the environment variables on your local dev machine:

__Facebook__

```
export DATA_FACEBOOK=page_id,YOUR_PAGE_ID,app_id,YOUR_APP_ID,app_secret,YOUR_APP_SECRET,fb_page_path,YOUR_PAGE_URL,admin_id,YOUR_FB_USER_ID
```

* `YOUR_PAGE_ID`- The id of the fb page you want to use

* `YOUR_APP_ID`- App id of the facebook app you want to use to query the graph API

* `YOUR_APP_SECRET`- App secret of the facebook app

* `YOUR_PAGE_URL`- The URL of your facebook page, e.g. `fb_page_path,pages/my_fb_page/1234567890`

* `YOUR_FB_USER_ID` - Your user id (for open graph meta information)

__Google__

```
export DATA_GOOGLE=analytics,UA-XXXXXXXX-X
```