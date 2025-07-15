# JMeter-Project

This repository contains a test plan and test results for HTTP and FTP requests using Apache JMeter.

## Repository Contents

- **Test Plan.jmx**  
  The main JMeter test plan including:
    - HTTP request
    - FTP GET and PUT requests
    - View Results Tree for analysis of all test executions

- **Results.csv**  
  A CSV file with test results, including details for each executed request (success/failure, execution time, etc.).

- **Results11.csv**  
  An alternative or additional CSV file with test results (may include results for a different set of tests or parameters).

## How to Use This Project

1. **Install Apache JMeter**  
   Download and install [Apache JMeter](https://jmeter.apache.org/).

2. **Clone the repository**  
   ```sh
   git clone https://github.com/VladanSimic/JMeter-Project.git
   ```

3. **Open the test plan**  
   Start JMeter and open the `Test Plan.jmx` file.

4. **Configure parameters as needed**  
   Edit IP addresses, ports, usernames, and passwords in the test plan according to your environment.

5. **Run the tests**  
   Click Start in JMeter and monitor results in the View Results Tree component.

6. **Analyze the results**  
   Exported results are available in the CSV and DOCX files (`Results.csv`, `Results11.csv`, `Results.docx`) for further analysis.

## Notes

- The test plan is customizable and can be extended by adding new HTTP/FTP requests or other JMeter functionalities.
- Exported results are useful for further analysis of the performance and stability of the tested services.
- When working with FTP requests, always verify the validity of access credentials, server availability, and file permissions.

## Author

Vladan Simic  
GitHub: [VladanSimic](https://github.com/VladanSimic)
