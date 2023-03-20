
# TMS: Tranportation Management System

The TMS is a prototype transportation management system developed for Fake Corporation's shipping and logistics division. The system allows the company's staff members to manage the order creation, management, and billing process for their customers.

##  Disclaimer

The project available in this repository is an academic project and is not intended to be publicly available since it is related to academic coursework, and there is a potential for academic misconduct if it is used improperly. Therefore, only a video recording of the project is available for viewing.

If you would like to request access to code base and additional materials related to this project, please contact me directly and make your request. Please note that access to any additional materials will be granted solely at my discretion and only for legitimate educational or research purposes.

By accessing the video recording of this project, you acknowledge and agree that you will not use it for any unauthorized or unethical purposes, and that any misuse of the project may result in serious consequences, including academic penalties and disciplinary action.
## Project Overview

The TMS system is a critical part of the shipping and logistics industry, allowing for the purchasing, scheduling, monitoring, and billing of organizations who desire to have cargo shipped via truck or train. The TMS system is designed to be a prototype to help determine the feasibility and core issues of developing a deeper solution for the huge, multinational Fake Corporation.

The TMS solution prototype is a system that allows Fake Shipping Handling and Transportation (FSHT) staff members to manage the order creation, management, and billing process for the company. Specific, high-level functional stories and workflows are as follows:

- Call for, take, and then plan orders from the Contract Marketplace.
- Planning an order requires that the requested cargo be assigned to one or more available Carriers (e.g. Trucking Companies) that FSHT has relationships with.
- Carriers provide the Trips necessary to deliver Orders to their destination.
- Once scheduled, the TMS can simulate the passage of time allowing for updates on the Carrier’s trucks to be requested from the Carrier Update System.
- Once Orders are completed, the TMS system will compute the final bill for the Customer, and post the invoice to the accounts system.
## Tech Stack
The TMS solution is a WPF GUI application with a MySQL database backend. 

## Run Locally

To use the application, follow these steps:

	1. Clone the repository to your local machine
	2. Ensure that you have a MySQL server running
	3. Open the solution in Visual Studio
	4. Update the connection string in the appsettings.json file to match your database configuration
	5. Build and run the application

## Demo

Insert gif or link to demo
