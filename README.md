# LabViewer Application

The **LabViewer Application** is designed to assist in managing lab attendance and asset tracking. It includes features such as a splash screen, sidebar navigation, Firebase integration, and cloud data management.

---

## **DEMO**

### **Splash Screen**
- The application starts with a splash screen featuring a loading animation.
- A combination of the **Clock** and **Slider** components is used to create a loading effect with a `TimerInterval` of 3000 milliseconds (3 seconds).
- After the timer ends, the app automatically transitions to the **Main Menu**.
<img src="https://github.com/user-attachments/assets/b19c6044-3e7b-458b-b15e-b1f444e01a4f" alt="Splash Screen" style="height: 300px; width: auto;">

---

### **Main Menu**
- The main menu allows users to navigate between different pages using **Button** components.
- Includes sound and vibration feedback using the **Sound** component.
- The **UrsAI2Sidebar** extension is used to create a sidebar menu for additional navigation options.
<img src="https://github.com/user-attachments/assets/aafd6155-276a-48ce-ab98-5aea2bced7cb" alt="Main Menu" style="height: 300px; width: auto;">
<img src="https://github.com/user-attachments/assets/9c8bf5bf-32ca-4ba5-b1a5-7305396bdc0d" alt="Main Menu" style="height: 300px; width: auto;">
<img src="https://github.com/user-attachments/assets/f43264fb-9e42-4252-821e-706a97f1d8b7" alt="Main Menu" style="height: 300px; width: auto;">

---

### **Firebase Integration**
- The application uses **FirebaseDB** for data storage and management.
- **DatePicker** is used for date selection, while **Spinner** is used for option selection.
- The **Camera** component allows users to take photos of lab assets directly within the app.
- Image files are saved using the **TaifunFile** extension, which helps to rename the files with a shorter, simplified format.
- The recorded data is displayed in a table format using the **Table Arrangement** and **ListView** components.

---

### **Asset Data Entry Screen**
- Users can input asset information using text fields and select options using **Spinner** components.
- Captured photos are uploaded and stored in the Firebase database for documentation purposes.
<img src="https://github.com/user-attachments/assets/10b7307f-8dcc-470b-8759-bcb6b8283a1d" alt="Firebase Integration" style="height: 300px; width: auto;">

---

### **Data Recap Screen**
- The data recap screen displays a list of entered assets using a combination of **Table Arrangement** and **ListView** components.
- Users can review and manage asset data directly from this screen.
<img src="https://github.com/user-attachments/assets/6728bca5-514c-4c00-ac27-c16133c4500a" alt="Data Recap Screen" style="height: 300px; width: auto;">
<img src="https://github.com/user-attachments/assets/138f7ec1-7d45-417b-b86f-fab82d83ef77" alt="Data Recap Screen" style="height: 300px; width: auto;">

---

### **Guidelines and About Us**
- The **Guidelines** screen provides users with instructions on how to use the app effectively.
- The **About Us** screen contains information about the developer and the application.
- Both screens utilize the **Label** component for displaying text content.

<img src="https://github.com/user-attachments/assets/6c8272da-e660-49b4-8e0e-9d06dfdec6e8" alt="Guidelines and About Us" style="height: 300px; width: auto;">
<img src="https://github.com/user-attachments/assets/3716477a-1525-4991-aa86-6c492eec4706" alt="Guidelines and About Us" style="height: 300px; width: auto;">

---

## **Technologies Used**
- **MIT App Inventor**: The development platform for building the application.
- **Firebase**: Used for cloud-based data storage and user authentication.
- **UrsAI2Sidebar**: Extension for sidebar navigation.
- **TaifunFile**: Extension for handling file uploads.
- **Google Spreadsheet**: Used for storing asset data and generating reports.

---

## **How to Use**
1. Launch the application to access the splash screen.
2. Navigate through the main menu using the provided buttons or sidebar menu.
3. Input lab asset data using the data entry screen.
4. Capture photos of assets and upload them to Firebase.
5. Review the entered data on the recap screen.
6. Access the **Guidelines** and **About Us** sections for additional information.

---

## **Contributions**
Feel free to report issues or suggest improvements by submitting a pull request or creating an issue in the repository.

---

Thank you for using the **LabViewer Application**!
