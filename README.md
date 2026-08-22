# 📘Mastering the Art of UI & API Testing with Postman & Newman – Search Feature (E-Commerce)

This project contains a complete manual testing workflow for evaluating the Search Feature of an e-commerce platform ([evershop](https://demo.evershop.io/)).
The assessment covers requirement clarification, test case design, execution on a live demo website ([evershop](https://demo.evershop.io/)), defect logging, and both UI & API validation of a happy-path search and checkout journey.

##  📑 Project Overview

This assessment focuses on testing a newly requested Dynamic Search Feature for a shoe-selling e-commerce platform.
The project includes:

- Requirement analysis (10 priority questions)

- **Test case design** based on clarified requirements

- UI **execution** on Evershop Demo

- **API** execution using Postman

- **Defect reporting** with proper naming conventions

- test analysis & reporting
  
- End-to-End Flow with **Postman & Newman**

```text
Search Product
      ↓
Get Product Details
      ↓
View Cart
      ↓
Add Product to Cart
      ↓
Verify Cart Quantity
      ↓
Delete Product from Cart
```
## 📂 Project Structure

```text
Mastering-the-art-of-UI-and-API-testing_using_Postman_with_newman/
│
├── Test_case_failed/
├── UI_Testing-API_Testing/
├── Defect/
├── 05_E2E_API_Testing_using_Postman_with_Newman/
│   ├── newman/
│   │   ├── Newman HTML report generation
│   │   └── Newman Summary Report.pdf
│   └── allAPItesting.postman_collection.json
│
├── Question.pdf
├── Manual Testing Assessment (Answer).pdf
├── Search_Test Case Design.xlsx
├── p1-q4.postman_collection.json
└── README.md
```  

## How to Run

#### Running API tests: 
```bash
# Import `cart.postman_collection.json` into Postman  
# Run the collection (All requests)
``` 
#### Clone the repository:
```bash
git clone https://github.com/Firoz04/Mastering-the-art-of-UI-and-API-testing_using_Postman_with_newman.git
cd Mastering-the-art-of-UI-and-API-testing_using_Postman_with_newmman 
```
#### run with Newman:
```bash

npm install -g newman   # (if not installed)  
newman run allAPItesting.postman_collection.json
```
#### To generate HTML reports using Newman:
```bash
npm i newman-report-htmlextra-g #(if not installed)
newman run allAPItesting.postman_collection.json -r htmlextra
```
## 👤 Author

Md. Firoz Hasan  
GitHub: [Firoz04](https://github.com/Firoz04)
