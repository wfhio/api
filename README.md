WFH.io JSON API
===============

Get jobs
--------

* `GET /api/v2/jobs.json`
* `GET /api/v2/jobs.json?page=2`
* `GET /api/v2/jobs.json?category_id=1`
* `GET /api/v2/jobs.json?source_id=1`

```json
[
    {
        "category": {
            "id": 1,
            "name": "Software Development"
        },
        "company": {
            "id": 1193,
            "name": "Hostmaker"
        },
        "created_at": "2015-12-17T22:43:40.000Z",
        "id": 2453,
        "source": {
            "id": 4,
            "name": "Stack Overflow Careers"
        },
        "title": "Full-Stack Software Development Engineer"
    },
    {
        "category": {
            "id": 1,
            "name": "Software Development"
        },
        "company": {
            "id": 786,
            "name": "Findify"
        },
        "created_at": "2015-12-17T22:30:29.000Z",
        "id": 2452,
        "source": {
            "id": 4,
            "name": "Stack Overflow Careers"
        },
        "title": "Scala Developer"
    },
    ...
]
```

Get job
-------

* `GET /api/v2/jobs/2453.json`

```json
{
    "application_info": "https://www.wfh.io/jobs/2453",
    "category": {
        "id": 1,
        "name": "Software Development"
    },
    "company": {
        "id": 1193,
        "name": "Hostmaker"
    },
    "created_at": "2015-12-17T22:43:40.000Z",
    "description": "#### Job Description\r\n\r\n__Who are we?__\r\n\r\nWe\u2019re Hostmaker \u2013 nice to meet you! Our attentive, guest-ready services create unforgettable experiences for those welcomed into the homes of our hosts. Guest-ready means exactly what it says on the tin: the little touches that do big things, from linen rentals and housekeeping to meeting and greeting excited explorers when they arrive. And we need a master-crafter of code to help us get our ducks in a line </badpun>.\r\n\r\nWe\u2019re well on our way to world domination (we\u2019re the leaders of our field in Europe). And we\u2019re looking for a nifty, knowledgeable coding extraordinaire to help us develop the platforms and tools needed to conquer the rest of the world. We\u2019ve just raised $2 million in funding, we operate in 3 cities (and counting), and we\u2019re growing our people too \u2014fast. As one of the first members of our tech team, you\u2019ll work closely with stakeholders across the company. You\u2019ll solve problems that have never been solved before, and you\u2019ll write the book on how we automate our supply chain, dynamically price listings, and scale the business while retaining a 5* customer experience. Don\u2019t worry, your buckets of talent will ensure it\u2019s a bestseller.\r\n\r\n__What can you expect?__\r\n\r\n* Trust, always. While we\u2019ll always be there to support you, we expect a good level of autonomy (Google is your friend). In return we\u2019ll give you space to think freely without us breathing down your neck\r\n* To work remotely, if you want to \u2013 we believe productivity isn\u2019t dictated by time spent chained to a desk\r\n* Flexibility! Though our technology stack is built on Rails, Node.js, and Ember.js, we\u2019re more concerned with your ability to solve problems, self-motivate and learn new skills than what specific languages and frameworks you know\r\n* To focus on the bigger picture, not just the dots (or, 1s and 0s). While you should be detail-oriented, you should also have a keen understanding of customer needs and strive to fulfil them at every turn\r\n* To become part of a close-knit, hard-working team \u2013 you\u2019ll need to be able to collaborate with the wider Hostmaker family as well as you can chat code with other devs\r\n\r\n__Our finishing touches__\r\n\r\nCulture is important to us. We love what we do, and make sure everyone in the team feels valued, respected and important. This makes people take pride in their work, and that\u2019s when the best work is produced. A few of the many perks of joining the Hostmaker team:\r\n\r\n* Competitive startup salary (no, we don\u2019t pay a big fat corporate wage, but what did you expect?), with an opportunity for equity options based on experience\r\n* A fast-growing seed-stage company full of bright, engaged folks who\u2019ll keep you on your toes everyday\r\n* A supportive investor group that believes in our vision\r\n* No mega-corp fluff: we focus on results, not face-time\r\n* Discounted Airbnb travel\r\n* Discounts at Hostmaker homes (we\u2019re now in London, Rome and Barcelona!)\r\n* Local travel and phone bills are included\r\n\r\n#### Skills & Requirements\r\n\r\n__Who are you?__\r\n\r\n* 2+ years\u2019 on-the-job experience, and be prepared to show us \u2013 we\u2019re nosey\r\n* If it was earned in a fast-paced startup or in supply chain, all the better\r\n* You\u2019ve got a Bachelor\u2019s degree in computer science, computer engineering, mathematics (or the equivalent in work experience) and you\u2019re not afraid to use it\r\n* You know Ruby on Rails, Node.js or Ember.js like the back of your hand\r\n* Your friends call you obsessive but you prefer the term \u2018detail orientated\u2019. However we\u2019re looking for clean, scalable, unit-tested code, so you\u2019re right up our street\r\n* You\u2019ve got a firm grasp on HTML, CSS and jQuery\r\n* You\u2019ve had your fair share of run-ins with SQL databases and have come out victorious (And you\u2019ll get bonus points for familiarity with NoSQL technologies like MongoDB)\r\n* You\u2019re experienced in AWS, especially EC2, RDS, and S3 (and other acronyms we may not have even heard of yet)\r\n* DevOps experience is highly desirable, especially if it involved AWS OpsWorks or Chef\r\n* Single page application design patterns are no match for your code wizardry\r\n* And neither is designing and communicating with RESTful interfaces\r\n* You\u2019ve worked with distributed version control systems such as Git or Mercurial, and loved them\r\n\r\n#### About Hostmaker\r\n\r\nHostmaker is a full-service hospitality provider for hosts on Airbnb. We provide hotel-style cleaning services, linen rental and welcome packs for arriving guests as well as profile management services for hosts. We take care of listing, pricing and guest communication. We do the work, you gather the glorious reviews. \r\n\r\nWith Hostmaker, you are in good hands. We are a team of hospitality professionals with over 30 years of experience in strategy, hotel design and guest services. We are ardent Airbnb fans and look to Airbnb when searching for places to stay whenever we travel. We also host on Airbnb, so we understand the challenges facing hosts and travellers.",
    "id": 2453,
    "location": "",
    "source": {
        "id": 4,
        "name": "Stack Overflow Careers"
    },
    "title": "Full-Stack Software Development Engineer"
}
```

Get categories
--------------

* `GET /api/v2/categories.json`

```json
[
    {
        "id": 1,
        "name": "Software Development"
    },
    {
        "id": 2,
        "name": "System Administration"
    },
    ...
]
```

Get sources
-----------

* `GET /api/v2/sources.json`


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
    },
    ...
]
```

Get companies
-------------

* `GET /api/v2/companies.json`
* `GET /api/v2/companies.json?page=2`

```json
[
    {
        "id": 1,
        "name": "ISC"
    },
    {
        "id": 2,
        "name": "Surevine"
    },
    ...
]
```

Get company
----------

* `GET /api/v2/companies/1.json`

```json
{
    "id": 1,
    "name": "ISC",
    "showcase_url": null,
    "twitter": "ISCdotORG",
    "url": "http://www.isc.org"
}
```
