# Contributing to Bodega Virtual

First off, thank you for considering contributing! It’s people like you who make the open-source community such a great place to learn, inspire, and create.

To maintain the quality of the project and the sanity of the maintainers, please take a moment to review these guidelines.

---

## 🏗 Our Architecture
[cite_start]As a reminder, **Bodega Virtual** is composed of three independent repositories[cite: 1]. Please ensure you are opening issues or Pull Requests in the correct repository based on the logic you are modifying:

* **[graphql-product-service](https://github.com/BodegaVirtual/graphql-product-service):** For backend API logic, AWS CloudFormation scripts, DynamoDB schemas, and Lambda functions.
* **[product-admin-app](https://github.com/BodegaVirtual/product-admin-app):** For the store owner's interface, product/category management logic, and sales tracking.
* **[product-web-app](https://github.com/BodegaVirtual/product-web-app):** For the customer-facing storefront, shopping cart functionality, and PayPal payment integration.

If your change affects the interaction between these projects, please mention the related PRs in your description.

---

## 🐛 How to Report a Bug
If you find a bug, please search the **Issues** tab of the relevant repository first to see if it has already been reported. If not, open a new issue and include:
* A clear title and description.
* Steps to reproduce the problem.
* Expected vs. Actual behavior.
* Screenshots/Logs (if applicable).

---

## 💡 Feature Requests
We’re always open to new ideas! Please open an issue labeled `enhancement` before starting work on a major feature. This allows the community to discuss the implementation and ensures the feature aligns with the project’s goals.

---

## 🚀 The Pull Request Process
1.  **Fork** the repository and create your branch from `main`.
2.  **Install dependencies** and ensure your local environment matches the production requirements (AWS/PayPal Sandbox).
3.  **Write clean code:** Follow the existing style and naming conventions.
4.  **Test your changes:** Ensure that your contribution doesn't break existing functionality.
5.  **Update documentation:** If you’re adding a feature, update the `README.md` or relevant docs.
6.  **Submit the PR:** Provide a detailed description of what you changed and why.

---

## ⚖️ License Agreement
By contributing to this project, you agree that your contributions will be licensed under the **Apache License 2.0**.

You also represent that you are the original author of the code or have the legal right to submit it. This helps us keep the project legally "clean" and protects all users from future liability or copyright claims.

---

## 💬 Need Help?
If you have questions about where a specific piece of logic should live (e.g., whether a function belongs in the GraphQL service or the Admin App), feel free to open a discussion in the main repository or reach out to the maintainers.
