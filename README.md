# Krazy Ideas Design and Architecture
[![License](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0.html)

Krazy Ideas is an open source solution to a problem plaguing virtually all enterprises... how to ensure a company creates and supports best innovative ideas. There have been many attempts at creating internal hackathons, 20 percent work-on-your-own-project type of efforts and various types of mentorship-driven initiatives.

Krazy Ideas is not created to displace these efforts but to compliment them. It is designed to give a voice to silent majority of a companies' employees in expressing their admiration for ideas one of their own will bring forth.

## Architecture
![KrazyIdeas Architecture](https://github.com/krazyideas/design/raw/master/media/Krazy%20Ideas%20Architecture.png "Krazy Ideas Architecture")

### Components
* DB: Currently H2 in memory is being used
* Backend: Spring Data Rest driven microservice [Backend Github Repo](https://github.com/krazyideas/backend))
* Frontend: NodeJS driven microservice [Frontend Github Repo](https://github.com/krazyideas/frontend)
* Client: AngularJS driven browser App. Currently embedded and served from Frontend.

## Installation
Recommended installation is via Docker Compose which allows all components to be correctly deployed for development, testing and (eventually) for production use. Alternative mechanisms we will be leaving for community efforts.

## Testing
Unit and Integration tests is located on each microservice and client application. Functional and performance testing is located on [Test Github Repo](https://github.com/krazyideas/test)
