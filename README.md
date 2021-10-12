# my-shift

* Part of the source code is modified from [Quickstarts overview](https://github.com/gsuitedevs/python-samples/blob/master/calendar/quickstart/quickstart.py)

## Instructions:

* [Create a project](https://developers.google.com/workspace/guides/create-project)


* [Create OAuth credentials](https://developers.google.com/workspace/guides/create-credentials)


* Get import and export calendar ID in 

```
Calendar Settings -> Integrate calendar -> Calendar ID
```

* Create a `.env` and set up as following
```
IMPORT_CALENDAR_ID=
EXPORT_CALENDAR_ID=
TIMEZONE = 'Asia/Tokyo'
CLEAR_OLD_EXPORT = False
ADD_NEW_EXPORT = False
MONTH_OFFSET = 0
QUERY_NAME = 張
```

* Run with docker-compose
```
docker-compose up --build --force-recreate -d
```