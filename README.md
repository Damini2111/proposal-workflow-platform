# MNP & RSP Proposal Management System

## Overview

The **MNP & RSP Proposal Management System** is a web-based application developed using Django to manage and track proposals across the MNP and RSP modules. The system provides structured proposal listings, status-based tracking, filtering, and data management to improve accessibility and workflow efficiency.

## Key Features

- **MNP Module:** Supports proposal-related management and workflows within the MNP module.
- **RSP Module:** Provides proposal listing and status-based tracking.
- **Search and Filtering:** Filter proposal records using available criteria, such as financial year and zone.
- **Server-Side Pagination:** Loads proposal records in manageable pages to improve performance.
- **Sorting:** Organizes proposal records using supported table columns.
- **AJAX Integration:** Supports asynchronous data retrieval for interactive listings.
- **Data Export:** Supports available DataTables export options, such as CSV, PDF, and printing.
- **Django Backend:** Handles application logic and database interactions.

## Technology Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript, jQuery
- **Tables and Pagination:** jQuery DataTables
- **Communication:** AJAX and JSON
- **Database:** Project-configured database

## Project Structure

```text
MNP_RSP_dev/
├── manage.py
├── rspapp/
│   ├── views.py
│   └── templates/
│       └── list_of_rsp_proposal.html
└── README.md
```

*Note: This is a representative structure. Update it to match the actual project files and include the MNP module's paths if applicable.*

## How It Works

1. Users access the relevant MNP or RSP module.
2. Proposal records are displayed through the application's listing interfaces.
3. Users can search, filter, sort, and navigate records using the available features.
4. The Django backend processes requests and retrieves the relevant data.
5. Pagination helps manage large proposal datasets efficiently.

## Getting Started

### Prerequisites

- Python
- pip
- Git
- The database configured for the project

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Navigate to the project directory:

   ```bash
   cd MNP_RSP_dev
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure the required environment variables and database settings.

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

## Future Improvements

- Further optimize proposal listing and database queries.
- Improve pagination and filtering performance for large datasets.
- Enhance validation, error handling, and automated testing.
- Improve documentation for the MNP and RSP workflows.

## Author

**Damini**  
Computer Science Engineering

## Disclaimer

This repository should contain only code and documentation that you are authorized to publish. Remove credentials, environment files, confidential company information, and sensitive production data before making the repository public.
