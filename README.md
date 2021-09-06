# Postman collection for Typesense

As an alternative to accessing Typesense API via `curl` commands on your terminal, we have just made it easier for you by providing all the resources of Typesense API into a <a href="typesense.postman_collection.json" download="/typesense.postman_collection.json">Postman collection</a>.

## Import the collection

Once you have downloaded the [Postman collection](typesense.postman_collection.json), you need to import it into Postman.

![Collection import](/screenshots/Import.png)

you should now be able to see the collection on to your left.

![Collection](/screenshots/collection.png)

## Import the environment

We have provided the [Postman Environment](/typesense.postman_environment.json) -- you need to import that as well.

![Environment Import](/screenshots/env_import.png)
---
**NOTE**

To get a better understanding of what Postman environments are take a look at [here](https://learning.postman.com/docs/sending-requests/managing-environments/).

---
## Edit the environment

![Edit](/screenshots/edit_collection.png)

Set the TYPESENSE_API_KEY to your key that you have used to spin up typesense.

![Edit API Key](/screenshots/set_api_url.png)

Set the url to typesense

![Edit url](/screenshots/set_api_url.png)

## That's it!

You can now use the collection to test out all the API's of Typesense.

![Create collection](/screenshots/create_collection.png)
