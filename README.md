# Advanced QR Code Generator

A lightweight, browser-based tool to generate highly customizable QR codes. This project allows users to create QR codes for URLs or text, customize colors, adjust dimensions, and even add a personalized signature or watermark directly onto the generated image.

## 🚀 Features

-   **Real-time Generation:** Generate QR codes instantly as you type or adjust settings.
-   **Custom Colors:** Choose specific foreground and background colors to match your branding.
-   **Adjustable Size:** Scale the QR code from 100px to 500px.
-   **Quiet Zone Control:** Adjust the border thickness (modules) around the QR code.
-   **Custom Signature:** Add an optional text signature (like a GitHub username) at the bottom of the QR code.
-   **High Error Correction:** Uses `QRCode.CorrectLevel.H` to ensure the QR remains readable even with an added signature.
-   **Downloadable:** Save your generated QR code as a PNG image with a single click.
-   **Responsive Design:** Works seamlessly on both desktop and mobile devices.

## 🛠️ Technologies Used

-   **HTML5 & CSS3:** For structure and modern, responsive styling.
-   **JavaScript (Vanilla):** For logic and DOM manipulation.
-   **QRCode.js:** A cross-browser JavaScript library for generating QR codes.

## 📖 How to Use

1.  **Enter Content:** Type the URL or text you want to encode in the "Content" field.
2.  **Customize Appearance:**
    *   Select your preferred **QR Color** and **Background Color**.
    *   Use the sliders to adjust the **Size** and **Border**.
3.  **Add a Signature (Optional):** Enter text in the "Signature" field to overlay a small label at the bottom of the QR code.
4.  **Generate:** Click the **"Generate QR Code"** button to refresh the preview.
5.  **Download:** Once satisfied, click **"Download Image"** to save the result as `qrcode_generato.png`.

## 💻 Local Setup

Since this is a client-side application, you don't need a server.

1.  Clone the repository:
    ```bash
    git clone https://github.com/danielelozzi/QR.git
    ```
2.  Open `index.html` in your favorite web browser.

## 📄 License
This project is open-source. Feel free to use and modify it!