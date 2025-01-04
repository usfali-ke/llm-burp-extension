# llm-burp-extension

# Steps to Use the Enhanced Extension - v1
1. Save the code to a file, e.g., ChatGPTVulnFinderWithTab.py.
2. Load the extension in Burp Suite:
   Go to Extender > Extensions > Add.
   Select "Python" and load the file.
3. Capture HTTP traffic:
   Intercept and forward requests as usual.
View the analysis results under the "ChatGPT Vulnerabilities" tab.

# Steps to Use the Enhanced Extension - v2
1. Save the code as a .py file, e.g., EnhancedChatGPTVulnFinder.py.
2. Load the extension in Burp Suite:
   Go to Extender > Extensions > Add.
   Select "Python" and load the file.
3. Configure the API key:
   Enter your OpenAI API key in the tab and click "Save API Key."
4. View analysis: Analyze captured HTTP traffic, and results will populate the tab.
5. Use features:
   Search for terms or export results via the provided buttons.

This enhanced version streamlines user interaction and offers advanced features, making it a robust tool for integrating ChatGPT into Burp Suite workflows.

# Steps to Adapt to a Specific LLM
1. Refer to the LLM provider's API documentation.
2. Update the sendToLLM function to match the required payload structure.
3. Configure the API URL and authentication settings using the Burp Suite tab.

This design ensures flexibility and allows the extension to work seamlessly with any LLM supporting an API interface.

Payload Adaptability: The payload structure and headers can be adapted based on the LLM provider’s requirements.
