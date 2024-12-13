
# GlowGuide

**GlowGuide** is a personalized skincare recommendation tool that uses image analysis to assess skin conditions and provide tailored skincare advice. By uploading a photo of their skin, users can receive product suggestions and skincare routines based on their unique skin needs, helping them achieve a healthy, glowing complexion.

**[View the Project](https://glowguidee.onrender.com/)**

---

## Features

- **Image Analysis**: Upload a photo of your skin, and GlowGuide will analyze the image to detect conditions such as acne, dryness, pigmentation, and more.
- **Personalized Recommendations**: Receive skincare product suggestions and routines based on the analysis of your skin.
- **User-Friendly Interface**: A simple and intuitive web interface for uploading images and receiving personalized skincare advice.
- **Powered by Gemini API**: Skin condition analysis is powered by the **Gemini API**, ensuring accurate and efficient results.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Machine Learning Model**: **Gemini API** for skin condition analysis
- **Web Hosting**: Local or cloud-based hosting (e.g., Heroku, AWS, etc.)

---

## Requirements

To run the project locally, you’ll need:

- **Node.js** (for backend)
- **Express.js** (for handling API requests)
- **Gemini API** (for skin condition model)
- **npm** (for managing dependencies)

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/glowguide.git
cd glowguide
```

### Install Dependencies

Install the required Node.js dependencies:

```bash
npm install
```

---

## Usage

### Running the Application Locally

To start the server locally, use the following command:

```bash
npm start
```

This will launch the web application locally at `http://localhost:3000`.

### Uploading an Image

1. Open the GlowGuide app in your browser.
2. Upload a clear image of your face using the provided file input.
3. Wait for the app to process the image using the machine learning model via the Gemini API.
4. Get personalized skincare recommendations based on the skin analysis.

---

## Gemini API Integration

The skin analysis model is powered by **Gemini API**. The application communicates with the Gemini API to analyze the uploaded image and return skin condition results. Ensure that the Gemini API is deployed and accessible before testing the functionality.

---

## Contributing

We welcome contributions to GlowGuide! If you'd like to contribute, please fork the repository and submit a pull request.

### Steps to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add feature'`)
5. Push your branch (`git push origin feature-name`)
6. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Node.js & Express.js**: For creating the backend server and handling API requests.
- **HTML/CSS/JS**: For building the frontend user interface.
- **Gemini API**: For hosting the machine learning model to analyze skin conditions.
- **Machine Learning Model**: For detecting skin conditions such as acne, pigmentation, etc.

---

Simply replace `https://your-project-link.com` with the actual URL where your project is hosted or deployed.

Let me know if you need further adjustments!
