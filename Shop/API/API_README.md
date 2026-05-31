# 🔌 API Testing — demoshopping.ru

REST API testing for an online electronics store [demoshopping.ru](http://demoshopping.ru).  
Collection created in **Postman**, exported as JSON.

---

## File

| File | Description |
|---|---|
| [Shopping_postman_collection.json](./Shopping_postman_collection.json) | Postman collection — import directly into Postman |

---

## Endpoints Covered

| Module | Method | Endpoint | Description |
|---|---|---|---|
| **User** | POST | /register | New user registration |
| **User** | POST | /login | User login |
| **Products** | GET | /products | Get product list |
| **Products** | GET | /products/id/{id} | Get product by ID |
| **Products** | POST | /add-product | Create new product |
| **Products** | PUT | /products/id/{id} | Full product update |
| **Products** | PATCH | /products/id/{id} | Partial product update |
| **Products** | DELETE | /products/id/{id} | Delete product |
| **Cart** | POST | /cart | Add item to cart |
| **Cart** | GET | /getCart | Get cart contents |
| **Cart** | PATCH | /cart/{id} | Update cart item |
| **Cart** | DELETE | /cart/{id} | Remove item from cart |
| **Payment** | POST | /pay | Process payment |

---

**To use:** Import `Shopping_postman_collection.json` into Postman via File → Import
