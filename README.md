# Automatic Website Deployment via GitHub Actions + Webhook

## Introduction

The scenario of this deployment automation is a server hosting a static website.
The sources are hosted on GitHub. Whenever the sources are updated on GitHub,
the server builds the website via a GitHub Actions workflow and deploys the
generated static site on the webserver.

The setup described here is used for <https://www.cryptool.org/>.
