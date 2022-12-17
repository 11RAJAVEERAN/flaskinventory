# Inventory-Management webapplication used for flask framework
An inventory management system using Flask


## What to look for here?
  1.  Adding Products and Locations(#adding-products-and-locations)
  2. Deleting Products and Locations(#deleting-products-and-locations)
  3. Moving Products(#moving-products)
  4. Editing Products and Locations(#editing-products-and-locations)
- 
To run this system you will need :

- Python 
- Flask
- SQLALCHEMY
- WTForms

```
pip3 install -r requirements.txt
```

## Running the app
 Set your current path to where the cloned folder is and run the file **run.py**

### Adding Products and Locations
Products require product name and quantity to be filled. Location only requires location name

### Deleting Products and Locations
Deleting only requires a button click, although the transfers(if any) will remain in the history.

### Moving products
Here products can be moved to a location, from a location as well as to and from a location. Products need to initially be added to various locations from the central warehouse.

### Editing Products and Locations
Change in product or loaction name creates changes in their names in the history and system overview.So, you can rectify a spelling error and still not loose any data.

# Built using
- Flask
- SQLAlchemy


