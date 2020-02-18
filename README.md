# simple-api
class 06 lab

## simple api

- [x] Implement an API server suitable for a storefront, using json-server
- [x] Connect a web server
- [ ] Swagger Documentation
- [ ] Stretch: Alter json-server to produce proper standardized API output

### Author: Kevin Dreyer

### Links and Resources

http test commands

POST
```cmd
http post :3000/categories name="Tech" display_name="Electronics" description="Tech products"
http post :3000/categories name="Books" display_name="books" description="Read material"
http post :3000/categories name="Groceries" display_name="Food" description="things to eat"
http post :3000/products category="Tech" name="TV" display_name="Television" description="flat screen tv"
http post :3000/products category="Books" name="Ulysses" display_name="Ulysses hard cover" description="Ulysses chronicles the passage of"
```
GET
```cmd
http get :3000/categories
http get :3000/products
http get :3000/products/1
```
PUT
```cmd
http put :3000/products/4 category="Books" name="Ulysses" display_name="Ulysses soft cover" description="Ulysses chronicles the passage of"
```
DELETE
```cmd
http delete :3000/categories/1
```