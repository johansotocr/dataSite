# Datasite Demo repository

This project is using cypress to automate some functional test cases.

### Basic requirements:
 - nodeJS installed
 - npm installed

### Setup:
- 1. Go to the folder where you want to clone the repo

- 2. Clone the github repo by

```bash
$git clone https://github.com/johansotocr/dataSite.git
```

- 3. Locally, enter to the downloaded folder and run
```bash
$npm install
```

### Running:
- 1. Open cypress by
```bash
$npx cypress open
```

- 2. You can also run cypress headless by
```bash
$npx cypress run --spec "cypress/e2e/"
```
<img width="846" alt="image" src="https://github.com/johansotocr/dataSite/assets/15791382/6fd73c60-111d-4ec8-8c36-4de3787d8980">

- 3. Adding Allure reporting tool to the framework which can be run by
```bash
$npm run openReport"
```
![Screenshot 2024-04-09 at 9 05 02 PM](https://github.com/johansotocr/DatasiteDemo/assets/15791382/da10dec8-a664-497d-aeea-c7fc7f7bec81)
