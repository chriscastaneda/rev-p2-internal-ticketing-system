# Ask IT
Mock application of an internal-ticketing-system built to support a community of company employees and the IT personnel that can resolve their issues. Composed of posts and comments, this website allows employees to create inquiries in the form of a ticket that can be resolved by any of the aforementioned personnel

**Subject:**
- login, signup
- client data storage
- Peer-to-peer interaction
- Agile scrum practices

demo: https://s3-internal-ticketing-system.s3.us-west-1.amazonaws.com/index.html
[![Demo](https://github.com/chriscastaneda/rev-p2-internal-ticketing-system/blob/master/assests/img/demo_snip.PNG)](https://drive.google.com/file/d/10OXxnCC41nw44Z3nhHYRkfyc8cxjXH23/view){:target="_blank"}

## Features
- Documentation (all methods have basic documentation)
- Server Unit testing (> 80% coverage)
- Client Unit testing (> 30% coverage)
- SQL Data Persistance (3 tables; all 3NF)
- Filter by ticket category
- Admin/Employee dashboard (ID'd on login)

### Tech Stack:
- [x] PostgreSQL
- [x] Node-Postgre (AWS-RDS)
- [x] AWS-EC2
- [x] Java: Spring Boot
- [x] Spring Data
- [x] Spring Security + JWT
- [x] Hibernate
- [x] Bcrypt
- [x] JUnit
- [x] TypeScript
- [x] CSS Bootstrap
- [x] React
- [x] Jest/Enzyme
- [x] Git SCM (on GitHub)

## Init Instructions

### Server - SpringBoot
- Update Maven Project
- Run as springboot app: _Application.java_

### Client - React JS
- install node 6.14.4 or higher
- _client/_ npm install
- npm start

## User Login
<div id="anchor">

#### &#x128280; Default accounts
</div> 

```
Employee:
-username: employee
-password: 1234

Administrator: 
-username: admin
-password: 5678
```
