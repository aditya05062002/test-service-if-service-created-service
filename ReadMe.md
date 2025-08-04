# FastAPI Generator

This guide explains how to set up and run the **FastAPI Generator** project.

---

##  1. Create a `.env` File

Ensure that a `.env` file exists in the root directory, similar to `.env.example`.

---

##  2. Set Up and Run the Project

Open **CMD** (or terminal) at the project root and follow these steps:

---

### Create a Virtual Environment

```bash
python -m venv venv
```

---

### Activate the Virtual Environment

- **On Windows:**  
  ```bash
  venv\Scripts\activate
  ```

- **On macOS/Linux:**  
  ```bash
  source venv/bin/activate
  ```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run the FastAPI Server

```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

Once started, your FastAPI server will be available at:  
`http://localhost:8000`

---

##  Run Test Cases

Run the following command **within the virtual environment** to execute the generated test cases:

```bash
pytest
``` 
