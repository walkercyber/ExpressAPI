# ExpressAPI

This project is a simple **Node.js + Express** application that acts as a **proxy API** for a remote **.NET API** hosted at  
[`https://isabelladaoodapi.azurewebsites.net/`](https://isabelladaoodapi.azurewebsites.net/).

It allows users to **fetch** and **create** product data through endpoints that forward requests to the external .NET API.

---

## 🚀 Features
- Built with **Node.js** and **Express**
- Connects to a remote **.NET Web API**
- Two main endpoints:
  - `GET /products` — Retrieves all products from the .NET API  
  - `POST /product` — Sends new product data to the .NET API
- Includes an HTML documentation page for easy reference

