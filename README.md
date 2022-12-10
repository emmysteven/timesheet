# Timesheet
<br/>

An Implementation of Clean Architecture with .NET 6
With this Open-Source Codebase, you will get access to the world of Loosely-Coupled and Inverted-Dependency Architecture in .NET 6

## Upcoming Release

### v1.1-release

Read the [Changelog file](https://github.com/emmysteven/timesheet/blob/main/CHANGELOG.md) to see the new changes.

Clone this repository to get the latest unreleased version.


## Releases

v1.0-preview - IS NOT YET OUT<!--[Download the first Preview here](https://github.com/emmysteven/timesheet/releases/tag/v1.0-preview) -->

### v1 Preview.
Follow these steps to get started
1. Clone this Repository and Extract it to a Folder.
2. Change appsettings.mock.json to appsettings.json in WebUI directory
3. Run the following commands on Terminal in the WebUI project's directory.
- dotnet restore
- dotnet ef database update --context DataContext
- dotnet run (OR) Run the Solution using Visual Studio 2022 or JetBrain Rider

Check out my [website](https://www.emmysteven.com) or say [Hi on Twitter!](https://twitter.com/emmysteven_)

## Purpose of this Project

The purpose of this project is to provide an e-timesheet for End-of-Day operations on Oracle Flexcube without having to use a paper timesheet.

This project is well documented along with the steps taken to build this solution from scratch. You can tweak it to suit your taste.
- Demonstrate clean architecture in .NET 6
- This is not a proof of concept
- Implementation that is ready for production
- Integrate the most essential libraries and packages



## Technologies
- .NET 6
- REST Standards
- .NET 6 Libraries



## Features
- [x] Clean Architecture
- [x] CQRS with MediatR Library
- [x] Entity Framework Core - Code First
- [x] Repository Pattern - Generic
- [x] MediatR Pipeline Logging & Validation
- [x] Serilog
- [x] Swagger UI
- [x] Response Wrappers
- [ ] Healthchecks
- [x] Pagination
- [ ] In-Memory Caching
- [ ] Redis Caching
- [x] RDBMS
- [ ] JWT Authentication
- [ ] Role based Authorization
- [x] Custom Exception Handler
- [x] Fluent Validation
- [x] Automapper
- [ ] SMTP / Mailkit / Email Service
- [ ] Complete User Management Module (Register / Generate Token / Forgot Password / Confirmation Mail)
- [ ] User Auditing



## Prerequisites
- JetBrains Rider 2021.3.2 & above | Visual Studio 2022 Community and above
- .NET Core 6.0 SDK and above
- Basic Understanding of Clean Architecture
- I Recommend that you read [Onion Architecture In ASP.NET Core With CQRS – Detailed](https://www.codewithmukesh.com/blog/onion-architecture-in-aspnet-core/) article to understand this project much better. This project is just an Advanced Version of the mentioned article.

## Getting Started

## Changelog
Every changes / additions / deletions will be recorded in the [Changelog file](https://github.com/emmysteven/timesheet/blob/main/CHANGELOG.md).

## Questions? Bugs? Suggestions for Improvement?
Having any issues or troubles getting started? [Get in touch with me](https://www.emmysteven.com/contact) or [Raise a Bug or Feature Request](https://github.com/emmysteven/restaurant/issues/new/choose). Always happy to help.

## Support
If this project helped you learn something new? or helped you at work? Do Consider Supporting. <br/>Give it a star <br/>ETH: <code>0x9F4942911f2406E5897669Db99184d47B3078E99</code>


## Share it!
There are many improvements and fixes along the way from the day I started out. Thanks to the community for the support and suggestions.
Please share this Repository within your developer community, if you think this would make a difference! Thanks.

## About the Author
### Emmy Steven
- Blogs at [emmysteven.com](https://www.emmysteven.com)
- Twitter - [Emmy Steven](https://www.twitter.com/emmysteven_)
- Linkedin - [Emmy Steven](https://www.linkedin.com/in/emmysteven/)

## Licensing
emmysteven/timesheet Project is licensed with the [MIT License](https://github.com/emmysteven/timesheet/blob/main/LICENSE).