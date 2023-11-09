# SaaS Data Solution Using Generative AI - Code Reviewer Assistant 

![image](https://github.com/prajwal-cn/Code-Bug-Fixer-As-a-Service-SaaS-using-LLM/assets/127007794/d6da6b89-6f01-401d-a826-076215c4898a)

## Overview
The Code Reviewer Assistant is a web application designed to help developers improve their coding skills through code review exercises. The application leverages OpenAI's GPT-3.5 language model to provide explanations for code errors and suggestions for fixing them.

## Features
1. **Error Explanation:** Users can submit code snippets with associated errors, and the assistant generates natural language explanations for the errors.

2. **Code Correction:** After receiving an error explanation, users can request the assistant to provide a corrected version of the code.

3. **Usage Limit:** Users have a usage limit of three code submissions without charge. After reaching the limit, a payment prompt is presented for continued usage.

4. **Stripe Integration:** The application utilizes Stripe for payment processing, allowing users to purchase additional code review opportunities.

## Getting Started
1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/code-reviewer-assistant.git
   cd code-reviewer-assistant
   ```

2. Install dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. Set up configuration:
   - Create a `config.py` file and configure API keys for OpenAI and Stripe.

4. Initialize the database.
   ```bash
   python app.py
   ```

5. Run the application.
   ```bash
   python app.py
   ```

6. Access the application at `http://127.0.0.1:5000/` in your browser.

## Usage
1. Visit the home page and submit a code snippet with an associated error.

2. Receive an error explanation and have the option to request a corrected version of the code.

3. After three free submissions, users are prompted to make a payment through the integrated Stripe payment gateway to continue using the service.

## Dependencies
- Flask
- OpenAI GPT-3.5
- SQLite
- Stripe

## Contributions
Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note:** Ensure you comply with OpenAI and Stripe usage policies and guidelines when deploying this application.
