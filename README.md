# Kutumb Project

This is a web application designed to manage user authentication and quota listing efficiently. The app features three pages with distinct functionalities: Login Page, Quota Listing Page, and Add Quota Page. The application is deployed on a free domain, which might require multiple API recall attempts due to server limitations.

## Deployment Link
[Visit the Kutumb App](https://amazing-marigold-f1de66.netlify.app/quota_list)

## Source Code
[GitLab Repository](https://gitlab.com/amit979/kutumbproject)

---

## ⚠️ Note:
- If the page does not respond, please refresh the page multiple times.
- Since the app is deployed on a free domain, it may require more than **5 API recall attempts** before the APIs work correctly.

---

## Features and Pages Overview

### 1. **Login Page**
   - **Image**: *(Upload the image link from your desktop here.)*
   - **Functionality**:
     - OTP validation: Enter OTP `1234` to proceed. Incorrect input will show an error message.
     - OTP input accepts only **4 digits**. Entries with more or fewer digits are restricted.
     - Both **username** and **OTP fields** must be filled. Submission is disabled until all fields are complete.
     - On successful submission, the user is redirected to the **Quota Listing Page**.

---

### 2. **Quota Listing Page**
   - **Functionality**:
     - Displays a list of quotas with images and text.
     - Includes a floating **"Add Quota"** button on the left side, which opens the **Add Quota Page**.
     - Pagination support:
       - **Next Button**: Appears only when more data is available.
       - **Previous Button**: Appears only when prior data exists.
     - The page is fully responsive for various screen sizes.

---

### 3. **Add Quota Page**
   - **Functionality**:
     - Allows users to add quota text and upload files.
     - Validation:
       - Both **quota text** and **file** fields are mandatory.
       - Displays an error notification for invalid submissions.
     - On successful submission, the form closes via a popup notification.

---

## How to Use the App
1. **Login Page**:
   - Enter username and OTP (`1234`).
   - Click **Submit** to navigate to the **Quota Listing Page**.

2. **Quota Listing Page**:
   - Browse through the listed quotas.
   - Use the pagination buttons to navigate.
   - Click the **Add Quota** floating button to open the Add Quota form.

3. **Add Quota Page**:
   - Fill in the required quota text and upload a file.
   - Submit the form to add a new quota to the list.

---

## Screenshots
*(Upload the relevant images/screenshots here.)*
![Uploading image.png…]()

![image](https://github.com/user-attachments/assets/87539d16-5afe-4f5f-bb05-0edcea745bed)
![image](https://github.com/user-attachments/assets/3dad4b37-e75b-4bc0-ba75-f73487a5d552)



---

## Technologies Used
- **Frontend**: React.js
- **Deployment**: Netlify
- **Version Control**: GitLab

---

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://gitlab.com/amit979/kutumbproject.git
   cd kutumbproject
