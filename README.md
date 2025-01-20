# Affective Response Analysis through Event Narration

## Overview
This project is an innovative exploration of emotional responses to interactive storytelling. Using advanced Natural Language Processing (NLP) techniques, it analyzes user feedback on pre-written story events to extract emotional states, intensity, and relevance. The system tracks emotional evolution across sessions, offering valuable insights into user psychology, with applications in therapy, education, and entertainment.

## Key Features

### Emotion Tracking
- Captures and stores emotional responses linked to specific narrative events.
- Covers 13 emotions, including happiness, sadness, anger, and surprise.

### Session Management
- Monitors user emotions over multiple sessions.
- Tracks emotional changes and behavioral trends.

### Relevance Mapping
- Analyzes the alignment of user feedback with narrative events using cosine similarity.

### Dynamic Adaptation
- Provides real-time emotional insights.
- Dynamically adjusts narratives based on user responses.

### Insights Visualization
- Generates graphs and metrics to represent emotional trends, stress levels, and engagement over time.

## Technologies

### NLP Models
- **LSTM**
- **RoBERTa**
- **ALBERTa**
  
These models are utilized for emotion extraction and analysis.

### Database
- A structured schema is used to store:
  - User feedback
  - Emotional responses
  - Session data

### Visualization Tools
- **Matplotlib** for graphical insights into emotional trends and engagement.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/affective-response-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd affective-response-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the database:
   - Configure the database schema as per `schema.sql`.

5. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. Start the application and interact with the story events presented on the interface.
2. Provide feedback during or after each narrative event.
3. Visualize your emotional trends and engagement metrics via the generated insights.
4. Use the system to explore emotional changes across multiple sessions.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For questions or feedback, please contact [Siddhant Sirohi](mailto:siddhantsirohi2@gmail.com).

