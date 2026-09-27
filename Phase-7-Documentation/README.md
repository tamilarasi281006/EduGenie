# Phase 7: Documentation

## How to Run the Project Locally

1. Clone the repository.

2. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

3. Activate the virtual environment:

   **Windows:**

   ```bash
   .venv\Scripts\activate
   ```

   **Mac/Linux:**

   ```bash
   source .venv/bin/activate
   ```

4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Create a `.env` file and add:

   ```text
   GEMINI_API_KEY=your_key_here
   ```

6. Run the application:

   ```bash
   python app.py
   ```

7. Open the application in your browser:

   ```text
   http://127.0.0.1:5000
   ```
