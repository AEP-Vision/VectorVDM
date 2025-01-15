## What is VectorVDM?
VectorVDM (Vocal Development Mode) is a unique tool that lets you control your Anki/DDL Vector robot with simple voice or text commands. It uses advanced technology from OpenAI GPT-4 to turn your instructions into Python code, run it on the robot, and explain what the code does. It’s perfect for anyone, whether you’re just starting out or already experienced.

---

## Key Features
1. **Speak or Type Commands**: Tell Vector what to do, and the software creates the required code for you.
2. **Simplified Robot Control**: Easily adjust Vector’s head, lift, and movements or play fun animations.
3. **Instant Execution**: The generated code runs on your Vector robot immediately.
4. **Learn by Doing**: Understand how the code works with clear, step-by-step explanations.
5. **Problem Alerts**: If there’s an issue, Vector will notify you and provide feedback.

---

## What You Need
1. **Anki Vector Robot**: Ensure your robot is set up and has SDK access enabled.
2. **Python**: Version 3.7 or newer.
3. **Required Libraries**: Install these before starting:
   ```bash
   pip install anki_vector openai
   ```
4. **OpenAI API Key**: Get a GPT-4 API key from OpenAI and add it to the program.

---

## How to Use

### Step 1: Set Up
- Open the `VDM_V2.py` file in your code editor.
- Replace the placeholder API key with your own:
  ```python
  openai.api_key = "YOUR_OPENAI_API_KEY"
  ```

### Step 2: Start the Program
Run the file in your terminal:
```bash
python VDM_V2.py
```

### Step 3: Give a Command
- When prompted, describe what you want Vector to do. For instance:
  ```
  Describe what you want Vector to do: Move forward and wave.
  ```
- Vector processes your input, generates Python code, runs it, and explains the results.

---

## What Happens Behind the Scenes
1. **Vector Gets Ready**: The robot adjusts its head and lift to prepare for commands.
2. **Code Generation**: The software sends your request to GPT-4, which writes Python code for it.
3. **Code Execution**: Vector immediately performs the actions described in the code.
4. **Code Explanation**: You get a clear breakdown of what the code does.

---

## Troubleshooting
- **Code Not Generated**: If GPT-4 can’t create the code, Vector will notify you and suggest trying again.
- **Execution Errors**: If there’s a problem running the code, Vector will explain what went wrong.

---

## Included Files
- **`VDM_V2.py`**: The main file for interacting with Vector.
- **`vector_program.py`**: A temporary file where generated code is saved and executed.

---

## Who Is This For?
VectorVDM is ideal for:
- **Beginners**: Learn programming with a hands-on, interactive robot.
- **Teachers**: Introduce coding in an engaging and fun way.
- **Developers**: Quickly experiment and test ideas with Vector.

© 2025 IceliteAI
