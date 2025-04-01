Future backend structure?

```
schuffle/
│── events/
│   │── migrations/
│   │── google_calendar/
│   │   │── __init__.py
│   │   │── api.py  # Handles API requests to Google Calendar
│   │   │── utils.py  # Helper functions
│   │── models.py
│   │── views.py
│   │── urls.py
│── tasks/
│   │── migrations/
│   │── notion/
│   │   │── __init__.py
│   │   │── api.py  # Handles API requests to Notion
│   │   │── utils.py
│   │── models.py
│   │── views.py
│   │── urls.py
```
