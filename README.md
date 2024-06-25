# TextAnalysis
Text Analysis using R

Existing sentiment analysis tools often provide a surface-level understanding of emotions in text data. They typically categorize sentiment as positive, negative, or neutral, failing to capture the richness of human expression. This project aims to bridge this gap by developing a more nuanced sentiment analysis system. Our system will move beyond basic classifications and identify specific emotions such as frustration, joy, or sarcasm. This deeper emotional intelligence will unlock valuable insights across various applications. From improved customer service that addresses underlying frustrations to insightful social media listening that captures audience sentiment beyond basic positivity or negativity, our refined sentiment analysis system holds the potential to revolutionize how we interact with and understand the world around us. 

The proposed solution entails the development of a user-friendly Shiny application using R programming for text analysis tasks. This application offers an interactive dashboard interface, organized with a header, sidebar, and body sections using the shinydashboard package. Users can conveniently upload text files in .txt or .pdf formats or input text directly into a designated text area within the dashboard. Through reactive expressions, the application dynamically retrieves and processes the text data, enabling real-time updates based on user inputs. Core functionalities include generating visualizations such as bar plots for the top 10 most common words, word clouds depicting word frequencies, and sentiment analysis plots categorizing text sentiments. Additionally, the application provides an output indicating the most prevalent emotion identified in the text data along with an associated emoji. A clear button is incorporated to reset the session, facilitating a seamless user experience by allowing users to input fresh text for analysis.

The aim of the proposed solution is to provide users with an intuitive and efficient tool for conducting text analysis tasks. By leveraging the power of Shiny and R, users can effortlessly explore and derive insights from textual data, empowering them to make informed decisions and gain valuable insights from their data

Technology Used
Shiny, shinydashboard, tidyverse, wordcloud, RColorBrewer, pdftools, plotly

## Output:

Dashboard:

![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/HomePage.png?raw=true)

Method 1: Text Analysis using uploaded file
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method1/mostCommonWord.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method1/wordCloud.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method1/sentimentAnalysis.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method1/emotionEmoji.png?raw=true)

Method 2: Text Analysis using textbox
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method2/mostCommonWord.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method2/wordCloud.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method2/sentimentAnalysis.png?raw=true)
![alt text](https://github.com/chaitali-gaikwad/TextAnalysis/blob/main/Output/Method2/emotionEmoji.png?raw=true)
