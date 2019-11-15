# Backoffice Users and API Keys

In this article you will learn how to add Users to the backoffice and how to manage the API Keys.

## The Backoffice User

A Backoffice user can be added in two ways.

-   Added from the portal from the Team Management section, or
-   From the Users Section in the Backoffice

A feature that is unique for Heartcore is the option to create an API Key for specific users. The API Key can be created from the API Key section of the User page. This page can be found under the Users Section in the top-left navigation of the backoffice.

![User Page in the Backoffice](images/userAPI.png)

## API Keys

In order to connect to the two APIs your user will need to have an API Key assinged. When you have navigated to the section mentioned above you can create the API Key by clicking the "Create API Key" button.

A modal will pop up where you enter the Name of the Key and set a date for when it should expire. If there is no expire data, the API Key will be valid until you delete it manually.

![Creating the API Key](images/createAPI.png)

Once the API Key has been created you will see the actual key and two examples on how to use the Key with the Authorization header and an API-Key header.

![The created API Key](images/generatedAPI.png)

You are able to see a list of all your created API Keys and all relevant information. You are also able to revoke a generated key.

![List of all APIs](images/listOfAPIs.png)