
## Prerequisites

To run the tests, you need to have python  +playwright + pytest-playwright + pytest installed on your machine.

4. **Install dependencies**:
    - You can install all the required packages by running the following command:
      ```bash
      pip install -r requirements.txt
      ```

    This will install Playwright, pytest, and other dependencies required for the project.

5. **Install Playwright Browsers**:
    Playwright requires the browser binaries to run the tests. You can install them by running:
    ```bash
    python -m playwright install
    ```

NOTE : befire running the test you need to give your own email&password for the "https://airportgap.com/docs" in order to generate the token
the credentials section is placed under the helper/airportgap_config file
---->
 CREDENTIALS = {
    "email": "XXX",
    "password":"XXX"
}