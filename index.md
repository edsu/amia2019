---
pagetitle: Airtable API
revealjs-url: lib/reveal
theme: generic
transition: slide
---

#

<img src="images/airtable.png">

## Airtable API

# 

::: incremental
1. *What* are APIs?
2. *Why* use the Airtable API?
3. *How* do you use the Airtable API?
:::

#

<img width="80%" src="images/apis.png">

#

<a href="https://ifttt.com/airtable"><img src="images/ifttt.png"></a>

# 

## Web APIs usually consist of:

::: incremental
1. Authentication Keys
2. URLs for Data
3. Data as JSON
4. Documentation
:::

# 

## Authentication Key

keyW9dr3GZI99Q7t93kodp4UD

#

## URLs for Data

https://api.airtable.com/v0/app0oW/Folder-Level-Metadata

#

## Data as JSON

```json
{
  "records": [
    {
      "id": "rec00nRarqo0SknCy",
      "fields": {
        "Box": "079",
        "Folder": "38",
        "Series": "Subject File",
        "Title": "Stations, Massachusetts-Texas",
        "Digitize?": "Yes",
        "ID": "naeb-b079-f38",
        "IA URL": "https://archive.org/details/naeb-b079-f38"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    },
    {
      "id": "rec01HEMcIX1np3vU",
      "fields": {
        "Box": "0010",
        "Folder": "08",
        "Series": "Central Correspondence Files",
        "Title": "1961-1962 July\n",
        "Digitize?": "No",
        "ID": "naeb-b0010-f08",
        "IA URL": "https://archive.org/details/naeb-b0010-f08"
      },
      "createdTime": "2018-06-15T19:48:34.000Z"
    },
    {
      "id": "rec09DXMqiVQNd1Uw",
      "fields": {
        "Box": "048",
        "Folder": "05",
        "Series": "Subject File",
        "Title": "Educational Media Council, 1962-1964 May",
        "Digitize?": "Maybe/Investigate",
        "ID": "naeb-b048-f05",
        "IA URL": "https://archive.org/details/naeb-b048-f05"
      },
      "createdTime": "2018-06-15T21:30:19.000Z"
    },
    {
      "id": "rec0CtvIlNxxfLqFQ",
      "fields": {
        "Box": "011",
        "Folder": "09",
        "Series": "Central Correspondence Files",
        "Title": "1963-1966 August",
        "Digitize?": "No",
        "ID": "naeb-b011-f09",
        "IA URL": "https://archive.org/details/naeb-b011-f09"
      },
      "createdTime": "2018-06-15T19:48:34.000Z"
    },
    {
      "id": "rec0K9AJjdozWY9Ck",
      "fields": {
        "Box": "086",
        "Folder": "18",
        "Series": "Subject File",
        "Title": "Universities and Colleges, State University of Iowa",
        "Digitize?": "Yes",
        "ID": "naeb-b086-f18",
        "IA URL": "https://archive.org/details/naeb-b086-f18"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    },
    {
      "id": "rec0KQ0swpBIosgNB",
      "fields": {
        "Box": "068",
        "Folder": "09",
        "Series": "Subject File",
        "Title": "Moley, Raymond, 1962",
        "Digitize?": "Yes",
        "ID": "naeb-b068-f09",
        "IA URL": "https://archive.org/details/naeb-b068-f09"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    },
    {
      "id": "rec0QmAXLHzpiV4gf",
      "fields": {
        "Box": "079",
        "Folder": "18",
        "Series": "Subject File",
        "Title": "Stations, Massachusetts-Texas",
        "Digitize?": "Yes",
        "ID": "naeb-b079-f18",
        "IA URL": "https://archive.org/details/naeb-b079-f18"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    },
    {
      "id": "rec0RmfYnXBMdWXG3",
      "fields": {
        "Box": "034",
        "Folder": "02",
        "Series": "Subject File",
        "Title": "Committees Publications, 1954-1964",
        "Digitize?": "Yes",
        "Digitization/Preservation Progress Tracking by Folder": [
          "recXEnWuTRixqCce7"
        ],
        "Creator(s)": [
          "recSChDQYCuTy8ZXR"
        ],
        "Subject(s)": [
          "recrs9Al9x1FBmn03"
        ],
        "Date": "1954-1964",
        "Coverage (Temporal)": "1954-1964",
        "Contributor(s)": [
          "rec8eXK6gLLxNKEta",
          "recwmVvt8PlJVgL8z",
          "recG04T9QQXbQ9KFg",
          "recOJPOuM5orwraF2",
          "recanua1xfygubK7s",
          "recLdSCFIUnDOIcrJ",
          "recSNfXpM2NqxHqMF",
          "rectzEXGE4qdmtZRc",
          "rec0KjRkVZ9uyNrSq",
          "rechQQSbnwkca8DX5",
          "rechhUTAZhYWKeNX4",
          "rec59SbO6gYCRTqp9",
          "recO38VrxHAlnTaDd",
          "reczxfJOMLYkObv6I",
          "recu151CWz75vMNWO",
          "recnh6c7R8BVKPBV7",
          "recmNoTRyGtYk84jH",
          "recGmrZkdQEhohhUP",
          "recf7ufzBqYXV80Sg",
          "recNYeO4XYKZkRuwN",
          "recu2XwbaGL8NTxYh",
          "rechL8X6FvFSSaMlO",
          "recuIExPBffh83q4M",
          "recaSOSqrCNP5tWdV",
          "recKzA21GbS5ZPS8r",
          "rec6tQToTrODOrHBb",
          "recIxjwh94qWYbLNe",
          "recNCtjeaMbofDEa5",
          "recX8YtS6Bdije7Ew",
          "recQUsB0e5yJNgC5M",
          "rec3LKCanj5N1AWYW",
          "recfCmQKGVbSeyPW5",
          "recMKlquyQD2Q2VN8",
          "rec1Mnke7Kb4s2PgN",
          "recD7VaBDdKVLkJzm",
          "recRo13SEy1LZWGPG",
          "reczA5DAD9WwvI0pt",
          "recyfsbiME6qXCwL2",
          "rec0aLcobB0XT1Zk0",
          "recdwfrvWa1mOiNEi",
          "recj01VWBHl9zPcLW",
          "recM6HYIxDNAsHVZG",
          "rec94CCQnn3iMdwpx",
          "reckeodh7RnHmXl11",
          "recdK0mDjTXThJzdD",
          "recqokegPqkno7bHj",
          "recat4WGd7XiV4LEl",
          "recvqKvclTsog4SYB",
          "rectgv2RnYW9zlH0i",
          "rechGtvMml9RaFmrv",
          "recOx8nuMSCoTGLTz",
          "recTeqzh2UvWnrDzy"
        ],
        "Publisher": [
          "recurjyARV1ThAXLB"
        ],
        "Rights": "Wisconsin Historical Society",
        "Collection": "National Association of Educational Broadcasters Records, 1925-1977 (bulk 1950-1970)",
        "Type(s)": [
          "Text",
          "Correspondence",
          "Meeting minutes and reports",
          "Reports"
        ],
        "Format": "image/tiff",
        "Description": "1954 to 1964 correspondence regarding the NAEB publications committee, with reports and questionnaires about the Newsletter and Journal. Includes discussion of publication goals and changes, committee management, and article submissions.",
        "Priority": "2",
        "ID": "naeb-b034-f02",
        "Progress": [
          "Completed"
        ],
        "IA URL": "https://archive.org/details/naeb-b034-f02"
      },
      "createdTime": "2018-06-15T21:30:19.000Z"
    },
    {
      "id": "rec0T7eCot2aFyZ7h",
      "fields": {
        "Box": "090",
        "Folder": "04",
        "Series": "National Educational Radio Files",
        "Title": "Daily Correspondence File, 1965 November-1968 August",
        "Digitize?": "No",
        "ID": "naeb-b090-f04",
        "IA URL": "https://archive.org/details/naeb-b090-f04"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    },
    {
      "id": "rec0cecgjGpMAwHWP",
      "fields": {
        "Box": "079",
        "Folder": "21",
        "Series": "Subject File",
        "Title": "Stations, Massachusetts-Texas",
        "Digitize?": "Yes",
        "ID": "naeb-b079-f21",
        "IA URL": "https://archive.org/details/naeb-b079-f21"
      },
      "createdTime": "2018-06-19T02:02:41.000Z"
    }
  ],
  "offset": "itr2O4gbQQRDdZMEA/rec5qXtOD9fhCKX0a"
}
```

# 

<img style="border: thin inset #ccc; height: 300px;" src="images/airwaves.jpg">

#

<img width="60%" src="images/diagram.png">
