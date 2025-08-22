# Rex

Rex is a real-time AI assistant designed to provide contextual help by capturing screen and audio. It's built using Electron and JavaScript, offering a seamless experience for various use cases, including interviews and learning.

## Features

- **Real-time Assistance**: Provides AI-powered responses based on live screen and audio capture.
- **Customizable Profiles**: Adapt the AI's behavior for different scenarios (e.g., interview, learning).
- **Multilingual Support**: Supports various languages for broader accessibility.
- **Configurable Capture**: Adjust screenshot intervals and image quality.
- **Stealth Features**: Options for discreet operation.
- **Keyboard Shortcuts**: Efficient control over the application.

## Installation

To set up Rex on your local machine, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/RashulRajput/rex.git
    cd rex
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

## Usage

To start the Rex application:

```bash
npm start
```

### API Key Setup

Rex requires a Gemini API key to function. You will be prompted to enter your API key when you first start the application. You can obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/).

### Customization

-   **Profiles**: Select different profiles (e.g., 'interview', 'learning') from the settings to tailor the AI's responses.
-   **Language**: Change the language of the AI assistant in the settings.
-   **Screenshot Interval**: Adjust how frequently screenshots are taken for AI analysis.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.
