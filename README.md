# Healthcare Dataset Data Cleaning & Standardization

## Project Overview

This project demonstrates a structured **data cleaning and standardization workflow** performed on a healthcare dataset containing patient administrative and medical information.

The project was created as part of my **Data Entry & Administrative Data Management Portfolio** to demonstrate my ability to transform messy, inconsistent records into a clean, organized, and professionally formatted dataset suitable for administrative record management and further analysis.

## Dataset Description

The dataset contains patient-level records including:

* Patient Names
* Dates of Visit
* Age
* Blood Pressure
* Email Addresses
* Phone Numbers
* Medications
* Medical Conditions

The original dataset contained common real-world data-quality issues such as inconsistent capitalization, mixed date formats, missing values, inconsistent numeric entries, and formatting inconsistencies.

## Data Cleaning & Standardization Process

### 1. Patient Names

**Issue:** Patient names were entered in lowercase or inconsistent formats.

**Action:** Names were standardized using **Title Case**.

**Example:** `david lee` → `David Lee`

**Formatting:** Left-aligned

### 2. Dates of Visit

**Issue:** Dates were recorded using inconsistent formats.

**Action:** Dates were standardized into a consistent **Short Date** format.

**Formatting:** Centered/left-aligned

### 3. Missing Values

**Issue:** Missing records appeared as `NaN`, blank cells, or null values.

**Action:** Missing values in relevant fields were replaced with **N/A** to clearly identify unavailable information.

Fields addressed included:

* Age
* Blood Pressure
* Email
* Phone Number
* Medication
* Medical Condition

### 4. Age & Blood Pressure

**Issue:** Some numeric information contained inconsistent text-based entries or formatting.

**Action:** Numeric values were standardized where applicable, including converting written numbers into numerical digits.

**Formatting:** Right-aligned

### 5. Email Addresses

**Issue:** Email addresses contained inconsistent capitalization.

**Action:** Email addresses were standardized to **lowercase**.

**Formatting:** Left-aligned

### 6. Phone Numbers

**Issue:** Phone number entries required consistent formatting and alignment.

**Action:** Phone number records were standardized and organized for easier administrative use.

**Formatting:** Right/center-aligned

### 7. Medications & Medical Conditions

**Issue:** Medical information contained inconsistent capitalization and formatting.

**Action:** Medication and condition entries were standardized using **Title Case**.

**Formatting:** Left-aligned

## Professional Data Formatting Standards

| Data Type    | Examples              | Alignment    |
| ------------ | --------------------- | ------------ |
| Text         | Patient Name, Email   | Left         |
| Medical Text | Medication, Condition | Left         |
| Numeric      | Age, Blood Pressure   | Right        |
| Contact      | Phone Number          | Right/Center |
| Date         | Date of Visit         | Center/Left  |

Different alignment standards were applied according to the type of information in each column to improve readability, consistency, and professional presentation.

## Data Quality Improvements

The cleaning process focused on:

* Consistent capitalization
* Consistent date formatting
* Standardized numeric values
* Clear identification of missing information
* Consistent email formatting
* Organized contact information
* Standardized medical information formatting
* Improved readability and column structure
* Professional presentation of administrative records

## Repository Contents

 
### 📄 Cleaned Healthcare Dataset

[**View / Open healthcare_dataset_cleaned.csv**](healthcare_dataset_cleaned.csv)


## Skills Demonstrated

* Data Entry
* Data Cleaning
* Data Standardization
* Administrative Data Management
* Spreadsheet Data Organization
* Missing-Value Handling
* Text Formatting
* Date Standardization
* Numeric Data Formatting
* Healthcare Data Organization
* Data Quality Control
* Attention to Detail

## Project Purpose

The purpose of this project is to demonstrate how raw administrative records can be transformed into a **clean, consistent, and professionally organized dataset**.

These skills can be applied to roles involving:

* Data Entry
* Administrative Support
* Data Management
* Healthcare Administration
* Records Management
* Virtual Assistance
* Data Quality Assurance

## Author

**Bukkie**

Data Entry | Administrative Data Management | Data Analytics
