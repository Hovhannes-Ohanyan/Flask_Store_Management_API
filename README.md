Flask Store Management API

The Flask Store Management API is a simple web application that allows you to create stores,
add items to stores, list stores and their items, and retrieve store and item details.
It is built using the Flask web framework in Python.

Usage

Creating a Store
To create a new store, send a POST request to /stores with JSON data containing the store name.


Adding an Item to a Store
To add an item to a specific store, send a POST request to /stores/{store_name}/items with JSON data containing the item name and price.


Listing All Stores
To retrieve a list of all stores and their respective items, send a GET request to /stores.


Retrieving Store Details
To retrieve details about a specific store, send a GET request to /stores/{store_name}.

Retrieving Items in a Store
To retrieve a list of items within a specific store, send a GET request to /stores/{store_name}/items.
