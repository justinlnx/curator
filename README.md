# curator

Backend services to scrap through job postings to locate key words such as programming languages, development platform or specific development skills.

## Job search limitation

_Alpha version_
* location limited to **Vancouver**
* companies limited to **Microsoft**
* job category limited to **Software Engineering** excluding management roles

## Education

Look for strings contains keyword **Bachelor's**, **Master's**, **Ph.D.**, should consider secondary keywords such as program, ie "Computer Science", "Computer Engineering", or "Mathematics"

sample strings:

1. Bachelor's or Master's degree in Computer Science or equivalent industry experience
2. A minimum of a Bachelor’s degree in Computer Science, Computer Engineering, Information Security, or a related field; or equivalent alternative education, skills, and/or practical experience
3. Ph.D. in Computer Science, Mathematics, Physics, Electrical Engineering, or equivalent work experience

## Professional Work experience

Look for strings that contain number of years of work experience required to apply

sample strings:

1. At least 6+ years of a proven track record for building and shipping production software
2. 2+ years of experience working on a large-scale cloud service as a software engineer, site reliability engineer, or security engineer
3. Minimum of 1 years of experience shipping machine learnt software solutions.

## Programming Language

Looking for the specific programming langauges that candidates are familar with

sample strings:

1. Experience with C#\C++\Java or equivalent is required
2. 2+ years of relevant software development experience and proficiency in an object-oriented coding language such as C#, Java, Python, or C++ 
3. Familiarity with scripting languages such as PowerShell or bash
4. Strong coding skills in C/C++ in a production environment. Comfortable with Python or other scripting for rapid prototyping.

common programming langauges to include:
[C, C++, C#, Golang, Java, JavaScript, Object-C, PHP, Python, R, Ruby, Swift, TypeScript]

## Development Environment

Looking for specific development envirnment

Category:

* Web Development: [Angular, ASP.NET, Django, Ember, Express, HTML/CSS, jQuery, Node.js, Rails, React, Redux, Vue, Webpack, Grunt]
* Mobile App Development: [Android, iOS, Ionic, Kotlin, React Native, Swift, Xcode]
* Data Science: [Artificial Intelligence, Machine Learning, Tensorflow, Scikit-learn, Pytorch]
* Cloud Development: [AWS, Azure]
* Scripting language: [PowerShell, Bash]
* Database: [Heroku, MangoDB, MySQL, Postgres, SQL, Firebase, Cosmos]
* Testing: [Selenium WebDriver, Jest, Jasmine, Cypress, Puppeteer]
* Networking protocols: [HTTPS, TCP/IP]
* Operating System: [Linux/Unix, Windows, macOS]

## User workflow

* enter location to search for
* select interested companies
* enter personal information
  - education background, degree + area of study
  - work exp, [<1 year/newgrad, 1-3 year/jr, 3-5 year/intermediate, 5-7 year/senior, 7+ year/senior]
* select programming languages 
* select development environment
  - choose (multi-select) [web, mobile, db, cloud, AI/ML, test, ...]
  - based on selected enviornment, select framework, tools, libraries that candidates are familiar with
* click search
* return list of job postings sorted by relevance (support different sort, soryBy company, date posted, relevance)

