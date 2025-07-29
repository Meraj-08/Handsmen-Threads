<div align="center">
  <br />
  <h1>🧵 HANDSMEN THREADS</h1>
  <p>
    <em>Elevating the Art of Sophistication in Men's Fashion with Salesforce-powered digital transformation.</em>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Salesforce-black?style=for-the-badge&logo=salesforce&logoColor=white&color=00A1E0" alt="Salesforce" />
    <img src="https://img.shields.io/badge/Apex-black?style=for-the-badge&logo=apachespark&logoColor=white&color=F88909" alt="Apex" />
    <img src="https://img.shields.io/badge/Lightning_App-black?style=for-the-badge&logo=zapier&logoColor=white&color=7F00FF" alt="Lightning App" />
    <img src="https://img.shields.io/badge/Flows-black?style=for-the-badge&logo=autodesk&logoColor=white&color=FF6F00" alt="Flows" />
  </p>

</div>

# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion  


---

## ✨ What is HandsMen Threads?

HandsMen Threads is a Salesforce-powered digital transformation solution for a modern fashion brand. It is built to:
- Centralize business-critical data
- Automate workflows across sales, support, and inventory
- Enable real-time insights and better collaboration

The aim is to elevate backend efficiency while creating a seamless experience for customers and internal teams alike.

---

## 🛠️ Key Features

- **Automated Order Confirmations**  
  Instantly notifies customers with email confirmations post-purchase.

- **Dynamic Loyalty Program**  
  Loyalty tiers are updated automatically based on user behavior.

- **Proactive Stock Alerts**  
  Inventory thresholds automatically trigger alerts below 5 units.

- **Scheduled Bulk Order Processing**  
  Apex batch jobs handle bulk order and inventory updates every night.

---

## ABSTRACT  

The project presents the implementation of a customized Salesforce CRM solution for HandsMen Threads, a premium men's fashion and tailoring brand. The objective was to streamline business operations, enhance customer engagement, and maintain data integrity across departments.
The solution involves designing a robust data model featuring five key custom objects: Customer, Order, Product, Inventory, and Marketing Campaign. Business processes were automatically focused: Triggered Flows, Scheduled Flows, Partial Arms, and Apex to handle other confirmations, highly status updates, and proactive stock alerts.
To ensure clean and reliable data, validation rules were established, and a role-based security model was implemented in the Sales, Inventory, and Marketing teams. The solution also includes a scheduled batch job using Apex to enable new sales quantities.
This end-to-end CRM implementation improves customer experience through personalized communication, ensures operational efficiency with automation, and lays a scalable foundation for future business growth using the Salesforce Platform.


## OBJECTIVE

The main objective of this project is to develop and implement a customized Salesforce CRM validator for Handwake Threads to streamline core business operations, maintain data integrity, and enhance customer satisfaction.
By building a centralized system to manage customers, orders, products, inventory, and marketing campaigns, the project aims to:
•	Automatic key processes such as order confirmations, loyalty status updates, and stock alerts.
•	Ensure accurate and consistent data entry using validation rules.
•	Enable real-time visibility of inventory and customer interactions.
•	Improve internal team coordination through role-based access control.
•	Deliver personalized customer experiences through targeted communication and loyalty programs.


## TECHNOLOGY DESCRIPTION

### Salesforce :
Salesforce is a cloud-based Customer Relationship Management (CRM) platform that helps businesses manage customer data, automate processes, and improve service, marketing, and sales operations. It provides paths and click tools as well as programmatic capabilities (like APIs and Flows) to build custom business solutions.

### Custom Objects :

Objects in Salesforce are like tables in a database. Custom Objects are created to store specific data.

Example:

•	Customer_ c – Stores customer info

•	Product_ c – Stores product details

•	Order_ c – Stores orders<br>


Handsmen Customers object 
<img width="868" height="599" alt="image" src="assetes/2.png" /><br><br>
Handsmen Products object
 
<img width="868" height="480" alt="image" src="assetes/3.png" /><br>

Handsmen Orders object
 
<img width="868" height="611" alt="image" src="assetes/4.png" /><br><br>
Inventorys object

<img width="868" height="537" alt="image" src="assetes/5.png" /><br><br>


### Tabs :

Tabs are used to display object data in the Salesforce UI.
Example: A lab for Product_ c allows users to easily view and manage products.
 
<img width="868" height="51" alt="image" src="assetes/tabs.png" /><br><br>

### Custom App :<br>
An App in Salesforce is a collection of tabs grouped together for a specific business purpose.
### Profiles :<br>
Profiles define what a user can see, do, and edit in Salesforce. It controls object permissions, field access, and more.<br><br>
### Roles :<br>
Roles control the data visibility in Salesforce's role hierarchy. It's used for sharing settings and reporting.<br><br>
### Permission Sets :<br>
Permission Sets grant additional permissions to users without changing their profile.<br><br>
 
### Validation Rules :<br>
Validation Rules ensure data entered meets business criteria.<br>
Example:<br>
•	Email must contain @gmail.com<br>
•	Stock cannot be negative<br>

### Email Templates :<br>
Predefined formats for sending emails to customers or users.<br>
Example:<br>
•	"Order Confirmation" template<br>
 <img width="868" height="455" alt="image" src="assetes/emailalert2.png" /><br><br>


### Email Alerts :<br>
Email Alerts are actions in Flows or Workflow Rules that send emails using predefined templates.<br>
Example:<br> When a loyalty level changes, an email is sent to the customer.<br>
Low Stock Email alert.<br>


 
<img width="866" height="455" alt="image" src="assetes/emailalert1.png" /><br><br>

 
 <img width="866" height="450" alt="image" src="assetes/loyality.png" /><br><br>

### Flows :<br>
Flows automate business logic without code. They can create, update, or send notifications.<br>
Example:<br>
•	Flow triggers email alerts on new order<br><br>
### Apex :<br>
Apex is Salesforce's object-oriented programming language. It allows developers to write custom logic.<br>
Example: <br>Triggers:<br>
•	Update Total_Amount_of in order<br>
•	Reduce inventory stock<br><br>

## CONCLUSION<br>
The HandsMen Threads CRM system built on Salesforce successfully streamlines key business processes like customer management, product cataloging, order processing, inventory tracking, and loyalty program automation. By leveraging Salesforce tools like Custom Objects, Flows, Validation Rules, and Apex, the system ensures accurate data entry, real-time updates, and enhanced customer experience. Through automation and well-structured user roles, the platform minimizes manual errors, speeds up operations, and provides better insights into sales and stock.

