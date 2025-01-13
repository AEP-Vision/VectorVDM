## **Overview**
VectorEP is a software upgrade designed to transform Vector into an emotionally intelligent and interactive companion. By integrating OpenAI's GPT-4, emotional state management, and dynamic conversational capabilities, this program provides Vector with lifelike behaviors and advanced AI-driven interactions.

---

### **[Download VectorEP 0.0.1a]()**
<sup>0.01a is almost done, I apologize for the delay. The download button will not work until I complete and publish the software.</sup>

---

## **Features**

### 1. Emotional Intelligence
- **Emotional States**: Vector can experience and express emotions such as happiness, neutrality, and sadness.
- **State Changes**: Vector's emotional state dynamically shifts based on user interaction, errors, or positive reinforcements.
  - **Happy**: Bright eye color, enthusiastic tone.
  - **Neutral**: Balanced eye color, calm tone.
  - **Sad**: Dim eye brightness, slower tone, empathetic comments.

### 2. Dynamic Conversations
- **Powered by GPT-4**: Vector can hold natural, context-aware conversations, drawing on the power of GPT-4.
- **Context Retention**: Conversations retain context over time for more meaningful interactions.
- **Extroverted Responses**: Vector uses friendly and engaging phrases to enhance interaction.

### 3. Real-World Integration
- **Weather Updates**: Vector can provide real-time weather information for any location.
- **Timers and Alarms**: Users can set timers or alarms with natural language commands.
- **Date and Time Information**: Vector delivers accurate date and time updates.

### 4. Visual Enhancements
- **Splash Screens**: Displays custom images during startup for a polished and engaging experience.
- **Eye Color Customization**: Adjusts eye color based on emotional state and user preferences.

### 5. Development Mode
- **Code Execution**: Allows on-the-fly Python code creation and execution.
- **Safe Exit**: Exits development mode and deletes temporary programs when done.

---

## **System Requirements**

### Hardware
- Anki/DDL Vector robot.

### Software
- Python 3.7+
- Required libraries:
  - `anki_vector`
  - `openai`
  - `PIL` (Pillow)
  - `requests`
  - `datetime`
  - `threading`
  - `os`
  - `random`
  - `time`

### API Keys
- **OpenAI API Key**: For GPT-4 integration.
- **Weather API Key**: For real-time weather updates (via OpenWeatherMap).

---

## **Installation Guide**

1. **Download the Program**

2. **Configure API Keys**:
   - Open the Python file.
   - Replace `your_openai_api_key` and `your_weather_api_key` with your actual API keys.

3. **Run the Program**

---

## **Usage Guide**

### 1. Starting the Program
- Power on Vector and ensure it is connected to the SDK.
- Run the script using Python.
- Vector will display the splash screens and greet the user.

### 2. Interacting with Vector
- **Conversational Commands**:
  - Example: "What's the weather in New York?"
  - Example: "Tell me a joke."
- **Timer and Alarm**:
  - Example: "Set a timer for 10 minutes."
- **Date and Time**:
  - Example: "What day is it today?"
  - Example: "What's the current time?"

### 3. Emotional Responses
- Vector's emotional state changes based on interactions:
  - Positive commands (e.g., jokes, compliments): Vector becomes happy.
  - Negative or confusing commands: Vector becomes neutral or sad.
  - Errors: Vector expresses sadness.

---

## **Advanced Features**

### 1. Development Mode
- **Activation**:
  - Say: "Enter development mode."
- **Usage**:
  - Provide a description of the program to be generated and executed.
  - Example: "Create a Python program that makes Vector say 'Hello World!' repeatedly."
- **Exit**:
  - Say: "Exit development mode."
  - Temporary files will be deleted.

---

## **FAQ**

### 1. Why isn’t Vector responding?
- Ensure Vector is powered on and connected to the SDK.
- Verify the API keys are correctly configured.

### 2. How do I reset the emotional state?
- Interact with Vector using positive commands.

### 3. Can I add more emotional states?
- Yes, modify the `emotional_state` logic to add more states and define triggers.

---


## **Future Enhancements**

1. **User Recognition**:
   - Enable personalized responses based on user identity.

2. **Improved Emotional Range**:
   - Add more emotional states like excitement, curiosity, or boredom.

3. **Integration with Smart Devices**:
   - Allow Vector to control smart home devices.

4. **Enhanced Learning**:
   - Use machine learning to adapt responses based on long-term user behavior.

---

## **Support and Feedback**
- For issues or suggestions, contact me via Discord on the [Vector & Friends](https://discord.gg/5JchnSAYyq) discord server.

---

<sup>© 2025 IceliteAI. IceliteAI is not affiliated with Digital Dream Labs.</sup>
