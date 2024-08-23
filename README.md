# Web Automation

This project demonstrates how to automate web tasks using Selenium WebDriver with Java.

## Setup

1. **Download and install the Chrome WebDriver** from [ChromeDriver](https://sites.google.com/chromium.org/driver/).
2. **Add Selenium WebDriver dependencies** to your `pom.xml` if using Maven:

    ```xml
    <dependencies>
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.7.2</version>
        </dependency>
    </dependencies>
    ```

3. **Set the path to the WebDriver executable** in the `System.setProperty` method.

## Usage

1. Update the `WebAutomation.java` script with your credentials and the URL of the login page you want to automate.
2. Compile and run the script:

    ```bash
    javac WebAutomation.java
    java WebAutomation
    ```

## License

This project is licensed under the MIT License.
