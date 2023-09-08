# C19-SYSTEM
A project based on file structures concept in C++ language which is  designed to get the input from the user to a text file and CRUD  operations are performed on the same. 
# COVID-19 Patient Record and Vaccination Management System

This C++ program is designed to manage COVID-19 patient records and vaccination appointments efficiently. It offers features for adding, searching, and displaying patient records, as well as booking vaccination slots and viewing vaccination statistics.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [COVID-19 Patient Records](#covid-19-patient-records)
- [Vaccination Management](#vaccination-management)
- [Contributing](#contributing)
- [License](#license)

## Features

### COVID-19 Patient Records

- Add patient details including BU number, name, age, phone number, and hospital.
- Search for patients by BU number or name (secondary key).
- Remove patient records.
- Display patient records.
- Secondary key index for efficient searching.
- Data files for patient records and index storage.

### Vaccination Management

- Record vaccination appointments with Aadaar number, name, age, gender, phone, and address.
- View and search vaccination records.
- Book vaccination slots with start and end times.
- Sort vaccination slots.
- Display vaccination statistics, including the number of vaccinated people and available slots.

## Getting Started

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/Venkatchavan/C19-System.git
   ```

2. Compile the C++ program using a C++ compiler (e.g., g++):

   ```shell
   g++ main.cpp -o covid_manager
   ```

3. Run the program:

   ```shell
   ./covid_manager
   ```

## Usage

### COVID-19 Patient Records

1. **Add Patient Record:** Enter patient details, including BU number, name, age, phone number, and hospital. The system will store the data and update the index files.

2. **Search Patients:** Search for patients by BU number or name (secondary key). The system displays matching records.

3. **Remove Patient Records:** Delete patient records by specifying the BU number.

4. **Display Patients:** View the details of all patients in the system.

### Vaccination Management

1. **Add Vaccination Record:** Record vaccination appointments by entering Aadaar number, name, age, gender, phone number, and address. The system will store the data and update the index files.

2. **View Vaccination Records:** Display vaccination records, including Aadaar number, name, age, gender, phone number, and address.

3. **Search Vaccination Records:** Search for vaccination records by name (secondary key) and display matching records.

4. **Book Vaccination Slots:** Book available vaccination slots with specified start and end times.

5. **Sort Vaccination Slots:** Sort the vaccination slots based on start times.

6. **View Vaccination Statistics:** Check the number of people vaccinated and the available slots.

## Contributing

If you'd like to contribute to this project or have suggestions for improvements, please feel free to open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the Venkat Chavan N and Sandhya Shanbhag.Contact venkatchavan1999@gmail.com 
```

You can use this README as a starting point and customize it further based on your preferences. It provides an overview of the program's features, instructions for getting started, and details on how to use the system for managing COVID-19 patient records and vaccination appointments.
