
# Simple Tasks

SimpleTaskManager is a lightweight task management web application built using Spring Boot. This project incorporates JSON serialization and deserialization to enable efficient communication between the client and server. Users can register, log in, and manage tasks with ease, with data exchanged in JSON format.

### Key Features:
- User Registration and Authentication
- Create, Read, Update, and Delete (CRUD) Operations for Tasks
- Intuitive Web Interface for Task Management
- Secure Password Storage with BCrypt
- JSON Serialization and Deserialization for Efficient Data Transfer

### Technologies Used:
- Spring Boot
- Spring Security
- Thymeleaf (or your preferred template engine)
- Spring Data JPA
- HTML, CSS
- JSON (Jackson library for serialization and deserialization)

### Getting Started: 
1. Clone the repository: `git clone https://github.com/yourusername/SimpleTaskManager.git`
2. Navigate to the project directory: `cd SimpleTaskManager`
3. Open the project in your preferred IDE (e.g., IntelliJ, Eclipse).
4. Configure the application.properties file with your database settings.
5. Run the application.

Feel free to fork, contribute, and customize the project to suit your needs!

### Getting Started Guide:

1. **Clone the Repository:**
   - Open a terminal and run the following command to clone the repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/SimpleTaskManager.git
     ```

2. **Navigate to Project Directory:**
   - Change into the project directory using the following command:
     ```bash
     cd SimpleTaskManager
     ```

3. **Open in IDE:**
   - Open the project in your preferred Integrated Development Environment (IDE), such as IntelliJ IDEA or Eclipse.

4. **Configure Database:**
   - Open the `src/main/resources/application.properties` file.
   - Configure the database settings (e.g., URL, username, password) based on your local setup.

5. **Run the Application:**
   - Run the application using your IDE's tools or by executing the following command in the terminal:
     ```bash
     ./mvnw spring-boot:run
     ```
     (For Windows, use `mvnw.cmd` instead of `./mvnw`)

6. **Access the Application:**
   - Once the application is running, open a web browser and go to [http://localhost:8080](http://localhost:8080).
   - You should see the login and registration pages.

7. **Explore and Contribute:**
   - Explore the codebase, make modifications, and contribute to the project as needed.
   - Consider adding additional features, improving the user interface, or enhancing security.

This getting started guide assumes you have Maven installed. If not, you can download it from [Maven's official website](https://maven.apache.org/download.cgi).
