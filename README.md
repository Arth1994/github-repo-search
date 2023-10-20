# github-repo-search
# GitHub Repository Search with Angular

![GitHub](https://img.shields.io/github/license/yourusername/github-repo-search)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/github-repo-search)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/github-repo-search)](https://github.com/yourusername/github-repo-search/issues)

A simple GitHub repository search application built with Angular and Angular Material. This project allows users to search for GitHub repositories by name and view details of each repository.

## Features

- GitHub repository search by name.
- Display repository details, including name, owner, and description.
- Link to the GitHub page for each repository.

## Technologies Used

- Angular
- Angular Material
- TypeScript
- HTML/CSS
- GitHub API

## Project Structure

The project is organized into the following components:

- `app.component.ts` and `app.component.html` for the main application layout.
- `repo-search` component for the GitHub repository search interface.
- `github.service.ts` for interacting with the GitHub API.

## Getting Started

1. Clone the repository: `git clone https://github.com/yourusername/github-repo-search.git`
2. Navigate to the project folder: `cd github-repo-search`
3. Install dependencies: `npm install`
4. Run the development server: `ng serve`
5. Open a web browser and go to `http://localhost:4200/`

## Usage

1. Enter a repository name in the search bar.
2. Click the "Search" button to find repositories matching the query.
3. View the details of each repository, including the owner and description.
4. Click the "View on GitHub" button to open the repository's GitHub page.
