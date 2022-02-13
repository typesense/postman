# Postman collection for Typesense

Calling Typesense API via `curl` commands on your terminal can be a bit cumbersome.

Thankfully, we've put together a <a href="https://www.postman.com/typesense/workspace/typesense-api/overview">Postman collection</a> that you can use and share with your team. We'll also be happy to accept any changes or improvements -- send us a PR!

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
## Usage Instructions

In case you're not familiar with Postman, here's a quick walk-through on importing and using this collection.

### Step 1️⃣: Import the collection

Downloaded the [Postman collection](typesense.postman_collection.json), and import it into Postman.

![Collection import](/screenshots/Import.png)

You should now be able to see the collection on the left sidebar.

![Collection](/screenshots/collection.png)

### Step 2️⃣: Import the environment

We have also provided a [Postman Environment](/typesense.postman_environment.json) -- you need to import that as well.

![Environment Import](/screenshots/env_import.png)

> To get a better understanding of what Postman environments are, please [look here](https://learning.postman.com/docs/sending-requests/managing-environments/).

### Step 3️⃣: Edit the environment variables

![Edit](/screenshots/edit_collection.png)

Update the `TYPESENSE_API_KEY` variable match the API key that you use.

![Edit API Key](/screenshots/set_api_url.png)

Update the `url` to point to your local or remote Typesense server:

![Edit url](/screenshots/set_api_url.png)

### ✨ And that's it!

You can now use the Postman collection to hit the Typesense APIs.

![Create collection](/screenshots/create_collection.png)
