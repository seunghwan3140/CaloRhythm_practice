Getting Started
===============

This guide explains how to install and run the CaloRhythm application locally.

Prerequisites
-------------
- Python 3.9+
- MySQL (for storing nutrition data)
- pip package manager
- Git
- Required libraries listed in ``requirements.txt`` :contentReference[oaicite:2]{index=2}

Installation
------------

Clone the repository:

.. code-block:: bash

   git clone https://github.com/seunghwan3140/CaloRhythm
   cd CaloRhythm

Install dependencies:

.. code-block:: bash

   pip install -r requirements.txt

Database Setup
--------------
The system requires nutrition data in a MySQL database.  
You must:

1. Install MySQL server  
2. Create schema & import nutrient data  
3. Configure your credentials inside the application  

Running the Application
-----------------------

CaloRhythm uses Streamlit as its UI framework:

.. code-block:: bash

   streamlit run main.py

Once launched, you will see the nutrition calculator, optimizer, and nutrient
discovery tools.
