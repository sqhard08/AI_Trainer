# AI Trainer

This script is an automated system designed for training AI models on nature-related topics through continuous question generation and processing.

## Key Features

- **Initiates the Training Process**: Starts with a seed question about nature.
- **AI API Engagement**: Uses an AI API to generate responses, simulating learning.
- **Interaction Logging**: Logs all interactions for analysis and model improvement.
- **Follow-up Questions**: Creates follow-up questions based on previous responses, mimicking natural conversation flow.
- **Random Intervals**: Implements random intervals between interactions (9, 12, 16, 19, or 21 minutes) to simulate varied learning patterns.

## Highlights

- **Dynamic Question-Answer Generation**: Leverages an AI API for dynamic question-answer generation, continuously expanding the knowledge base.
- **Comprehensive Logs**: Maintains comprehensive logs in `/root/gainet.log` for tracking AI learning progress.
- **Robust Error Handling**: Features robust error handling and auto-restart capabilities to ensure uninterrupted training.
- **Endless Loop Operation**: Operates in an endless loop, facilitating long-term, evolving AI education on nature topics.
- **Optimized for Background Execution**: This script is optimized for background execution on servers, providing a consistent stream of training data to enhance AI.

## Installation

To install and use this AI training tool, follow these steps:

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/sqhard08/AI_Trainer.git
    ```

2. **Navigate to the Project Directory**:

    ```sh
    cd AI_Trainer
    ```

3. **Install Required Dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Script**:

    ```sh
    python gainet.py
    ```

---
