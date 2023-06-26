# graduation-project 🎓

This repository contains the submodules for the Graduation Project. Each submodule represents a different component of the project, providing specific functionality and features. The submodules/repos included in this repository are as follows:

## 1. sap-app

### Description

The `sap-app` submodule is a Flutter application designed to facilitate the process of obtaining prescribed medications from an automatic medicines vending machine. It provides features for patients, doctors, and admins to interact with the system.

### Features

#### Patient

- Prescription History
- Prescription QR Code
- Payment
- QR Code Display

#### Doctor

- Prescription Creation
- Prescription History

#### Admin

- Medicine Management

### Used Packages

- qr_flutter
- flutter_barcode_scanner
- provider
- flutter_stripe
- graphql_flutter
- http

For detailed information about the `sap-app` submodule, please refer to the [sap-app/README.md](sap-app/README.md) file.

## 2. sap-backend

### Description

The `sap-backend` submodule is an Apollo GraphQL server that serves as the backend for the SAP Mobile App. It provides various functionalities such as user management, medicine management, prescription management, and payment processing.

### Features

- User Management
- Medicine Management
- Prescription Management
- Payment Processing

### Used Technologies

- Apollo Server
- GraphQL
- MongoDB
- Node.js
- Express
- Stripe

For detailed information about the `sap-backend` submodule, please refer to the [sap-backend/README.md](sap-backend/README.md) file.

## 3. sap-pi-app

### Description

The `sap-pi-app` submodule is a tablet application developed using Flutter. It allows users to interact with a machine controlled by a Raspberry Pi for receiving prescriptions and ordering over-the-counter (OTC) medicines. The app provides a seamless experience for users to easily manage their medication needs.

### Features

- Receive Prescription
- Order Medicines

### Used Packages

- flutter_barcode_scanner
- flutter_stripe
- provider
- http

For detailed information about the `sap-pi-app` submodule, please refer to the [sap-pi-app/README.md](sap-pi-app/README.md) file.

## 4. sap-pi-backend

### Description

The `sap-pi-backend` submodule is a FastAPI server for controlling the Smart Automatic Pharmacy (SAP). It provides a RESTful API for managing medicines, prescriptions, and performing various actions related to SAP.

### Features

- List Medicines
- List OTC Medicines
- Show Medicine
- List Prescriptions
- Show Prescription
- Verify Prescription Medicines Availability
- Process Prescription
- Order Medicines
- Shelf Action

### Technologies Used

- FastAPI
- MongoDB
- Motor
- gpiozero

For detailed information about the `sap-pi-backend` submodule, please refer to the [sap-pi-backend/README.md](sap-pi-backend/README.md) file.
