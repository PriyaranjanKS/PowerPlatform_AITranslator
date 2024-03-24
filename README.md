# Dynamic Field Label Translation for Power Apps using Azure OpenAI

This repository hosts a Power Platform solution designed to dynamically translate the field labels in Power Apps using Azure OpenAI. The solution automates the translation process by passing field labels from Power Apps to Power Automate, where Azure OpenAI is invoked to perform the translation. The translated labels are then passed back to the Power App, allowing for a seamless international user experience.

## Overview

The solution aims to simplify the process of making Power Apps accessible to a global audience by providing dynamic translation of field labels. It leverages the powerful AI capabilities of Azure OpenAI to ensure accurate and context-aware translations.

Key Features:
- Dynamic translation of Power Apps field labels.
- Integration with Azure OpenAI for high-quality translations.
- Customizable to support various languages offered by Azure OpenAI.
- Enhanced user experience for non-English speakers.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:
- A Microsoft Power Platform environment.
- Access to Power Apps and Power Automate.
- An Azure subscription with Azure OpenAI service configured.

### Installation Instructions

1. **Download the Solution Package**
   - Clone this repository or download the solution package directly from the GitHub releases page.

2. **Import the Solution into Power Platform**
   - Navigate to your Power Platform Admin Center.
   - Go to **Solutions** and click **Import**.
   - Choose the downloaded solution package and follow the prompts to import.

3. **Configure Azure OpenAI Integration**
   - Within the Power Automate flow included in the solution, locate the HTTP action responsible for calling the Azure OpenAI service.
   - Update the HTTP action with your Azure OpenAI endpoint URL and API key. This will authenticate your requests to Azure OpenAI and enable translation.

### Post-Installation Configuration

- **Optimize Load Times**: To improve the solution's performance, especially the load times, consider adjusting the concurrency settings within the Power Automate flow. This can significantly enhance the user experience by reducing wait times for label translations.

## Usage

Once configured, your Power App will automatically translate field labels based on the settings defined in the Power Automate flow. Users will see the translated labels, making your app more accessible to a non-English-speaking audience.

## Contributing

Contributions are welcome! If you have suggestions for improving this solution, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
