#J.A.R.V.I.S - CHAT AI Assistant for Windows
Project Overview:

#J.A.R.V.I.S# is a sophisticated AI assistant application designed for the Windows platform, leveraging the capabilities of the Gemini API to generate intelligent, context-aware responses. This application features both text-based and voice-based interaction, providing users with a seamless and interactive experience. The assistant is capable of performing various offline tasks such as opening applications, searching the web, and navigating to predefined websites, all while offering real-time chat and voice feedback.

#Key Features:

Dual Interaction Mode: Engage with the assistant via text input in a chat-like interface or through voice commands using speech recognition.
Gemini API Integration: Utilizes Google's Gemini API to process user input and generate AI-driven responses.
Voice Feedback: Responses are provided audibly using speech synthesis, enhancing the user experience with verbal communication.
Offline Commands: Execute predefined offline actions such as launching applications (e.g., Notepad, Calculator, File Explorer), and navigating to popular websites like Instagram, YouTube, etc.
Real-Time Chat Interface: User and assistant interactions are displayed in a dynamic chat window, with clear distinction between user and assistant messages.
Technologies Used:

C# & WPF (Windows Presentation Foundation): For the creation of the desktop application and user interface.
Gemini API (Google Cloud): Powers the natural language processing and text generation features of the assistant.
Speech Recognition & Synthesis: Built-in speech recognition and synthesis capabilities within the .NET framework are used for voice interaction.
Newtonsoft.Json: Used for parsing and serializing JSON data in communication with the Gemini API.
Installation Instructions:

Clone the repository to your local development environment.
Open the solution file in Visual Studio.
Replace the GeminiApiKey placeholder in the MainWindow.xaml.cs file with your own valid API key from Google Cloud.
Build and run the application.
Usage:

Users can interact with the assistant by typing text into the input box or by using voice commands to trigger various functions.
The assistant provides responses in both text and voice formats, ensuring a dynamic user experience.
The application can perform tasks such as launching applications, searching Google, or navigating to predefined websites.
Prerequisites:

Gemini API Key: A valid API key from the Google Gemini API is required for text generation.
.NET Framework: Ensure you have the required version of the .NET Framework installed.
Contributing: Contributions are welcome! Feel free to fork the repository, submit pull requests, and enhance the functionality of the assistant. Please ensure all contributions adhere to the project's coding standards and maintain high-quality documentation.

#Note:

The Gemini API requires an active key, which can be obtained from the Google Cloud Console.
The assistant supports voice feedback and recognition, making it accessible for hands-free use. Ensure your microphone and speakers are properly configured for optimal experience.
License: This project is licensed under the MIT License - see the LICENSE file for details.
