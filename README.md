# insights 

**in·sights**  */ˈinˌsights/*

*Noun:*  
Pretty standard python app to read information from [google analytics](https://www.google.co.uk/analytics/).
	
*Synonyms:*   	
acumen, vision, wisdom, perception, understanding, observation

![insights](/img/app.jpg "insights")

## Description
Very simple app written in python to get insights using google analytics.

At the time of writing this is just a version of their [example](https://developers.google.com/analytics/devguides/reporting/core/v3/quickstart/service-py) with a few minor amendments. I am sure this will change given time.

## Development Info

You need to have [virtualenv](https://pypi.python.org/pypi/virtualenv) installed. 

```
git clone https://github.com/swmcc/insights.git 
cd insights 
virtualenv venv --distribute
. ./venv/bin/activate
pip install -r requirements.txt
export service_account_email=<whatever>
export key_file_location=<wherever>
python app.rb
```

