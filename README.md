# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:

### Project Title or Name of the Application	: SchoolPOS Simulation
### Section			   	      : Sodium
### Group Members			    : Andreas Chance Co, Randy Remonte, Jien Audrei Tomaneng
### Date (Proposal Date)  : Nov 13, 2026

### Project Description:

SchoolPOS is a simple program that models how checkout transactions work in a school setting. Manual calculations and tracking of sales are slow and prone to error. This application aims to automate in item pricing, receipt generation, and transaction logging.

The entire system is composed of persons (customers and cashiers), whose data shall be kept private and shall be deleted when necessary; Products (goods or services) along with their quantities; transactions; and at least a money vault. 

A single Transaction has a date and time, at least one Customer, at least one Product or Service, additional discounts or fees, optional notes as strings, and a cashier in charge. In this class, total price can be calculated, and attributes may be changed through setters in case of inputting mistakes or sudden transactional changes. Transaction data can then be logged into a spreadsheet or spreadsheet-compatible file.

A Person requires a name and a list of transactions. The abstract class has two subclasses: Customer with unit (batch/faculty department), and Cashier with actual shift time ranges.

A Product has a name and a unit price. (Goods and services count here.)

The target users are cashiers in small business booths, mainly temporary ones (e.g. fundraising, school fairs). While the project application is currently intended to be a simulation, the source code may be modified for real, practical use afterwards.



### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1: Apply inheritance by extending Customer and Cashier classes from a single Person class.
- Objective 2: Automate basic math in the checkout, accounting for item quantities, service fees, discounts, and total cost.
- Objective 3: Output a receipt and save the transaction record under the customer and in a spreadsheet-compatible file (e.g. CSV, Google Sheets)

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
