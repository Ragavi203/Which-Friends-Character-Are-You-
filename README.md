# Which Friends Character Are You? 🎭

Discover which iconic *Friends* character matches your personality! This Python-based web app, built with **Streamlit**, delivers a fun and interactive personality quiz inspired by the legendary sitcom *Friends*. Are you sarcastic Chandler, perfectionist Monica, or quirky Phoebe? Let the quiz decide!

---

## Features

- **Interactive Quiz:** Answer six fun and engaging questions to reveal your *Friends* character.
- **Dynamic Scoring:** The app evaluates your choices to match you with Chandler, Monica, Joey, Ross, Rachel, or Phoebe.
- **Custom Results Page:** Displays character traits, scores, and a personalized message.
- **Streamlit Interface:** A clean and user-friendly layout for seamless interaction.
- **Easy Sharing:** Hosted using **pyngrok**, allowing you to share your quiz with anyone instantly.

---

## How It Works

1. **Launch the App:** The app runs on Streamlit, creating an interactive quiz interface.
2. **Answer Questions:** Select options that resonate with you for each of the six questions.
3. **Get Results:** The app calculates scores dynamically and reveals your *Friends* character match with traits and scores.

### Sample Questions:
- What would you do at a party?
- How do you handle stress?
- What’s your idea of a perfect weekend?

---

## Technology Stack

- **Python**: Core programming language.
- **Streamlit**: For building the interactive front-end.
- **pyngrok**: For creating a public URL to share the app.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/friends-quiz.git
   cd friends-quiz
   ```
2. Install dependencies:
   ```bash
   pip install streamlit pyngrok
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```
4. Share your app using pyngrok:
   ```python
   from pyngrok import ngrok
   public_url = ngrok.connect(8501)
   print(f"Your app is live at: {public_url}")
   ```

---

## Future Enhancements

- **Additional Characters:** Expand the quiz to include characters from other popular shows.
- **Media Integration:** Add images, gifs, or videos to enhance the visual experience.
- **Advanced Scoring:** Introduce weighted scores for more nuanced results.
- **Multiplayer Mode:** Compare results with friends in real-time.
- **Permanent Hosting:** Deploy the app to a cloud service like Heroku or AWS.

---

## Contributing

Feel free to submit pull requests or suggest features. Collaboration is welcome!

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---


https://colab.research.google.com/drive/137vyp-0sQBIL7LZYsC6HAIgGAls2rvey?usp=sharing

## Try It Out!

Ready to find your *Friends* character? Explore the app and share your results!


