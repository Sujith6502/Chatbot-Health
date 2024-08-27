
# Conversational Wellness Score Calculator

## Overview

The **Conversational Wellness Score Calculator** is a web-based application built with Streamlit. It provides users with a conversational interface to evaluate their wellness based on health, lifestyle, diet, exercise, and stress levels. The app calculates a wellness score out of 100 and offers recommendations based on the score.

## Features

- **Conversational Flow:** Users engage with the app in a natural, text-based conversation.
- **Score Calculation:** The app calculates a wellness score based on user responses.
- **Personalized Recommendations:** Depending on the score, users receive tailored advice, such as joining an advanced wellness program, starting with a basic health program, or consulting with a wellness coach.

## Requirements

- Python 3.7 or higher
- Streamlit

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/conversational-wellness-score-calculator.git
   cd conversational-wellness-score-calculator
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` does not exist, you can manually install Streamlit:
   ```bash
   pip install streamlit
   ```

## Running the Application

To run the application locally:
```bash
streamlit run app.py
```

This will start a local server, and you can access the app in your web browser at `http://localhost:8501`.

## Deployment

### Deploy to Streamlit Cloud

1. **Push your code to GitHub**: Ensure your project is hosted on GitHub.

2. **Deploy on Streamlit Community Cloud**:
   - Go to [Streamlit Community Cloud](https://streamlit.io/cloud).
   - Log in with your GitHub account.
   - Click "New app" and select the repository and branch where your script (`app.py`) is located.
   - Follow the on-screen instructions to deploy the app.

3. **Access the Deployment Link**: Once deployed, you will receive a URL that you can share with others to access the app.

## Usage

The app guides users through a series of questions related to their health, lifestyle, diet, exercise, and stress levels. Users input their answers in a text-based format, and the app calculates a wellness score based on these responses. After the score is calculated, the app provides personalized recommendations.

## Example Conversation

- **App:** "Do you have any chronic health conditions? (yes/no)"
- **User:** "No"
- **App:** "How often do you visit a doctor for a check-up? (regularly/occasionally/rarely)"
- **User:** "Regularly"
- (Continues with other questions...)
- **App:** "Your Wellness Score is: 85/100. We recommend you enroll in our advanced wellness program."

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository, make your changes, and submit a pull request. Make sure to follow the coding style and include appropriate tests for your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or feedback, feel free to reach out to [thiruveedulasujith6502@gmail.com](mailto:thiruveedulasujith6502@gmail.com).
