## **Health Tracker**

### **Overview**
The Health Tracker is a Tkinter-based GUI application designed to assist users in tracking their health-related symptoms. It collects user details, validates inputs, retrieves relevant health information from the web, and stores data in a local database for future reference. This application is built to provide a simple, user-friendly interface for health tracking and information retrieval.

### **Features**
- **User Input Form:** Allows users to enter personal details such as name, phone number, age, symptoms, and duration.
- **Data Validation:** Ensures that user inputs meet specified criteria (e.g., age must be positive, phone number must have 10 digits).
- **Google Search Integration:** Automatically searches for health-related articles and resources based on the symptoms provided.
- **Database Storage:** Saves user details securely in an SQLite database for record-keeping and future reference.
- **Search Result Display:** Presents search results in a separate, scrollable window for easy reading.
- **Form Refresh:** Users can reset the form to enter new details without restarting the application.
- **Exception Handling:** Ensures smooth application performance by handling missing or incorrect inputs gracefully.

### **Tech Stack**
- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Database:** SQLite3
- **Web Scraping & API Integration:** Requests, BeautifulSoup, Google Search API
- **Data Validation:** Regex

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Health-Tracker.git
   cd Health-Tracker
   ```
2. Install required dependencies:
   ```bash
   pip install sqlite3 requests beautifulsoup4 google
   ```
3. Run the application:
   ```bash
   python main.py
   ```

### **Usage**
1. **Launch the Application**
   - Run `python main.py` to start the Health Tracker GUI.
2. **Enter Health Details**
   - Provide name, age, phone number, symptoms, and duration in the form.
3. **Submit the Form**
   - Click the **Submit** button to validate inputs and fetch relevant health information.
4. **View Search Results**
   - A new window opens displaying fetched health-related resources.
5. **Refresh the Form**
   - Use the **Refresh** button to clear the form and input new details.

### **Contributing**
Contributions are welcome! If you find issues or want to improve the application, feel free to:
- Fork the repository.
- Open an issue.
- Submit a pull request.
