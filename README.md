# Ecommerce WebApp Using Django Framework

![Logo](./Student%20information%20system.jpg)

A simple project based on an Online Ecommerce Site that uses Python with Django Web Framework. Following Django project contains all the important features which can be in use for the second year IT students for their college projects. It has a number of important features(codeastro.com) that will allow the users to shop online, manage orders, and more. This system as well as the website’s concept is all clear, it’s the same as real-life scenarios and well-implemented on it. 

In particular, this eCommerce site project in Python Django focuses mainly on dealing with online shopping, and order management. Also, the system displays all the available products. In addition, the system allows managing customer records. Evidently, this project is divided into two categories: Customer, and Admin Panel. In an overview of this web application, a customer can simply register from the client-side. Initially, the website displays all the available products with their respective details. Just like every other eCommerce website, this one has also got a cart system. This allows the customers to add a number of products to their cart before checking out. Speaking of check out, there’s a simple payment form that needs to be completed by the customers. In fact, the customers can view their orders list and track orders after successful payment. Besides, customers can make search queries and update their user profiles.

## Admin Panel
An administrator has full control over the system. He/she can manage customers, orders, and products. Here, each and every section has its own respective details such as name, images, and other important details. The very first step of the management of this system is to set up products. There are minor fields for each such as name, short description, price, and image(codeastro.com). All the published products are totally visible from the client-side. By accessing the admin panel, the user can oversee the overall records such as the number of registered users, orders, and published products. Talking about the registered users, the admin can view a list of users with every possible detail. Here, the admin can take actions such as removing or updating customers’ details.

## Order Management and Invoice
Moving towards the order management section, the system forwards each and every customer’s order details after their successful payment. By default, every order is marked under pending status which is also visible from both. An administrator can view a number of pending orders and take action accordingly. For this, an admin has to update the order status for each(codeastro.com). The user can update the status of an order from pending to order confirmed, on the way, or delivered. Which totally depends upon the status of their product and delivery stages. In fact, with each and every update, the customers can view and track each and every order. This helps to know the information about their orders and their arrivals. With it, the customers can also download an invoice from the orders section with displays every detail related to it.

Last but not least, a clean and simple dashboard is presented with various color combinations for a greater user experience while using this eCommerce Site Project in Python Django Framework. For its UI elements, a free open-source CSS framework; Bootstrap is on board with some Vanilla CSS too(codeastro.com). Presenting a new e-commerce website Project in Python Django which includes an admin panel with client-side interaction.

[Watch Full Video]()

## Available Features:

- Client-Side Interaction
- Admin Panel
- Customer Registration
- Add to Cart System
- Search Products
- Simple Payment Structure
- List Orders
- Track Orders
- Download Invoice (PDF)
- View/Update Profile
- Order Management
- Product Management
- Customer Management

## File Stucrure

```shell
├── Ecommerce-WebApp (Current Directory)
    ├── ecom
    ├── ecommerce
    ├── templates
    ├── db.sqlite3
    ├── manage.py
    ├── requirements.txt
    └── static
        
```



## How to Install and Run this project?

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
 python -m venv venv
```
For Mac
```
python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
source venv/scripts/activate
```

For Mac
```
source venv/bin/activate
```

**3. Install Requirements from 'requirements.txt'**
```
pip install -r requirements.txt
```

**4. make database migrations**
```python
python manage.py migrate
```

**5. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email, Username and Password

**6. Now Run Server**

Command for Windows:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

## Screenshots

![Admin Page](./1.PNG)
![Stuff Page](./3.PNG)
![student Page](./4.PNG)



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.




## Authors
- [@naemazam](https://github.com/naemazam?tab=repositories)

## License

[MIT](https://choosealicense.com/licenses/mit/)


