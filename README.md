# Bodega Virtual

**Bodega Virtual** is a barebones online store project. It is comprised of three separate repositories designed to be independently built and deployed, while remaining logically dependent on each other to provide a full solution.

The project is designed for deployment in **AWS** and includes integrated support for the **PayPal** payment system.

---

## 🏗 Project Ecosystem

| Component | Repository | Description |
| :--- | :--- | :--- |
| **Backend** | [graphql-product-service](https://github.com/BodegaVirtual/graphql-product-service) | Responsible for data storage creation and access. |
| **Admin UI** | [product-admin-app](https://github.com/BodegaVirtual/product-admin-app) | User interface for the owner to administer the store. |
| **Customer UI** | [product-web-app](https://github.com/BodegaVirtual/product-web-app) | The online store interface for customer interaction. |

---

## 🛠 Component Breakdown

### 1. GraphQL Product Service
This backend project handles the core infrastructure. It utilizes an **AWS CloudFormation script** to provision data storage tables, lambda functions, and access configurations.

### 2. Product Admin App
This application allows the project owner to manage the store operations:
* **Product Management**: Create products and organize them into specific categories.
* **Sales Tracking**: Monitor and track sales performance across the store.

### 3. Product Web App
This is the customer-facing storefront:
* **Shopping**: Customers can view products, add them to a shopping cart, and perform purchases.
* **History**: Customers can access their current shopping cart and view their full purchase history.

---

## 🌐 Demo Environments
Use the following credentials to test the live demo applications:

| Application | URL | User | Password |
| :--- | :--- | :--- | :--- |
| **Admin App** | https://admindemo.bolito.co/ | `test@test.co` | `Demo1234` |
| **Customer App** | https://appdemo.bolito.co/ | N/A | N/A |

---

## ⚖️ License & Liability
This project is licensed under the **Apache License 2.0**.

### Limitation of Liability
This software is provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability or fitness for a particular purpose. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.
