## 1. 3D Printing (Task 1)

I successfully explored the mechanics of 3D printing and reviewed the standard operating procedures. After downloading an STL file, I configured crucial slicing parameters—including bed temperature and infill density—using slicing software. The model was successfully sliced into G-code and executed on the 3D printer.

---
## 2. API (Task 2)

An **Application Programming Interface (API)** is a bridge that allows different software applications to communicate. It operates on a request-response cycle: a client requests information, and the API retrieves and returns the relevant data. APIs power everyday applications like weather updates, payment gateways, and social media feeds.

**Project Application:** For this task, I built a **Random Dog Generator** user interface. The app makes asynchronous calls to a public dog API, retrieves image data, and dynamically displays it to the user. 

**Source Code:** [View on GitHub](https://github.com/gouravpd26-cmyk/gourav-api)

**Website link:** [Dog-API](https://gourav-api.vercel.app/)

![Dog api image](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/dog-api-image-task-2.jpg?raw=true)

---
## 3.Working with GitHub (Task 3)

I successfully completed the GitHub integration task by exploring and applying essential collaboration tools. Following the repository's README instructions, I familiarized myself with continuous integration by utilizing GitHub Actions to automate workflows. Additionally, I gained practical experience in project tracking and code review by managing tasks through GitHub Issues and proposing code changes via Pull Requests. This exercise solidified my understanding of professional version control practices.

### Pull request

![Pull request](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/working-with-github-task-3.jpg?raw=true)

---
## 4. Command lines on Ubuntu (Task 4)

I successfully navigated the Ubuntu command line and executed the following fundamental file and directory management tasks:

* **Directory Creation & Navigation:** Created a new directory named `test` using `mkdir` and navigated into it using the `cd` command.
* **File Management:** Generated a blank file directly from the terminal without a text editor utilizing the `touch` command, and verified its creation using `ls` to list the directory contents.
* **Bulk Operations:** Created 2,600 individual directories simultaneously with alphanumeric naming conventions utilizing bash brace expansion.
* **File Concatenation:** Successfully combined the contents of two separate text files, outputting the merged text directly to the terminal display using the `cat` command.

This exercise solidified my understanding of core bash commands and shell automation.

### Generated multiple folder
![multiple folder image](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/marvel-task-4-ubuntu.jpg?raw=true)

### Concatenation of two files

![concatenation image](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/marvel-task-4-ubuntu2.jpg?raw=true)

---
## 5. Build Your Own Brain - Linear Regression from Scratch (Task 5)

**Objective:** To implement a Linear Regression model from scratch using Gradient Descent and evaluate its performance against the `scikit-learn` library using the California Housing dataset.

### Implementation Highlights
* **Custom Algorithm:** Developed a Python class to manually compute predictions, calculate gradients, and update weights and bias over 1,000 iterations.
* **Optimization:** Utilized Gradient Descent with a configured learning rate of 0.1 to iteratively minimize the Mean Squared Error (MSE).
* **Preprocessing:** Applied `StandardScaler` for feature normalization, which proved critical for preventing gradient divergence and ensuring smooth convergence.

### Performance Comparison
Both models were evaluated using standard metrics (MSE, MAE, and R²).
* **Custom Model:** Achieved high accuracy, successfully converging to mirror the optimized library's metrics.
* **Scikit-Learn:** Delivered nearly identical results instantaneously by utilizing Ordinary Least Squares (OLS) rather than iterative descent.
* **Visualization:** A 2D plot mapping 'Median Income' against 'House Value' successfully demonstrated the model's line of best fit intersecting the data distribution.

### Key Takeaways
Building this algorithm manually provided a profound understanding of how weights are optimized mathematically, emphasizing the critical importance of feature scaling and learning rate calibration in machine learning pipelines.

![code image](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/linear-regression-task-5.png?raw=true)

![graph image](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/linear-regression-graph-task-5.png?raw=true)

---
## 6. The Matrix Puzzle (NumPy and Matplotlib) (Task 6)

**Objective:** Decode a scrambled NumPy array to reveal a hidden image using array manipulation and Matplotlib visualization.

**Process:**
1. **Loading Data:** Loaded the `encoded_array.npy` file using `np.load()`.
2. **Reshaping:** Determined the array size (10,000 elements) and reshaped the flat 1D array into a 100x100 2D square matrix using `.reshape((100, 100))`.
3. **Reorienting:** The data was tilted, so `np.rot90(decoded_image, k=-1)` was applied to rotate the matrix 90 degrees clockwise, correcting the upright orientation.
4. **Visualization:** Plotted the final matrix using `plt.imshow()` with axes disabled.

**Outcome:** Successfully decoded the matrix to reveal an upright yellow smiley face.

![code-task-6](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/decode-matrix-code-task-6.png?raw=true)

![image-task-6](https://github.com/gouravpd26-cmyk/marvel-level-0-reports/blob/main/decode-matrix-image-task-6.png?raw=true)

---
## 7. Create a Portfolio Webpage (Task 7)

I developed a responsive personal portfolio website to showcase my background, technical interests, and projects. Built using modern web frameworks and styled with custom CSS. The final codebase is version-controlled and successfully pushed to a GitHub repository for deployment.

**Link:** [My-Portfolio](https://my-portfolio-jade-alpha-32.vercel.app)

![Portfolio-page]()

---
## 8. Writing Resource Article using Markdown (Task 8)

I authored a technical Markdown article titled "The Whispering Silicon: An Introduction to Acoustic Cryptanalysis". The repository, containing the fully formatted plain-text resource, has been successfully committed and pushed to GitHub.

**Link:** [Acoustic Cryptanalysis](https://github.com/gouravpd26-cmyk/marvel-md-task/blob/main/acoustic_cryptanalysis.md)

---
## 9. Tinkercad (Task 9)

**Task Overview**
Successfully completed the Tinkercad simulation tasks, progressing from basic circuit familiarization to building a functional sweep radar system.

**Key Accomplishments:**
* Simulated a basic ultrasonic distance sensor circuit, successfully outputting real-time distance metrics to the Serial Monitor.
* Engineered a simulated radar system by integrating the ultrasonic sensor with a micro servo motor.
* Programmed the servo to sweep across a specified degree range while the ultrasonic sensor continuously emitted sound waves to detect object distances and map the immediate area.

**Task Outcomes:**
* Gained hands-on proficiency with the Tinkercad simulation environment and component wiring.
* Understood the practical working principles of ultrasonic sensors (time-of-flight measurements) and servo motor control.
* Grasped the foundational concepts of radar technology and automated spatial scanning.

![Tinkercad]()

---
## 10. Speed Control of DC Motor (Task 10) 

I successfully completed the speed control task for DC motor using an Arduino UNO and an L298N H-Bridge motor driver. The circuit was first simulated in Tinkercad to verify the logic and wiring. Subsequently, I constructed the physical hardware setup, utilizing signals to effectively regulate the motor's RPM. The complete hardware demonstration and its functionality were successfully recorded on video.

![Video]()

---
## 11. LED Toggle Using ESP32 (Task 11)

I successfully configured the Arduino IDE for ESP32 development and programmed the board to operate as a standalone web server. By connecting the ESP32 to a local network, I deployed a web interface that sends HTTP requests to the microcontroller. The system accurately parses these incoming client requests to toggle the state of an LED connected to the GPIO pins, demonstrating fundamental IoT hardware control.

![Image]()

![Video]()

---
## 12. Karnaugh maps and deriving the logic circuit (Task 14)

This project details the design of a simple burglar alarm circuit using two inputs: a door sensor and a key button. The objective is to activate an LED or buzzer only if the door is opened without the authorized key being pressed. 

By analyzing the four possible input combinations, I determined the alarm triggers in just one specific scenario. Using a Karnaugh map, I derived the simplified Boolean logic expression: Alarm equals Door AND NOT Key ($A = D \cdot \overline{K}$). 

To construct this circuit, the key input connects to a NOT gate. This inverted signal, alongside the direct door input, feeds into an AND gate. The resulting output from the AND gate successfully drives the alarm mechanism.

![Karnaugh]()

---
## 13. Introduction to VR (Task 17)

I have successfully completed this task. The comprehensive study—covering the core differences between VR and AR, current technology trends, the software/hardware stack, and prominent Indian companies in the space—is fully documented in the attached .md file.

Link to report: [.md file](https://github.com/gouravpd26-cmyk/Intro-to-VR/blob/main/VR.md)

---


