🤖 Simple Sentiment Analyzer
This is a very small and basic web-based AI project designed to analyze the sentiment of a given sentence. It's built primarily for beginners learning about web development and GitHub Pages deployment.

✨ Features
Basic Sentiment Analysis: Determines if a sentence is Positive, Negative, or Neutral based on a predefined list of keywords.

Simple User Interface: A clean and intuitive interface for inputting text and displaying results.

Instant Feedback: Provides immediate sentiment analysis upon clicking the "Analyze Sentiment" button or pressing Enter.

Fully Client-Side: All logic runs directly in your browser, with no server-side components.

🚀 How to Use
Open the Application: If deployed on GitHub Pages, simply navigate to the live URL.

Enter Text: Type or paste any sentence into the text area.

Analyze: Click the "Analyze Sentiment" button or press the Enter key.

View Result: The sentiment (Positive, Negative, or Neutral) will be displayed below the button.

💻 Technologies Used
HTML: For the structure of the web page.

Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

JavaScript: For the core sentiment analysis logic and interactive elements.

💡 How It Works (The "AI" Part)
This sentiment analyzer is not powered by complex machine learning models. Instead, it uses a very simple, rule-based approach:

It has predefined lists of common "positive" and "negative" words.

When you enter a sentence, it counts how many positive words and how many negative words are present in your input.

If positive words outnumber negative words, the sentiment is declared Positive.

If negative words outnumber positive words, the sentiment is Negative.

If the counts are equal or no specific sentiment words are found (and the input is not empty), the sentiment is Neutral.

This makes it a great project for understanding basic programming logic and demonstrating client-side web applications.