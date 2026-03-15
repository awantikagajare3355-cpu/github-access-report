# GitHub Access Report Service

## Overview
This project connects to the GitHub API and generates a report showing which users have access to which repositories in a GitHub organization.

## Technologies Used
- Java
- Spring Boot
- GitHub REST API

## How to Run the Project
1. Clone the repository
2. Open the project in IntelliJ IDEA
3. Run GithubReportApplication
4. Server starts on port 8080

## API Endpoint
GET /access-report

Example:
http://localhost:8080/access-report

## Authentication
The application uses a GitHub Personal Access Token configured in application.properties.

## Output
Returns JSON data showing repositories and user access information.

## Assumptions
- GitHub token has repo and read:org permissions
- Organization name is configured in the application
