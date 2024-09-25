# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.


## Exporter Service
User interacts with the component to choose an export option (PDF, DOC, XLS, etc.).

Renderer: [https://github.com/diegomura/react-pdf#readme] Documentation: [https://react-pdf.org/]



# The Emotional AI Project
Developmental Project by MO Cavada
## Overview

The "Emotional AI" project aims to create a comprehensive platform for introspection and emotional analysis. The project is structured to serve multiple purposes, including acting as an API server, providing an admin UI for data management and analysis, and planning for future expansion to include a cross-platform app using React Native.

## Prototypes on Developmemt

* [Dataset Analyzer with LLM](https://www.kentoverse.com)

* [Cross-platform Chat App React to React-Native](https://www.botski.info)

* UX/UI Design: [ Figma Wireframe ](https://www.figma.com/design/AcpskXz9xS0Y0qE7zngR9E/Untitled?node-id=0-1&t=pTsE8FtQNqlHFVqZ-1)


**Important Note: Emotional AI stands for Emotional Authentic Intelligence. We are not building an AI that mimics human emotions, which is impossible. Instead, our focus is on creating tools that help users introspect and understand their own emotions and interactions authentically.**

These 3 constants are:

1. **Change (Moment of Interaction)**: This constant highlights the dynamic nature of relationships, emphasizing the importance of actions (Act), reactions (React), and attractions (Attract) in shaping human connections.

2. **Power (Influence and Effect from Interactions)**: This constant delves into the forms of power that influence relationships, including negative/destructive power, positive/creative power, and neutral/equilibrium. Understanding these forces helps in navigating the complexities of emotional interactions.

3. **Moments (Timeline Connections of Influence and Effect)**: This constant focuses on the temporal aspects of relationships, stressing the significance of past reflections, future insights, and present awareness. By introspecting on these moments, individuals can gain deeper insights into their interactions and connections.


## Purpose and Alignment to Technology

To create an app that guides users through introspection using “The 3 Constants of Human Connection.” This app will teach users how to understand their interactions, the influences of these interactions, and the underlying causes rooted in our past and present experiences can define potential outcomes in our future.


## Reflection App, the following design patterns would align most closely:

1.	In-context Learning – Since the app provides personalized reflections based on user inputs, AI-generated content, and spiritual insights, this aligns with in-context learning. The model adapts to the user’s input to provide emotionally attuned and spiritually relevant guidance, akin to personalized AI responses.

2.	Data Preprocessing / Embedding – The Reflection App likely uses data preprocessing to convert user inputs into a form that can be embedded for further processing by the AI model. This embedding allows the app to analyze the emotional and spiritual content of journaling entries, enhancing the personalized nature of the insights.

3.	Prompt Construction / Retrieval – In generating AI-powered reflections and insights, the app would involve constructing prompts based on user data and retrieving relevant Bible verses or spiritual content. The alignment with Sentiment Analysis also suggests that the prompts are crafted to be contextually relevant to the user’s emotional state.

4.	Prompt Execution / Inference – The AI model (e.g., ChatGPT or other language models) takes the constructed prompts and executes them to generate personalized insights. This is core to delivering reflections based on the user’s journaling and ensuring that they are emotionally and spiritually attuned.

## The Introspection Process

1. **Analyze the Interplay of Interactions**: This step focuses on understanding the initial interactions that stem from our inherent need to connect with others.
2. **Visualize the Effect of Interactions**: This step examines the effects that attract and influence future interactions based on our initial connections.
3. **Understand the Connection between Interactions and Past**: This step delves into how past experiences and memories influence our current interactions and connections.

## Application of Emotional AI

The AI component of the app will assist users in:

- **Analyzing their interactions (Act, React, Attract)**
- **Visualizing the influences of these interactions (Negative, Positive, Balanced)**
- **Understanding on past experiences, forecasting future outcomes, and maintaining present awareness**

The book premise aligns with our goal to create an introspective guide and incorporate Emotional AI to support users in understanding and improving their connections that foster healthier and meaningful relationships.

https://www.ibm.com/docs/en).

# Emotional AI and Introspection App Integration

## 1. User Interaction and Data Collection

### Chatbot and Conversation Interface (OpenAI GPT-3/4)

- **User Inputs**: Use OpenAI’s GPT-3/4 to manage user interactions through chat. This can include handling user queries, providing conversational responses, and engaging in empathetic dialogue.
- **Journaling and Logging**: Enable users to write journal entries or log their moods using natural language inputs. GPT-3/4 can help make this process smoother by suggesting prompts and assisting with text entry.

## 2. Emotion and Sentiment Analysis

### Analysis with IBM InspectorRAGet

- **Text Analysis**: Once user inputs are collected, send the text data to IBM InspectorRAGet for detailed sentiment and emotion analysis. This tool can provide insights into the user’s emotional state by analyzing the language used.
- **Real-Time Feedback**: Implement real-time analysis where user inputs are immediately processed by IBM InspectorRAGet to provide instant feedback or suggestions based on the detected emotions.

## 3. Integration Workflow

### Step-by-Step Process

1. **User Interaction**:
   - Users interact with the app via chat or journaling features powered by GPT-3/4.
   - GPT-3/4 handles the conversation flow and assists users in expressing their thoughts and emotions.
2. **Data Transfer**:
   - User-generated text is sent to IBM InspectorRAGet for emotion and sentiment analysis.
   - InspectorRAGet processes the text and returns a detailed emotional analysis.
3. **Emotional Insights**:
   - The emotional analysis from InspectorRAGet is integrated back into the app.
   - Insights are displayed to the user, providing a summary of their emotional state and any identified patterns.
4. **Personalized Responses**:
   - Based on the emotional insights, GPT-3/4 generates personalized responses, suggestions, and content recommendations.
   - The app can suggest activities, articles, or coping strategies tailored to the user’s current emotional state.

## 4. Personalized Content Recommendations

- **Content Delivery**: Use the emotional analysis to tailor content recommendations. If InspectorRAGet detects stress, GPT-3/4 can suggest relaxation techniques, mindfulness exercises, or supportive articles.
- **Adaptive Learning**: Continuously refine content suggestions based on user feedback and ongoing emotional analysis.

## 5. Visualization and Reporting

- **Emotional Insights Dashboard**: Create visual reports and dashboards that display the emotional analysis over time. Users can track their emotional journey and identify patterns or triggers.
- **Progress Tracking**: Allow users to see how their emotional health evolves, with insights generated by IBM InspectorRAGet and narrative summaries by GPT-3/4.

## 6. Backend Integration

- **Data Pipeline**: Establish a secure and efficient data pipeline to transfer user inputs from the frontend (GPT-3/4) to the backend (InspectorRAGet) for analysis.
- **Scalability**: Ensure the system can handle large volumes of data and provide real-time analysis and feedback.

## 7. Security and Privacy

- **Data Encryption**: Implement robust encryption methods to protect user data during transmission and storage.
- **User Consent**: Ensure users are informed about how their data will be used and obtain their consent for emotional analysis.

## Technical Implementation

```python
import openai
import ibm_inspector_raget

# Initialize OpenAI GPT-3/4
openai.api_key = 'your_openai_api_key'

# Function to handle user input and generate response
def handle_user_input(user_input):
    # Generate response using GPT-3/4
    gpt_response = openai.Completion.create(
        engine="davinci",
        prompt=user_input,
        max_tokens=150
    )
    return gpt_response.choices[0].text.strip()

# Function to analyze emotion using IBM InspectorRAGet
def analyze_emotion(text):
    emotion_analysis = ibm_inspector_raget.analyze_text(text)
    return emotion_analysis

# Main interaction function
def main():
    user_input = input("Enter your thoughts: ")
    gpt_response = handle_user_input(user_input)
    emotion_analysis = analyze_emotion(user_input)
    
    print("GPT-3/4 Response:", gpt_response)
    print("Emotion Analysis:", emotion_analysis)

if __name__ == "__main__":
    main()

```
## Benefits

- **Separation of Concerns:** Keeping the admin UI and the public-facing UI separate allows for tailored interfaces for each audience without unnecessary complexity.
- **Scalability:** The backend API can serve multiple clients (admin UI, public web app, mobile app), making the architecture scalable.
- **Flexibility:** Different UI libraries can be used for different parts of the project, providing flexibility in tool choice.
- **Maintainability:** Separation of the admin and public interfaces makes the codebase easier to maintain and update.




## Entities and Relationships

### 1. Users: Stores user information.
- **UserID** (Primary Key)
- **Name**
- **Email**
- **Password**
- **ProfilePicture**
- **UserType** (Owner/Walker)

### 2. Interactions: Records the interactions between users.
- **InteractionID** (Primary Key)
- **UserID** (Foreign Key to Users)
- **InteractionType** (Act, React, Attract)
- **InteractionContent**
- **Timestamp**

### 3. Effects: Logs the effects of each interaction.
- **EffectID** (Primary Key)
- **InteractionID** (Foreign Key to Interactions)
- **EffectType** (Negative, Positive, Neutral)
- **EffectDescription**
- **ImpactLevel**

### 4. Moments: Captures reflections, insights, and present awareness.
- **MomentID** (Primary Key)
- **UserID** (Foreign Key to Users)
- **MomentType** (Past Reflection, Future Insight, Present Awareness)
- **Description**
- **Timestamp**

### 5. Relationships: Stores connections between users.
- **RelationshipID** (Primary Key)
- **UserID1** (Foreign Key to Users)
- **UserID2** (Foreign Key to Users)
- **RelationshipStatus**
- **StartDate**

## Entity Relationship Diagram (ERD)

- **Users (1) to Interactions (N)**: A user can have multiple interactions.
- **Interactions (1) to Effects (1)**: Each interaction has one effect.
- **Users (1) to Moments (N)**: A user can have multiple moments.
- **Users (1) to Relationships (N)** with themselves through UserID1 and UserID2: A user can have multiple relationships with other users.

## SQL Schema Example

```sql
CREATE TABLE Users (
    UserID INT PRIMARY KEY AUTO_INCREMENT,
    Name VARCHAR(100) NOT NULL,
    Email VARCHAR(100) NOT NULL UNIQUE,
    Password VARCHAR(255) NOT NULL,
    ProfilePicture VARCHAR(255),
    UserType ENUM('Owner', 'Walker') NOT NULL
);

CREATE TABLE Interactions (
    InteractionID INT PRIMARY KEY AUTO_INCREMENT,
    UserID INT,
    InteractionType ENUM('Act​⬤


```

## Steps to Generate an Generate an Entity Relationship Diagram (ERD) Diagram Locally

### 1. Install Required Libraries
Ensure you have Python installed, and then install the necessary libraries:
```bash
pip install sqlalchemy eralchemy

### 2. Create a Python Script : Save the following code into a Python file, e.g., generate_erd.py:


from sqlalchemy import create_engine, Column, Integer, String, Enum, ForeignKey, Text, DateTime
from sqlalchemy.ext.declarative import declarative_base
from sqlalchemy.orm import relationship
from eralchemy import render_er

Base = declarative_base()

class User(Base):
    __tablename__ = 'Users'
    UserID = Column(Integer, primary_key=True, autoincrement=True)
    Name = Column(String(100), nullable=False)
    Email = Column(String(100), nullable=False, unique=True)
    Password = Column(String(255), nullable=False)
    ProfilePicture = Column(String(255))
    UserType = Column(Enum('Owner', 'Walker'), nullable=False)

class Interaction(Base):
    __tablename__ = 'Interactions'
    InteractionID = Column(Integer, primary_key=True, autoincrement=True)
    UserID = Column(Integer, ForeignKey('Users.UserID'))
    InteractionType = Column(Enum('Act', 'React', 'Attract'), nullable=False)
    InteractionContent = Column(Text, nullable=False)
    Timestamp = Column(DateTime, nullable=False)
    user = relationship("User", back_populates="interactions")

class Effect(Base):
    __tablename__ = 'Effects'
    EffectID = Column(Integer, primary_key=True, autoincrement=True)
    InteractionID = Column(Integer, ForeignKey('Interactions.InteractionID'))
    EffectType = Column(Enum('Negative', 'Positive', 'Neutral'), nullable=False)
    EffectDescription = Column(Text, nullable=False)
    ImpactLevel = Column(Integer, nullable=False)
    interaction = relationship("Interaction", back_populates="effects")

class Moment(Base):
    __tablename__ = 'Moments'
    MomentID = Column(Integer, primary_key=True, autoincrement=True)
    UserID = Column(Integer, ForeignKey('Users.UserID'))
    MomentType = Column(Enum('Past Reflection', 'Future Insight', 'Present Awareness'), nullable=False)
    Description = Column(Text, nullable=False)
    Timestamp = Column(DateTime, nullable=False)
    user = relationship("User", back_populates="moments")

class Relationship(Base):
    __tablename__ = 'Relationships'
    RelationshipID = Column(Integer, primary_key=True, autoincrement=True)
    UserID1 = Column(Integer, ForeignKey('Users.UserID'))
    UserID2 = Column(Integer, ForeignKey('Users.UserID'))
    RelationshipStatus = Column(String(50), nullable=False)
    StartDate = Column(DateTime, nullable=False)
    user1 = relationship("User", foreign_keys=[UserID1])
    user2 = relationship("User", foreign_keys=[UserID2])

User.interactions = relationship("Interaction", order_by=Interaction.InteractionID, back_populates="user")
User.moments = relationship("Moment", order_by=Moment.MomentID, back_populates="user")
Interaction.effects = relationship("Effect", order_by=Effect.EffectID, back_populates="interaction")

# Creating the SQLite engine
engine = create_engine('sqlite:///:memory:')
Base.metadata.create_all(engine)

# Generating the ER diagram
render_er(Base, 'ERD_diagram.png')

# Generating the ER diagram
render_er(Base, 'ERD_diagram.png')

### 3. Run the Script, Execute the script to generate the ERD diagram

```python generate_erd.py


This markdown text provides a comprehensive guide for setting up and generating an ERD diagram locally using Python and the required libraries.


###4 # Steps to Generate an ERD Diagram Locally

## 1. Install Required Libraries
Ensure you have Python installed, and then install the necessary libraries:
```bash
pip install sqlalchemy eralchemy

## Documentation

### Entity Relationship Diagram (ERD)

![ERD Diagram](docs/erd/ERD_diagram.png)



## Project Structure

### Current Components

1. **API Server and Admin UI:**

### API Server 
- The current `emotional AI` app serves as the backend API server, providing endpoints for data management, user authentication, and other necessary backend services.
### Admin UI

- This application includes an admin UI for managing and analyzing data, built using the `@carbon/themes` library.
-  Build the admin interface using `@carbon/themes` within the same application.
- Implement features for data management and analysis accessible only to authorized admin users.


### Directory Structure

```plaintext
emotional-AI/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── Dockerfile
│   └── ...
├── admin-ui/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── Dockerfile
│   └── ...
├── public-web-app/
│   ├── src/
│   ├── public/
i;'/
veloper.mozilla.org/en-US/docs/Web/API/Web_components)
- Anothe option to consider is the Micro Frontend Architecture with Module Federation to manage dependencies. 

### 2. Mobile App (User)
   - A cross-platform mobile app will be developed using frameworks such as React Native or Flutter, ensuring optimized mobile experiences for public users.

* Test UI Prototype: - [IntroSpirit](https://www.botski.info)






### Simplified Explanation: In-Context Learning

**In-context learning** is a method for using large language models (LLMs), like GPT-4, without needing to fine-tune or retrain them. Instead of modifying the model itself, we control its behavior by giving it specific "context" through prompts. This makes it easy to use while keeping the process efficient.

### Example of In-Context Learning:
Imagine you’re building a chatbot to answer questions about legal documents. A simple approach might be to paste all the documents into the prompt and then ask a question. While this could work for small documents, it doesn't work well when you have a large dataset. For instance, GPT-4 has a limit on how much text it can process at once (about 50 pages). If you exceed that, the model performs worse and takes longer.

**In-context learning** fixes this by sending only the most relevant documents to the LLM, instead of dumping everything. The LLM then uses those relevant documents to answer the question effectively.

### How It Works:
1. **Data Preparation/Embedding**: 
   - First, your documents (like legal files) are broken into chunks and processed into a format the model can understand, called "embeddings."
   - These chunks are stored in a special database, called a **vector database**, which is designed to find and retrieve similar or relevant documents quickly.

2. **Prompt Construction/Retrieval**:
   - When the user asks a question (like a legal query), the system finds the most relevant chunks of text from the vector database.
   - A prompt is then created by combining a pre-defined template, some example outputs, and the relevant documents.

3. **Prompt Execution**:
   - This constructed prompt is sent to the LLM (such as GPT-4), which processes the information and gives an answer. Developers often include extra features like logging (keeping track of requests) and caching (saving previous results to avoid reprocessing) to make this step more efficient.

### Why Is This Useful?
- **No Need for Fine-Tuning**: Instead of retraining the LLM on new data (which can be costly and time-consuming), you only need to manage the data and how it's fed into the model.
- **Cost-Effective**: Training an LLM requires significant computing power, but with in-context learning, you're simply working with prompts and databases, which most companies already know how to handle.

### Common Questions:
- **Can we just increase the model’s context window (its ability to process more text at once)?**
   - While possible, it gets expensive very quickly. For example, asking GPT-4 a question over 10,000 pages could cost hundreds of dollars, making it impractical for most use cases.

In summary, **in-context learning** is a clever and efficient way to use LLMs by focusing on managing data and prompts, rather than training or modifying the models themselves.

# Emotional AI Book and The 3 Constants of Human Connection

Authored by Botski, the soon-to-be-published book “Emotional AI” explores human connections through the dual lenses of artificial intelligence and introspection. Drawing from transformative moments in his life, Botski identifies patterns that, when connected, form a coherent framework that can be processed through a single system. For instance, questions about a relationship’s past interactions can be passed through an algorithm to produce insightful answers. He hypothesizes that this framework, combined with inherent human attributes or constants, can address the increasing disconnections in human bonding. Having experienced this crisis himself, Botski is now dedicated to improving relationships by helping individuals reconnect with their innate ability to balance emotions, leading to clarity of mind, self-awareness, broader insights, and deeper introspection. His explorative work has culminated in a theory, “The 3 Constants of Human Connection,” which forms the basis of the book and outlines the fundamental elements governing human interactions and relationships.

The book premise aligns with the goal to create an introspective guide and integrated with AI's latest capabilities to support users in understanding and improving their connections.

