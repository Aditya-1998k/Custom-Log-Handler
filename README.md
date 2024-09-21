# Custom-Log-Handler
Logging in Python with custom handler:
```
DB Log Handler : Logging into database
Async Log Handler : Logging asynchronously to database
Console log Handler : Logging onto the console
File Log Handler : Logging into the file
Memory Log Handler : Logging into the Memory
```

### Project Structure
```
custom_log_handler_app/
├── app.py                # Main application
├── handlers/
│   ├── db_handler.py      # DB Log Handler (synchronous logging to the database)
│   ├── async_handler.py   # Async Log Handler (asynchronous logging to the database)
│   ├── console_handler.py # Console Log Handler (logging to console)
│   ├── file_handler.py    # File Log Handler (logging to a file)
│   └── memory_handler.py  # Memory Log Handler (logging to in-memory buffer)
├── logs/                 # Directory for log files
│   └── app.log           # Log file for File Log Handler
├── memory_log_buffer.py   # In-memory log buffer
├── database_setup.sql     # SQL for setting up logs table
├── docker-compose.yml       # Docker Compose configuration
├── Dockerfile               # Dockerfile for the Python app
├── requirements.txt         # Python dependencies
└── celery_worker.py         # Celery worker for asynchronous logging
```
