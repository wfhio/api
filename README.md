WFH.io JSON API
===============

Get jobs
--------

* `GET /api/jobs.json`
* `GET /api/jobs.json?page=2`
* `GET /api/jobs.json?&category_id=`
* `GET /api/jobs.json?&source_id=1`

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
        "description": "#### Job Description\r\n\r\n__Who are we?__\r\n\r\nWe\u2019re Hostmaker \u2013 nice to meet you! Our attentive, guest-ready services create unforgettable experiences for those welcomed into the homes of our hosts. Guest-ready means exactly what it says on the tin: the little touches that do big things, from linen rentals and housekeeping to meeting and greeting excited explorers when they arrive. And we need a master-crafter of code to help us get our ducks in a line </badpun>.\r\n\r\nWe\u2019re well on our way to world domination (we\u2019re the leaders of our field in Europe). And we\u2019re looking for a nifty, knowledgeable coding extraordinaire to help us develop the platforms and tools needed to conquer the rest of the world. We\u2019ve just raised $2 million in funding, we operate in 3 cities (and counting), and we\u2019re growing our people too \u2014fast. As one of the first members of our tech team, you\u2019ll work closely with stakeholders across the company. You\u2019ll solve problems that have never been solved before, and you\u2019ll write the book on how we automate our supply chain, dynamically price listings, and scale the business while retaining a 5* customer experience. Don\u2019t worry, your buckets of talent will ensure it\u2019s a bestseller.\r\n\r\n__What can you expect?__\r\n\r\n* Trust, always. While we\u2019ll always be there to support you, we expect a good level of autonomy (Google is your friend). In return we\u2019ll give you space to think freely without us breathing down your neck\r\n* To work remotely, if you want to \u2013 we believe productivity isn\u2019t dictated by time spent chained to a desk\r\n* Flexibility! Though our technology stack is built on Rails, Node.js, and Ember.js, we\u2019re more concerned with your ability to solve problems, self-motivate and learn new skills than what specific languages and frameworks you know\r\n* To focus on the bigger picture, not just the dots (or, 1s and 0s). While you should be detail-oriented, you should also have a keen understanding of customer needs and strive to fulfil them at every turn\r\n* To become part of a close-knit, hard-working team \u2013 you\u2019ll need to be able to collaborate with the wider Hostmaker family as well as you can chat code with other devs\r\n\r\n__Our finishing touches__\r\n\r\nCulture is important to us. We love what we do, and make sure everyone in the team feels valued, respected and important. This makes people take pride in their work, and that\u2019s when the best work is produced. A few of the many perks of joining the Hostmaker team:\r\n\r\n* Competitive startup salary (no, we don\u2019t pay a big fat corporate wage, but what did you expect?), with an opportunity for equity options based on experience\r\n* A fast-growing seed-stage company full of bright, engaged folks who\u2019ll keep you on your toes everyday\r\n* A supportive investor group that believes in our vision\r\n* No mega-corp fluff: we focus on results, not face-time\r\n* Discounted Airbnb travel\r\n* Discounts at Hostmaker homes (we\u2019re now in London, Rome and Barcelona!)\r\n* Local travel and phone bills are included\r\n\r\n#### Skills & Requirements\r\n\r\n__Who are you?__\r\n\r\n* 2+ years\u2019 on-the-job experience, and be prepared to show us \u2013 we\u2019re nosey\r\n* If it was earned in a fast-paced startup or in supply chain, all the better\r\n* You\u2019ve got a Bachelor\u2019s degree in computer science, computer engineering, mathematics (or the equivalent in work experience) and you\u2019re not afraid to use it\r\n* You know Ruby on Rails, Node.js or Ember.js like the back of your hand\r\n* Your friends call you obsessive but you prefer the term \u2018detail orientated\u2019. However we\u2019re looking for clean, scalable, unit-tested code, so you\u2019re right up our street\r\n* You\u2019ve got a firm grasp on HTML, CSS and jQuery\r\n* You\u2019ve had your fair share of run-ins with SQL databases and have come out victorious (And you\u2019ll get bonus points for familiarity with NoSQL technologies like MongoDB)\r\n* You\u2019re experienced in AWS, especially EC2, RDS, and S3 (and other acronyms we may not have even heard of yet)\r\n* DevOps experience is highly desirable, especially if it involved AWS OpsWorks or Chef\r\n* Single page application design patterns are no match for your code wizardry\r\n* And neither is designing and communicating with RESTful interfaces\r\n* You\u2019ve worked with distributed version control systems such as Git or Mercurial, and loved them\r\n\r\n#### About Hostmaker\r\n\r\nHostmaker is a full-service hospitality provider for hosts on Airbnb. We provide hotel-style cleaning services, linen rental and welcome packs for arriving guests as well as profile management services for hosts. We take care of listing, pricing and guest communication. We do the work, you gather the glorious reviews. \r\n\r\nWith Hostmaker, you are in good hands. We are a team of hospitality professionals with over 30 years of experience in strategy, hotel design and guest services. We are ardent Airbnb fans and look to Airbnb when searching for places to stay whenever we travel. We also host on Airbnb, so we understand the challenges facing hosts and travellers.",
        "id": 2453,
        "source": {
            "id": 4,
            "name": "Stack Overflow Careers",
            "url": "http://careers.stackoverflow.com/"
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
        "description": "We are looking for Scala developers to help us build and maintain our large-scale data processing platform. At Findify, we make extensive use of data-collection, processing and machine learning algorithms to help our merchants provide better search to their customers. You would be responsible for building high-performance data flows and Scala applications to help us achieve this goal.\r\n\r\n__Our engineering environment__\r\n\r\nTech stack:\r\n\r\nWe always strive to use the most suitable tool for the job, so our stack is constantly evolving. Currently, our backend is written mostly in Scala and Node.js. We use Scala for data processing and to power our machine learning algorithms. Node is used as a web framework to facilitate the interaction with our customers via various APIs. We make extensive use of AWS, and use any component we find suitable within our architecture, so we can focus on building our proprietary tech.\r\n\r\nWe\u2019re not afraid to challenge our choices, we love open source and above all, we\u2019re a product driven company so technology is at the core of everything we do. You can check out our full stack on [StackShare](http://stackshare.io/findify).\r\n\r\nDevelopment culture:\r\n\r\nWe are a small team that moves fast and iterates. We do weekly sprints, code reviews, testing, and once your code is submitted it gets pushed to production through our continuous deployment infrastructure. We put a lot of emphasis on code style, cleanliness and robustness. You will get to work with amazing engineers specializing in machine learning and distributed systems.\r\n\r\nAs an early engineer in a small team, you\u2019ll have the opportunity to make a real impact on the product, company vision and culture. You will get to work with the latest technologies out there, without being bound to any legacy. Have the opportunity to solve real-life problems. We will never limit your creativity, never shut down ideas before testing them with customers and we will never be boring! it\u2019s going to be an exciting ride!\r\n\r\n__Requirements__\r\n\r\nThe most important thing we are looking for in a candidate is proven passion for programming and problem solving: a Github/Stackoverflow account, an interesting project you can share, or a blog you write will go a long way.\r\n\r\nWe are a distributed team, so you can work from anywhere you want, as long as it\u2019s 2 hours +/- from CET. (The timezone is an important requirement for us at this stage)\r\n\r\nIt\u2019s really important to us that you have the ability to adapt to the company\u2019s work processes using the agile-scrum methodology, and using tools such as Trello and Slack. Not only because of our remote working culture, but even more so because of this, you need to be really awesome at communicating, and to be organized and self-driven.\r\n\r\nOh, and you need to want to have fun.\r\n\r\nThe basics:\r\n\r\n- Scala\r\n- Deep understanding of functional programming\r\n- Professional experience with Akka\r\n- Familiarity with Slick or another SQL ORM library\r\n- Familiarity with Linux / Unix\r\n- Git\r\n\r\nBeyond the basics (what would really impress us):\r\n\r\n- Experience in one or several of the following technologies: NoSQL databases, Apache Spark, Kafka\r\n- Professional experience in data-mining or machine learning\r\n- Experience building and running high-performance distributed systems with high-availability on AWS\r\n- Familiarity with data-loading techniques on Amazon Redshift\r\n- Experience using BI tools (Tableau, etc.)\r\n\r\n__Location & remote working__\r\n\r\nWe are a distributed team, so you can work from anywhere you want, as long as it\u2019s 2 hours +/- from CET. (The timezone is an important requirement for us at this stage)",
        "id": 2452,
        "source": {
            "id": 4,
            "name": "Stack Overflow Careers",
            "url": "http://careers.stackoverflow.com/"
        },
        "title": "Scala Developer"
    },
    ...
]
```

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
    },
    ...
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
    },
    ...
]
```

Get companies
-------------

* `GET /api/companies.json`
* `GET /api/companies.json?page=2`

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
