# 🌍 AI Global Translator : Dynamic Field Label Translation with Azure OpenAI for Power Platform

Enhance your Power Apps with automatic field label translation by integrating Azure OpenAI, making your applications accessible to a global audience. This Power Platform solution automates the translation process by passing field label values from Power Apps to Power Automate, where Azure OpenAI is called upon to provide translations. These are then dynamically displayed in your Power Apps. Follow the guide below to import and set up this solution in your own environment.

## 🚀 Features

- **Dynamic Translation:** Automatically translate field labels in Power Apps using Azure OpenAI.
- **Seamless Integration:** Leverages Power Automate to facilitate communication between Power Apps and Azure OpenAI.
- **Global Accessibility:** Makes your Power Apps accessible to users worldwide by supporting multiple languages.

## 🔧 Prerequisites

Before you begin, ensure you have:

- An active Microsoft Power Platform environment.
- Access to Power Apps and Power Automate.
- An Azure account with Azure OpenAI service provisioned.

## 📦 Installation Guide

### Step 1: Import the Solution

1. Download the solution package from this GitHub repository.
2. In your Power Platform environment, navigate to **Solutions**.
3. Click **Import**, then choose the downloaded solution package and follow the prompts to import.

### Step 2: Configure Azure OpenAI

1. Inside the imported solution, locate the Power Automate flow that interacts with Azure OpenAI.
2. In the HTTP action step, update the URL with your Azure OpenAI endpoint.
3. Replace the placeholder in the headers with your actual Azure OpenAI API key.

## ⚙️ Configuration

- **Power Apps Label Translation:** Update the field labels in your Power Apps to match the keys expected by the Power Automate flow for translation.
- **Language Settings:** Adjust the target languages in the Power Automate flow as per your requirements.

## 🛠️ Improving Load Time

The solution's response time can be optimized by tweaking the concurrency settings within the Power Automate flow. Experiment with these settings to find a balance between performance and resource usage.

## 📚 Documentation

For more detailed instructions on configuring and optimizing your solution, refer to the official Power Platform and Azure OpenAI documentation.

## 🤝 Contributing

Contributions to improve the solution are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## 💬 Support

For support, please open an issue in the GitHub repository or contact the project maintainers.

---

Enhance your Power Apps with our dynamic field label translation solution today and bring your applications closer to a global audience!
