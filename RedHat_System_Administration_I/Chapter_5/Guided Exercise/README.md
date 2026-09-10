# Guided Exercise: Ask Questions and Evaluate Answers from the Command-line Assistant

## Author

**Eng. Adel Shata**

<a href="https://github.com/Adel-Shata"><img src="https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat-square" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/adel-shata-a1b9a7376/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square" alt="LinkedIn"></a>
<a href="mailto:adel.shata.eng@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?logo=gmail&logoColor=white&style=flat-square" alt="Email"></a>

---

### 1. Log in to the ``servera`` machine as the student user.

![Step 1](docs/step_1.png)

---

### 2. Install the command-line assistant on the servera machine using ↓↓.

```bash
student@workstation:~$ sudo dnf install command-line-assistant
```

![Step 2](docs/step_2.png)

---

### 3. Ask the command-line assistant for tools that can list processes that are running under the student user.

![Step 3](docs/step_3.png)
---

### 4. Following the instructions that the command-line assistant provides, run the ``top`` command to list the processes run by the student user. Pipe the top command output to the command-line assistant, and ask the command-line assistant to explain the output.

**(4.1, 4.2). Using ``man top`` to check how to pipe to output to another process without issues.**

![Step 4.1](docs/step_4_p1.png)
![Step 4.2](docs/step_4_p2.png)

**4.3. Ask the command-line assistant to explain the output.**

![Step 4.3](docs/step_4_p3.png)

*****

---

### 5. Troubleshoot and resolve an issue with the web server (the httpd service) by using the command-line assistant.

**5.1. Use the ``sudo systemctl start`` command to try to start the web server. Use student as the password.**

![Step 5.1](docs/step_5_p1.png)

**5.2. Ask the command-line assistant to help interpret the failure messages so that you can troubleshoot why the httpd service failed to start.**

![Step 5.2](docs/step_5_p2.png)

**5.3. Ask the command-line assistant to provide a solution to the issue.**

![Step 5.3](docs/step_5_p3.png)

**5.4. Fix the syntax error in the ``/etc/httpd/conf/httpd.conf`` file by using the solution that the command-line assistant provides. Use student as the password.**

![Step 5.4](docs/step_5_p4.png)

**(5.5, 5.6). Restart the ``httpd`` service. Use student as the password. Verify that the httpd service started successfully.**

![Step 5.5](docs/step_5_p5.png)
---

### 6. Return to the workstation machine as the student user.

![Step 6](docs/step_6.png)

