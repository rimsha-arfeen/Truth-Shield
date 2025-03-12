🔍** Truth Shield - Spam & Misinformation Detector**


Project Overview
Truth Shield is a spam and misinformation detection system that helps users identify spam messages, fact-check statements, and verify sources such as email and phone numbers. The system is built using Python, NLP (Natural Language Processing), Machine Learning, and Web Scraping techniques to ensure reliable detection of fraudulent or misleading content.

Key Features
Spam Detection

Uses Naïve Bayes classification to detect spam messages.
Analyzes the text input and categorizes it as SPAM or NOT SPAM based on learned patterns.
Fact Checking

Uses Google Fact Check API to verify if a given message contains false or misleading information.
Returns fact-check results to indicate whether the statement is verified, disputed, or not found.
Source Verification

Checks the authenticity of an email address by querying emailrep.io.
Verifies a phone number using the Numverify API to determine its validity.
Misinformation Highlighting

Identifies misleading or suspicious keywords (e.g., "fraud," "scam," "fake") in messages.
Highlights these words to make users aware of potential misinformation.
Related Content Search

Fetches relevant articles and scam alerts from DuckDuckGo to provide context on possible frauds or hoaxes.
Technology Stack
Programming Language: Python
Libraries & Tools:
scikit-learn (Machine Learning)
nltk (Natural Language Processing)
BeautifulSoup (Web Scraping)
requests (API Communication)
pandas (Data Handling)
Gradio (User Interface)
How It Works
User Inputs a message, email, and/or phone number.
The spam detection model analyzes the message.
The fact-checking API searches for verification results.
The email & phone verification APIs check source authenticity.
The DuckDuckGo search retrieves related content for further information.
The system displays results to help the user determine if the content is legitimate.
Use Cases
Preventing fraud & phishing attacks by detecting suspicious messages.
Helping journalists & researchers fact-check claims before publication.
Assisting general users in verifying the authenticity of received emails and messages
