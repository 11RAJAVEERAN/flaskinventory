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


output screenshot:
homescreen
![Screenshot (2)](https://user-images.githubusercontent.com/98136582/208214588-ce8541a5-d21b-4d3e-a305-6cfcf7f29996.png)



![Screenshot (3)](https://user-images.githubusercontent.com/98136582/208214619-9a5fe4c6-6eca-457b-a283-0b33cd714150.png)

products

![Screenshot (4)](https://user-images.githubusercontent.com/98136582/208214669-509d7e3d-56fa-435c-921d-edeba3b7ef72.png)
location
![Screenshot (6)](https://user-images.githubusercontent.com/98136582/208214696-56694492-c1e0-42d1-83a2-142dcbf8a06a.png)

move products
![Screenshot (9)](https://user-images.githubusercontent.com/98136582/208214744-aa6bd18d-a6c7-4244-afd0-a2e78539bc37.png)
![Screenshot (11)](https://user-images.githubusercontent.com/98136582/208214783-84023831-2ca1-4814-9541-2988dd43820b.png)
