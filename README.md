# <h1 align = "center"> Java E-Mail Integration </h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-4.0-brightgreen.svg" />
</a>

</a>
    <img alt = "GPL v3" src="https://img.shields.io/badge/License-GPLv3-blue.svg" />
    </a>
</p>


---

<p align="left">

Java E-mail Integration (Sender) is a simple command-line tool that allows you to send emails to multiple recipients using JavaMail. It offers a convenient way to send emails programmatically with custom configurations.

## Prerequisites

Before using this tool, ensure that you have the following prerequisites installed on your system:

- Java Development Kit (JDK)
- Apache Maven (for building the project)

## Usage

1. **Clone the Repository:**

   Clone this repository to your local machine:

   ```shell
   git clone <repository-url>
   ```

2. **Build the Project:**

   Use Maven to build the project:

   ```shell
   mvn clean install
   ```

3. **Run the Program:**

   Execute the program by providing your email account password as an argument:

   ```shell
   java -jar target/weekly-test-email-sender.jar <your-email-password>
   ```

   Replace `<your-email-password>` with the password of your email account. This password is required for authentication and sending emails.

4. **Send Emails:**

   Follow the on-screen prompts to send emails:
   
   - Enter the number of recipients.
   - Enter the email addresses of the recipients one by one.
   - The program will send the email to the specified recipients.

## Project Structure

The project is structured as follows:

- `src/main/java/org/geekster/weeklyTest/` - Contains the Java source code.
  - `Main.java` - Main entry point of the program.
  - `customMailAuthenticate.java` - Custom authentication for sending emails.
  - `mailHandler.java` - Handles the sending of emails.
- `src/main/resources/mailMetaData.properties` - Configuration properties for email sending.
- `pom.xml` - Maven project configuration file.
- `target/` - Directory containing the compiled JAR file.

## Configuration

Customize the email sending properties in the `mailMetaData.properties` file:

- `host` - The email server host.
- `port` - The email server port.
- `sslProperty` - Enable or disable SSL (true or false).
- `authPerm` - Enable or disable authentication (true or false).
- `senderMail` - Your sender email address.

## Contributing

We welcome contributions! To contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

<!-- License -->
## License
This project is licensed under the [GNU General Public License v3.0](LICENSE).

<!-- Acknowledgments -->
## Acknowledgments
Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact
For questions or feedback, please contact [Amit Ashok Swain](mailto:business.amitswain@gmail.com).

