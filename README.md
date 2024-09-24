
# Sentiment-Driven Customer Support Chatbot 💬

This application integrates AI and sentiment analysis to serve as an efficient customer service chatbot. Users can submit reviews and receive instant responses, making it ideal for businesses and service providers with a large customer base. By automating customer support, it helps reduce the need for additional support agents, ultimately cutting costs and boosting profitability.

**Technologies Used:**

1. **Hugging Face Pipeline**: Utilized for sentiment analysis to assess the tone of customer reviews before forwarding them to the AI.
2. **Langchain**: Powers the AI that generates the chatbot's responses.
3. **Python**: The entire system is developed using Python.
4. **Gradio**: Provides the chat interface for user interaction.

Users can simply input their review, click the submit button, and receive a tailored response within seconds, driven by the sentiment of their review.







## Tests:
* Positive sentiment test_query
![Positive sentiment test result](https://private-user-images.githubusercontent.com/75625740/370482849-620027c6-f38d-4f2e-8bc1-6393af280aa9.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjcyMTU0NjMsIm5iZiI6MTcyNzIxNTE2MywicGF0aCI6Ii83NTYyNTc0MC8zNzA0ODI4NDktNjIwMDI3YzYtZjM4ZC00ZjJlLThiYzEtNjM5M2FmMjgwYWE5LmpwZWc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyNFQyMTU5MjNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wZWNlYTE1YTdlZmJhZTMwOTFlZTVhNTEwZmM2ZWQ4OTQ3Y2FiODAwNjlmODljYmI4ZmU0ZjZkNGUyMzI4M2RhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.UFT4x_DbG2p_Sa5xpcC5Q9hHYjfE-3H5UAk-SCo6tCI)



* Negative sentiment test_query
![Negative sentiment test result](https://private-user-images.githubusercontent.com/75625740/370483357-812347bf-a383-4b76-97a3-43b4e40a4438.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjcyMTU2MTEsIm5iZiI6MTcyNzIxNTMxMSwicGF0aCI6Ii83NTYyNTc0MC8zNzA0ODMzNTctODEyMzQ3YmYtYTM4My00Yjc2LTk3YTMtNDNiNGU0MGE0NDM4LmpwZWc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyNFQyMjAxNTFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zZDcyN2I0Nzk2MjZmZDUzOWI0OTgxM2NmNGRkZTIwZTY0MzljNjE3MDZmYjIwMGEwMjYzNGMyZDc5YzgwMTA3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.3MA2V0Zhz1yfjv9Odwqw4Fi2DxhmDuRQgTiogBRheEc)
