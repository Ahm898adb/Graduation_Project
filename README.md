Edge Plate OCR Project

This is the final project for the CCITS (College of Computer and Information Technology Studies) — Computer Network major at King Faisal University.

Simple edge service that watches a folder for images, runs YOLO + OCR to read license plates, stores plates in a local SQLite database, and can post violations to a backend or send plate data over TCP.

How to use:

    Edit config.py values as needed.
    Create a Python virtual environment:
    python3 -m venv venv
    source venv/bin/activate
    Install requirements:
    pip install -r requirements.txt
    Run:
    python main.py
