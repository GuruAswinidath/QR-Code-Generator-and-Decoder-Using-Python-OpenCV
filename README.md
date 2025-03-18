# QR-Code-Generator-and-Decoder-Using-Python-OpenCV

**Overview**

This project provides an interactive QR Code Generator and Decoder using Python, OpenCV, and Gradio in Google Colab. Users can:

✅ Enter text to generate a QR code image.

✅ Upload a QR code image to decode and extract the embedded text.

**Features**

✔ Generate QR Codes – Converts user input text into a QR code.

✔ Decode QR Codes – Extracts and displays text from an uploaded QR code image.

✔ Interactive UI – Built with Gradio for easy use.

✔ Works in Google Colab – No need for local installation.

**Usage**

1️⃣ Open Google Colab and run the provided script.

2️⃣ Enter text to generate a QR code.

3️⃣ Download the generated QR code image.

4️⃣ Upload a QR code image to decode its text.

5️⃣ The extracted text will be displayed on the screen.

Code Explanation
1. Generate QR Code
   
   Uses qrcode library to create a QR code from user input.

   Saves the QR code as an image (.png).
   
3. Decode QR Code

   Uses OpenCV (cv2.QRCodeDetector) to scan an uploaded image.

   Extracts and displays the text encoded in the QR code.
   
5. Gradio Interface

   Provides an easy-to-use web interface.

   Accepts text input and file uploads.

   Displays the generated QR code and decoded text.
   
**Example Output**

✅ Generated QR Code:

🔳 Displays the QR code image.

✅ Decoded Text:

📜 Extracts and shows the text from a QR code image.

**Troubleshooting**

❗ Issue: "No QR Code found in the image."

✔ Ensure you upload a valid QR code image.

❗ Issue: OpenCV error while decoding.

✔ Try uploading a clearer QR code image.
