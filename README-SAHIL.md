# Start Project

```bash
# requirements
python --version
# OUTPUT: Python 3.11.3
pip --version
# OUTPUT: pip 23.2.1 from /usr/lib/python3.11/site-packages/pip (python 3.11)


# start project
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Studying Project

**Files:**
- network/admin.py > network/models.py
- network/auth.py
- network/urls.py (has routes) > network/views.py *(TODO: what are entities in view.py file?)*
- FRONTEND - frontend/src/components/App.js
- FRONTEND - frontend/src/components/Profile.js (Route: `/profile/:username/`)
- FRONTEND - frontend/src/helpers/api.js (All http requests using fetch api)

# TODO:

Add postgres db url to `.env` file to actually be able to start the project because the new error is related to that when you try to run the project by following the guide in official readme.