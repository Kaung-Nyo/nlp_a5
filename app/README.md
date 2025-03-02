# GPT Chat App (Dash Version)

A modern chat application built with Dash and a pre-trained GPT model from Hugging Face.

## Features
- Interactive chat interface using Dash components
- Real-time response generation using GPT-2
- Bootstrap styling for a modern look
- Message timestamps
- Loading spinner during response generation
- Persistent chat history during session
- Responsive design

## Installation

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the App

1. Start the Dash server:
```bash
python main.py
```

2. Open your web browser and go to:
```
http://localhost:8050
```

## Configuration

You can modify the following in `main.py`:
- `model_name`: Change to use a different GPT model
- Generation parameters in the `generate_response()` function:
  - `max_length`
  - `temperature`
  - `top_k`
  - `top_p`

## Advantages of this Dash Version
- More interactive components
- Better state management
- Built-in loading states
- Modern UI with Bootstrap
- Real-time updates without page refresh
- Better error handling

## Note
The app uses the CPU by default but will automatically use CUDA if a GPU is available.
