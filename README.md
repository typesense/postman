# Postman collection for Typesense

If you tired of using the `curl` command in your terminal to test typesense api's , we have just made it easier for you by providing all the routes of Typesense API into a <a href="Typesense-v0.21.0.postman_collection.json" download="https://www.postman.com/typesense/workspace/typesense-api/overview">Postman collection</a>.

There are two methods you can use our postman collection. One is from the postman public API directory and other is just download the json from this Github repository and import it to your postman. We have shared the steps below for both the methods.

# Method - 1 - Importing from postman public API directory
Navigate to this <a href="Typesense-v0.21.0.postman_collection.json" download="https://www.postman.com/typesense/workspace/typesense-api/overview">Postman collection</a>, login into your postman click on typesense on to the left and select fork. Forking creates a copy of the collection in your account. 

![](/screenshots/Fork_1.png)

Give it a name and the workspace to which you want to import it.

![Collection](/screenshots/fork_2.png)

## Import the environment

We have provided the [Postman Environment](/Typesense-v0.21.0.postman_environment.json), you need to import that as well.

![Environment Import](/screenshots/env_import.png)
---
**NOTE**

To get a better understanding of what postman environments are take a look at [this.](https://learning.postman.com/docs/sending-requests/managing-environments/)

# Method - 2 - Importing from Github Repository
## Import the collection

Once you have downloaded the [Postman collection](Typesense-v0.21.0.postman_collection.json), you need to import it into Postman.

![Collection import](/screenshots/Import.png)

you should now be able to see the collection on to your left.

![Collection](/screenshots/collection.png)

## Import the environment

We have provided the [Postman Environment](/Typesense-v0.21.0.postman_environment.json), you need to import that as well.

![Environment Import](/screenshots/env_import.png)
---
**NOTE**

To get a better understanding of what postman environments are take a look at [this.](https://learning.postman.com/docs/sending-requests/managing-environments/)

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