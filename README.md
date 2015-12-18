WFH.io JSON API
===============

Get jobs
--------

* `GET /api/jobs.json`

Get job
-------

* `GET /api/jobs/1.json`

```json
{
    "application_info": "[https://www.isc.org/wordpress/about/jobs/software-engineer-bind-10/](https://www.isc.org/wordpress/about/jobs/software-engineer-bind-10/)",
    "category": {
        "id": 1,
        "name": "Software Development"
    },
    "company": {
        "id": 1,
        "name": "ISC"
    },
    "created_at": "2013-04-04T22:18:44.000Z",
    "description": "Background\r\n----------\r\n\r\nInternet Systems Consortium (ISC) develops commercial \u00adquality open\u00adsource software for the Internet Community. ISC has a proud history in the development of the Internet, with many of the DNS and DHCP \u00adrelated standards in use today written by current or past employees. We are currently seeking highly qualified and motivated software engineers.\r\n\r\nJob Description\r\n-------------\r\n\r\nWe are looking for a software engineer to help develop ISC BIND 10. This engineer will be a core part of the BIND 10 development team, building the next generation of DNS software. We need a professional programmer, who ideally has experience developing networking software. While the initial need is for the BIND 10 project, ISC software engineers move between projects over time.\r\n\r\nDuties will include:\r\n----------------\r\n\r\n* Design and develop new features for BIND.\r\n* Review code changes.\r\n* Assist release engineering.\r\n* Assist project planning.\r\n* Analyze and respond to bug reports from a variety of sources.\r\n* Promote ISC products and provide a professional and friendly image for ISC\u2019s services such as BIND and DHCP Support and the ISC Forum.\r\n\r\nDevelopment Environment\r\n----------------------\r\n\r\n* BIND 10 development at ISC is based on an Agile Scrum model.\r\n* BIND 10 uses a test driven development (TDD) methodology.\r\n* Working from home or from the Redwood City, California office is allowed. If working from home, a history of successfully completing tasks from a home office is a plus.\r\n* We are an open source shop. We make an effort to select open source development tools when possible. If we must select a closed source tool, we give preference to ones which support open protocols.\r\n\r\nMinimum job requirements:\r\n-----------------------\r\n\r\n* Education: B.E./B.Sc. or equivalent\r\n* Experience: 5 \u2013 10 years\r\n* Specific Skills:\r\n    * Required: C and C++ programming experience. Unix or Windows programming. An understanding of threads, locks, Berkeley socket API.\r\n    * Desirable: Make, Python, Unix Shells. Network Management. System Administration. An understanding of Windows network programming.\r\n* Specialized Knowledge:\r\n    * Required: A solid understanding of IP networking\r\n    * Desirable: In depth knowledge of DNS. Knowledge of DNSSEC. Experience with Agile development methodologies\r\n\r\nWorking Condition\r\n----------------\r\n\r\nFrom home or at 950 Charter Street, Redwood City, California. Expected to travel at least 3 times a year for face\u00adto\u00adface meetings, plus occasional travel for workshops or conferences. Some travel will be international.",
    "id": 3,
    "location": "United States",
    "source": {
        "id": 2,
        "name": "WFH.io",
        "url": "https://www.wfh.io"
    },
    "title": "Software Engineer (BIND 10)"
}
```

Get categories
--------------

* `GET /api/categories.json`

```json
[
    {
        "id": 1,
        "name": "Software Development"
    },
    {
        "id": 2,
        "name": "System Administration"
    }
]
```

Get sources
-----------

* `GET /api/sources.json`


```json
[
    {
        "id": 1,
        "name": "LaraJobs",
        "url": "https://larajobs.com"
    },
    {
        "id": 2,
        "name": "WFH.io",
        "url": "https://www.wfh.io"
    }
]
```

Get companies
-------------

* `GET /api/companies.json`

```json
[
    {
        "id": 1,
        "name": "ISC"
    },
    {
        "id": 2,
        "name": "Surevine"
    }
]
```

Get company
----------

* `GET /api/companies/1.json`

```json
{
    "id": 1,
    "name": "ISC",
    "showcase_url": null,
    "twitter": "ISCdotORG",
    "url": "http://www.isc.org"
}
```
