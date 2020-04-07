## Install
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
deactivate

# Schedule
(crontab -l 2>/dev/null; printf "5 15 * * * /code/SCOVID-19/run.sh") | uniq - | crontab -
```

## Notes
On April 2nd the death counting process changed.  
https://www.gov.scot/news/new-process-for-reporting-covid-19-deaths/
