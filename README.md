# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product vision statement

A mobile-friendly web application that helps users manage their budget by tracking, searching, and organizing their spending through transaction records and balance views.

## User stories

[Link to User Stories in the Issues Page](https://github.com/software-students-fall2024/2-web-app-webstars/issues)

## Steps necessary to run the software

Before you begin, ensure you have met the following requirements:

- **Python**: This project requires Python 3.x. You can download Python from [here](https://www.python.org/downloads/).

- **Pip**: Python's package installer, `pip`, must also be installed. You can install/upgrade it by running:

  ```bash
  python -m ensurepip --upgrade
  ```

### Step 1: Clone the Repository and Navigate into project directory

To get a local copy of the project, use the following command:

```bash
git clone https://github.com/software-students-fall2024/2-web-app-webstars.git
```

Navigate into directory by running following command:

```
cd 2-web-app-webstars.git
```

### Step 2: Set up Virtual Enviroment

Create and activate a virtual environment using the following commands:

```
python -m venv venv
```

For macOS/Linux:

```
source venv/bin/activate
```

For Windows:

```
venv\Scripts\activate
```

### Step 3: Install Requirements

Install the project dependencies by running the following command:

```
pip install -r requirements.txt
```

### Step 4: Create .env file

A file named .env is necessary to run the application. This file contains sensitive environment variables holding credentials such as the database connection string, username, password, etc.

For the use of this project, the env file is sent to the admins/managers via the team's messenger channel (webstars).

### Step 5: Running the software

Run the following command:

```
python app.py
```

## Task boards

[Task Board](https://github.com/orgs/software-students-fall2024/projects/7)
