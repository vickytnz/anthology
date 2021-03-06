# Anthology [![Build Status](https://travis-ci.org/JordanHatch/anthology.png?branch=master)](https://travis-ci.org/JordanHatch/anthology)

An easier way to keep track of the books on your office bookshelf.

* Uses GitHub authentication for your organisation
* Keeps track of multiple copies of each book
* Looks up book details from Google Books and Openlibrary based on the ISBN

![](http://jordanhatch.github.com/anthology/img/screenshot.png)

## Configuration

The app is configured with a collection of environment variables:

* `LIBRARY_TITLE` - name of the library, displayed throughout the app
* `GITHUB_CLIENT_ID`
* `GITHUB_CLIENT_SECRET`
* `GITHUB_ORG` - organisation username to restrict access
* `REQUEST_IP` - IP address to provide as the requester in calls to the Google Books API (required for Heroku)
* `RAILS_SECRET_TOKEN`

If you're using Airbrake or Errbit, you can set the following environment variables:

* `AIRBRAKE_API_KEY`
* `AIRBRAKE_HOST`

## Licence

Anthology is released under the [MIT Licence](http://www.opensource.org/licenses/MIT).
