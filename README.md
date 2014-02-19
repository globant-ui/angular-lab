Angular Lab
===========
## Target Audience
This lab targets Web UI developers regardless of their current seniority. However, is expected a basic knowledge on web technologies such as HTML, CSS, and an intermediate knowledge on JavaScript.
This lab is not a tutorial, its goal is not to teach Angular.js but to provide problems to exercise key Angular.js concepts, and best practices.

## Introduction
This lab is structured as a set of exercises leading to the construction of a web application. The lab will be considered completed by the developer once he has finished all the exercises and uploaded them to GitHub. In addition, the application must be deployed in GitHub pages so it can be used online. The evaluation will be done through code reviews using GitHub’s review tools.

Please fork this repository, and send a PR as soon as the lab is finished. Afterwards, the PR will be evaluated by an architect or senior developer. 

## Required Reading
- AngularJS Developer Guide: http://docs.angularjs.org/guide
- Angular’s FAQ: https://github.com/angular/angular.js/wiki/FAQ
- Collection of curated AngularJS-related links: https://github.com/jmcunningham/AngularJS-Learning

## Best Practices
### Angular’s Best Practices
- From Angular's wiki https://github.com/angular/angular.js/wiki/Best-Practices
- Advanced Design Patterns and Best Practices http://trochette.github.io/Angular-Design-Patterns-Best-Practices/#/intro
- AngularJS: The Bad and The Better http://miceplans.net/node/36
- AngularJS Best Practices: I’ve Been Doing It Wrong! Part 1 of 3 http://www.artandlogic.com/blog/2013/05/ive-been-doing-it-wrong-part-1-of-3/
- AngularJS Best Practices: I’ve Been Doing It Wrong! Part 2 of 3 http://www.artandlogic.com/blog/2013/05/angularjs-best-practices-ive-been-doing-it-wrong-part-2-of-3/
- AngularJS Best Practices: I’ve Been Doing It Wrong! Part 3 of 3 http://www.artandlogic.com/blog/2013/05/angularjs-best-practices-ive-been-doing-it-wrong-part-3-of-3/
- Best Practice Recommendations for Angular App Structure (official document) https://docs.google.com/document/d/1XXMvReO8-Awi1EZXAXS4PzDzdNvV6pGcuaF4Q9821Es/pub

### Angular's Anti-patterns
- From Angular's wiki https://github.com/angular/angular.js/wiki/Anti-Patterns
- AngularJS: 6 Common Pitfalls Using Scopes http://thenittygritty.co/angularjs-pitfalls-using-scopes

## Examples
- Official angular boilerplate https://github.com/angular-app/angular-app
- Ng-boilerplate project boilerplate http://joshdmiller.github.io/ng-boilerplate

## Testing
### Running Unit Tests
Use  jasmine and Karma for your unit tests/specs, but you are free to use whatever works for you.
Requires node.js, Karma (sudo npm install -g karma) and a local or remote browser.
Source: https://github.com/angular/angular-seed
### End-to-End Testing
Use protractor framework for end-to-end (E2E) tests. It uses native events and has special features for Angular applications.
Requires a webserver, node.js + ./scripts/web-server.js or your backend server that hosts the angular static files.
Source: https://github.com/angular/protractor

## Exercises
1. Complete Angular's official tutorial: http://docs.angularjs.org/tutorial
2. Create an application that list all the starred repositories a GitHub user has. The application must list all starred repos.
3. The application must authenticate the user.
4. Allow the user to sort her repositories using different statistics (http://developer.github.com/v3/repos/statistics/).
5. Add a search feature, filter results based on the search string.
6. Add graphics to present statistical data per repository.
7. Implement navigation using the angular router (angular-route).
8. Add internationalization support to the application developed in the previous step.
9. Refactor your application so all repository data is rendered using one or more custom directives.
10. Create a logging service. Log all relevant user actions.
11. Implement offline support, so the user can see her repositories even if she doesn't have connectivity.
12. Allow the user to unstar a repository. The repository must fade out from the list.
13. Add Google Analytics support.

_Application must include unit, and E2E tests._
 
