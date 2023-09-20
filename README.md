# React Blog API - JSON Server

## Overview

This JSON Server API serves as the backend for a React blog application. It provides a simple and easy-to-use RESTful API for managing blog posts, comments, and user data. This README file contains instructions for setting up and using the API.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Server](#running-the-server)
  - [API Endpoints](#api-endpoints)
- [Data Structure](#data-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you can use this JSON Server API, ensure that you have the following prerequisites installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) package manager

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/alyconr/jsonServer-Api-Blog.git

2. Navigate to the cloned directory:

    ```bash
    cd jsonServer-Api-Blog.git

3. Install dependencies:

    ```bash
    npm install 
    # Or
    yarn install
    ```
## Usage

### Running the Server

```bash
npm run start
# Or
yarn start
```
By default, the server will run on port 8000

### API Endpoints

```bash
GET /api/blogs
GET /api/blogs/:id
POST /api/blogs
PUT /api/blogs/:id
DELETE /api/blogs/:id
```
### Data Structure

The data structure for the JSON Server API is defined in the db.json file. You can customize the data or add more data types to suit your blog application's needs.

Example db.json structure:

```json
{
  "blogs": [
    {
      "title": "Title 1",
      "body": "Body 1",
      "author": "Author 1",
      "id": 1
    },
    {
      "title": "Title 2",
      "body": "Body 2",
      "author": "Author 2",
      "id": 2
    }
  ]
}
```
## Contributing
If you would like to contribute to this project, please follow the guidelines outlined in the [Contributing](CONTRIBUTING.md) file.

## 📝 License <a name="license"></a>

This project is [MIT](LICENSE.md) licensed.

