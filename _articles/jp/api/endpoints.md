---
changelog: 
last_modified_at: 
title: Endpoints and testing the API
redirect_from: []
date: 2019-03-29T16:53:56.000+00:00
menu:
  api-main:
    weight: 5

---
{% include not_translated_yet.html %}

## Endpoints

The [Bitrise API endpoint reference documentation](https://api-docs.bitrise.io) lists every available endpoint and their parameters, along with the possible responses. You can also try them out!

### Testing the API

You can try out any endpoint in the reference documentation itself! All you need to do is authenticate yourself and provide the required parameters. The API will return the appropriate response based on the call.

1. [Acquire a Personal Access Token](/api/v0.1#acquiring-a-personal-access-token).
2. Go to the [Bitrise API endpoint reference documentation](https://api-docs.bitrise.io).
3. Click `Authorize`.

   ![{{ page.title }}](/img/authorize.png)
4. Paste your Personal Access Token to the `Value` field.

   ![{{ page.title }}](/img/available-auth.png)
5. Click on the endpoint you want to try it out to open its details.
6. Fill in the required parameters.
7. Click `Execute`.

The API will return:

* The `curl` command of your request.
* The request URL.
* The server response.