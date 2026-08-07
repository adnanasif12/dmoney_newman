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
## Report
<img width="843" height="839" alt="image" src="https://github.com/user-attachments/assets/07e72e45-393e-4fc9-8bc0-8093a0c5fde2" />

<img width="865" height="512" alt="image" src="https://github.com/user-attachments/assets/6890cdf5-079a-4b36-860c-850f47992964" />

<img width="912" height="275" alt="image" src="https://github.com/user-attachments/assets/2b022d2c-192d-4f73-acd3-da005576d597" />
<img width="950" height="261" alt="image" src="https://github.com/user-attachments/assets/ee1ec672-8acd-4b69-8b19-28e49b8ea599" />



