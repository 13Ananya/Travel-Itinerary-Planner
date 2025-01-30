
# 🌍 Travel Itinerary Planner ✈️

A Python-based travel itinerary planner that generates personalized day trip itineraries for users. By providing the city and their interests, users receive a customized itinerary to help them plan their travel efficiently. 🌟

This project utilizes Langchain, Groq, and Gradio to create a seamless interactive experience for users to input their desired city and interests, while an AI model generates the itinerary. 🤖

## ✨ Features

- 🏙️ **City Input**: Users can specify the city they wish to visit.
- 💬 **Interest-Based Suggestions**: Users provide their interests (e.g., museums, parks, beaches) and receive a personalized itinerary.
- 🤖 **AI-Powered Itinerary**: Powered by Langchain's `ChatGroq`, the AI generates a brief, bulleted list of activities based on the city and interests.
- 🖥️ **Interactive Interface**: Gradio is used to create an intuitive web interface for user input and displaying the itinerary.

## 🛠️ Technologies Used

- **Python** 🐍: The core programming language.
- **Langchain**: For AI-driven conversation and itinerary generation.
- **Groq API**: To invoke the language model for generating the itinerary.
- **Gradio**: To create an interactive UI for the users.
- **ChatGroq**: Integrates the Groq API for model invocation using `llama-3.3-70b-versatile`.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8 or later. 🖥️

Install the required dependencies via `pip`:

```bash
pip install langchain gradio langchain-groq
```

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/travel-itinerary-planner.git
   cd travel-itinerary-planner
   ```

2. Set up the Groq API key by creating a `.env` file in the project root:
   ```
   GROQ_API_KEY=your_api_key
   ```

## 💡 Example

**Input**:

- 🌆 City: Bangalore
- 🎯 Interests: parks, historical sites, local food

**Output**:

![Bangalore Itinerary](https://github.com/13Ananya/Travel-Itinerary-Planner/blob/main/Travel%20Iternary%20Planner/Outputs/Bangalore.png)


## 🤔 How It Works

1. **User Inputs**: The user provides the city and their interests through Gradio’s interactive interface. 💬
2. **Processing**: The `input_city` and `input_interests` functions update the internal state of the application. ⚙️
3. **AI Model**: The AI model uses the Langchain framework to generate an itinerary based on the inputs. 🤖
4. **Output**: The AI-generated itinerary is displayed to the user in a clear, concise format. 📝

## 🚀 Future Enhancements

- 🌐 Add support for multi-day itineraries.
- 📅 Integrate external APIs for real-time information like opening hours and location data.
- 🔧 Allow the user to customize the number of activities or duration of each event.

## 📝 License

This project is licensed under the MIT License. 🏷️

