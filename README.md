# 🎣 Cheat-checker Phishing Template

This project is designed for **educational purposes**, providing a simple phishing template within a Docker environment. It includes an HTML phishing page that can be customized and deployed for awareness and training purposes.

---

## ✨ Features

- **🛠 Dockerized Environment**: Easy setup using Docker.
- **📄 Included HTML Phishing Page**: A ready-to-use HTML page designed to mimic a common login interface.
- **🔄 Customizable Payload**: Simple to replace the payload with your own executable.

---

## 🚀 Installation & Usage

Follow these steps to set up and run the cheatchecker phishing template:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ilolm/phishing_cheatchecker.git
   cd phishing_cheatchecker
   ```

2. **Add Your Payload**:
   - Place your backdoor or payload in the `html` directory.
   - Rename it to `cheat-checker.exe` for the template to work correctly.

3. **Build the Docker Image**:
   ```bash
   docker image build -t cheatchecker .
   ```

4. **Run the Docker Container**:
   ```bash
   docker container run -d -p 80:80 cheatchecker
   ```
   
5. **Access the Phishing Page**:
    - Open your browser and navigate to http://localhost to view the phishing page.

---

## 🖼️ Screenshot

![Screenshot](./screenshot.png)

---

## ⚠️ Disclaimer

This project is intended strictly for **educational purposes**. Unauthorized use of this template for any malicious activity is illegal and unethical. Always ensure you have explicit permission before conducting any security testing.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
