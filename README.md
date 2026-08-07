# Newman API Test Automation

## Project Summary
This project automates API testing using Postman collections with Newman. It runs the collection from the Postman JSON file and generates a clean HTML test report for easy review.

## Technologies
- Node.js
- npm
- Newman
- Postman Collection
- htmlextra reporter

## Prerequisites
Make sure you have the following installed on your machine:
- Node.js (recommended: v16 or above)
- npm

## Clone the Project
```bash
git clone https://github.com/adnanasif12/dmoney_newman.git
cd NewMan
```

## Install Dependencies
```bash
npm install
```

## Run the Project
To execute the Postman collection and generate the HTML report, run:

```bash
npm test
```

You can also run it directly with:

```bash
node report.js
```

## Project Structure
```text
NewMan/
├── collection/
│   └── dmoney.postman_collection.json
├── Reports/
│   └── report.html
├── package.json
├── report.js
└── README.md
```

## Report Output
After the run completes, the HTML report will be generated at:

```text
Reports/report.html
```
