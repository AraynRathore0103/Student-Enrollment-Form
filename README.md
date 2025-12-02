# Student Enrollment Form

A web-based Student Enrollment Form developed to demonstrate CRUD operations using **JsonPowerDB**. This project allows users to store student data effectively using a serverless NoSQL database approach.

## Table of Contents
- [Description](#description)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Release History](#release-history)
- [Illustrations](#illustrations)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Sources](#sources)

## Description
This project is a simple HTML form that captures student details (such as Roll No, Name, Class, Birth Date, Address, and Enrollment Date). It interacts with JsonPowerDB to save and retrieve data seamlessly. The primary focus is to showcase how to connect an HTML front-end with the JsonPowerDB backend API.

## Benefits of using JsonPowerDB
This project utilizes JsonPowerDB (JPDB) for backend storage. The benefits of using JPDB include:
- **High Performance:** It is a high-performance, real-time, lightweight, and serverless database.
- **Simple to Use:** Easy to learn and implement with simple REST API calls.
- **Serverless:** No need to manage server infrastructure; focus only on the frontend logic.
- **Dynamic:** Can handle dynamic data structures without predefined schemas.
- **Multi-mode:** Supports multiple modes of data retrieval and manipulation.

## Release History
* **v1.0.0** (2025-01-01)
    * Initial Release: Created basic enrollment form.
    * Integrated JsonPowerDB for `PUT` (Save) requests.
    * Added validation for form fields.

## Illustrations
*(Optional: You can add screenshots of your form here later by uploading images to the repo)*
![Form Screenshot](https://via.placeholder.com/600x400?text=Student+Enrollment+Form+Screenshot)

## Scope of Functionalities
- **Data Entry:** Users can input student details.
- **Data Validation:** Checks for empty fields and valid data formats.
- **Database Integration:** connecting to JsonPowerDB to store records.
- **Reset:** Ability to reset the form for new entries.

## Examples of Use
1. Open the `index.html` file in a browser.
2. Fill in the Roll No. (If the Roll No exists, data is fetched; if not, you can enter new data).
3. Fill in the remaining fields.
4. Click "Save" to store the data in the database.

## Project Status
- [x] Basic Form Structure
- [x] JsonPowerDB Connection
- [ ] Update Functionality
- [ ] Delete Functionality

## Sources
- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)