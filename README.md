# Excel Data Parser - Web and Mobile Application

This application allows you to parse Excel data and convert it into a structured format. It is designed to work seamlessly as both a web application and a mobile application.

## Features
- Parse Excel data and display it in a structured table format.
- Responsive design for optimal viewing on both web and mobile devices.
- Easy-to-use interface for copying and pasting data.

## Deployment Instructions

### Web Application
To deploy the web application, simply open the `index.html` file in any modern web browser. No additional setup is required.

### Mobile Application
To deploy the application on your mobile device, follow these steps:

#### Prerequisites
1. **Node.js and npm**: Ensure you have Node.js and npm installed on your system. You can download them from [Node.js official website](https://nodejs.org/).
2. **Apache Cordova**: Install Cordova globally using npm:
   ```bash
   npm install -g cordova
   ```

#### Steps to Deploy
1. **Create a Cordova Project**:
   Navigate to your project directory and create a new Cordova project:
   ```bash
   cordova create MyApp com.example.myapp MyApp
   ```

2. **Add Platforms**:
   Navigate into the project directory and add the platforms you want to target (e.g., Android, iOS):
   ```bash
   cd MyApp
   cordova platform add android
   cordova platform add ios
   ```

3. **Copy Your Web Application**:
   Copy your `index.html` and any other assets (CSS, JavaScript, images) into the `www` folder of the Cordova project.

4. **Build the App**:
   Build the app for the desired platform:
   ```bash
   cordova build android
   cordova build ios
   ```

5. **Deploy to Your Mobile Device**:
   - **For Android**:
     1. Enable USB debugging on your Android device.
     2. Connect your device to your computer via USB.
     3. Run the following command to deploy the app:
        ```bash
        cordova run android
        ```
   - **For iOS**:
     1. Open the `.xcodeproj` file in the `platforms/ios` directory using Xcode.
     2. Connect your iOS device to your computer.
     3. Select your device from the Xcode toolbar and click the "Run" button.

6. **Testing**:
   Once deployed, test the app on your mobile device to ensure it works as expected.

7. **Publishing**:
   If you want to publish the app to the Google Play Store or Apple App Store, follow the respective guidelines for publishing apps.

## Usage
1. Open the application in a web browser or on your mobile device.
2. Paste your Excel data into the textarea provided.
3. Click the "Parse Data" button to convert the data into a structured table format.
4. Copy the parsed data from the table and paste it into your Excel file.

## Support
If you encounter any issues or have any questions, please feel free to reach out for support.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.