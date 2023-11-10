# Chatbot CSV Exporter – Structuring Unstructured Data

## Description
The Chatbot CSV Exporter is an innovative tool aimed at analyzing and structuring unstructured user inputs using the OpenAI API. It interprets the responses from the chatbot and stores the extracted information in a structured CSV format. This enables efficient transformation of text inputs into usable datasets.

## Main Objectives
- Processing unstructured text inputs through the OpenAI API.
- Extraction and structuring of relevant information from the chatbot responses.
- Conversion of the interpreted data into a user-friendly CSV file format.
- Assigning the interpreted data to defined value ranges for precise analysis and processing.

## Main Advantages
- **Value Range Assignment**: The AI assigns interpreted data to defined value ranges, enabling precise analysis and processing.
- **Customizable Chatbot Behavior**: The language model can be adjusted in character and behavior to act empathetically, motivating the user to continue data input.
- **Active Data Collection**: The AI can autonomously recognize missing information and inquire, ensuring more comprehensive data collection.
- **User-Friendly Interface**: Implementation in a chat interface with memory function can realize user-friendly, interactive "questionnaire filling," enhancing user experience.
- **Personalized Experience**: The chatbot engages users in a conversation that feels more personal and less daunting than filling out predefined forms.
- **Time Flexibility**: Users can interact with the chatbot at their own pace, making data entry less stressful and more convenient.
- **Language Accessibility**: With the chatbot's ability to translate, language barriers are minimized, making the tool accessible to a broader audience.
- **Adaptive Interaction**: The AI can adjust to the user's level of understanding, making the tool accessible to users of different educational backgrounds and cognitive abilities.
- **Clarification Support**: Users can ask for clarifications on questions they do not understand, and the chatbot can explain in simpler terms or provide additional context.

## Functionality
- **Prompt Design**: The program uses specifically designed prompts to query the OpenAI API and extract relevant information from user input.
- **Data Interpretation**: Responses from ChatGPT are interpreted based on defined parameters that encompass various aspects of mental and physical wellbeing.
- **CSV Export**: The structured data are saved in a CSV format, turning unstructured inputs into valuable datasets.

## Installation
- **Step 1**: Clone the repository. The program is also available as a Google Colab notebook in the repository and can be opened in this way.
- **Step 2**: Set up your Python environment and install the required dependencies.
- **Step 3**: Configure your OpenAI API keys according to security regulations. Replace 'Your-API-Key' with your actual OpenAI API key.

## Usage
- Run the program and follow the instructions for user input.
- Check the generated CSV file format for the structured data.

## Technological Insights
- The project utilizes the advanced capabilities of the OpenAI API to enable efficient interpretation and structuring of data.

## Data Privacy and Ethical Considerations
- Data privacy and ethical aspects are a significant concern, and the program does not currently meet the required standard in this regard. Therefore, data are stored in a local CSV file over which the user has full control, and no third parties have access. The project currently serves exclusively to demonstrate what is possible with this technology and is explicitly intended only for private self-experiments.

## License
- This project is licensed under the MIT License.



## Example

### Initial User Prompt
This screenshot shows the initial user prompt with information on headache, wellbeing, and additional random information. Note that no name is provided in this prompt.

![1](https://github.com/Sometimesemo/ChatbotCSVExporter/assets/141934590/03683789-fb31-4fa0-a80d-84d6db77990e)



### CSV Data after First Prompt
Here we see the data extracted from the first prompt and saved into the CSV file.

![2](https://github.com/Sometimesemo/ChatbotCSVExporter/assets/141934590/001c0905-8c51-48e6-97c8-480ae4d5e93f)



### Follow-Up Prompt
In this follow-up prompt, the user provides their name and additional information. The chatbot responds and asks for headache information, which is missing in this second Prompt (But is already known from the previous one). This demonstrates the current version's lack of memory, which will be addressed in a future update.

![3](https://github.com/Sometimesemo/ChatbotCSVExporter/assets/141934590/8b0375f7-1400-4672-a8fc-8ec100c596ea)



### Updated CSV File
The CSV file is updated with new information from the follow-up prompt.

![4](https://github.com/Sometimesemo/ChatbotCSVExporter/assets/141934590/b7350ba0-b9ff-4e59-8993-5a7443a9491d)



## Use Cases

- **Anamnesis in Healthcare and Psychotherapy**: By facilitating a conversational interface for anamnesis, the tool can replace traditional forms and make initial consultations more engaging and less formal.

- **Automated Surveying**: Surveys and feedback forms can be conducted in a conversational manner, making them more interactive and less impersonal compared to static forms.

- **Educational Feedback and Assessment**: In educational settings, the chatbot can be used to gather feedback from students or conduct assessments in a way that is engaging and adaptive to their comprehension level.

- **Inclusive Data Collection**: The chatbot's ability to interact and adapt makes it suitable for collecting data from diverse populations, including those with different levels of literacy or language proficiency.
