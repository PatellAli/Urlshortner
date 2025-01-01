# Urlshortner


A simple URL shortener built with Node.js, Express, MongoDB, and ShortID. This application allows users to shorten URLs, track how many times each URL has been accessed, and store the data in a MongoDB database.

## Features
- Generate a short URL for a given long URL.
- Redirect short URLs to their original URLs.
- Track and store how many times each short URL has been used.
- API endpoints for interaction via Postman or browser.

---

## Technologies Used
- **Node.js**: Backend runtime environment.
- **Express**: Web application framework for building APIs.
- **MongoDB**: NoSQL database to store URL mappings and usage statistics.
- **ShortID**: Library to generate unique short identifiers.
- **Nodemon**: Utility to monitor changes during development.

---
## Screenshots

### Original Url 
![Original Url](/screenshots/originalurl.png)

### Url Analytics
![url analytics](/screenshots/urlAnalytics.png)

### Using new url
![Using new url](/screenshots/usingUrl.png)

### Database
![Datbase](/screenshots/database.png)
---

## Installation and Setup

### Prerequisites
- Node.js installed on your system.
- MongoDB installed locally or access to a MongoDB Atlas cluster.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
