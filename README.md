# PROJECT PROPOSAL IN COMPUTER SCIENCE 2	

## PROJECT TITLE: 
MindType: An Interactive Personality Exploration and Self-Reflection Program

## PROBLEM:
Teenage years are an important period of personal development, during which individuals begin to form a stronger understanding of who they are, what they value, how they interact with others, and what they prefer. However, teenagers may sometimes find it difficult to understand their own personality, tendencies, and preferences. This uncertainty can lead them to question how well they know themselves and how they relate to the people around them.

Personality tests are one way people can explore these aspects of themselves. However, some personality assessments may present their results in ways that are difficult for teenagers to understand or may simply provide a personality label without encouraging further reflection. There is therefore an opportunity to create a simple and interactive program that allows teenagers to explore their personality preferences in an accessible and engaging way.

To address this, we propose MindType, a personality exploration program inspired by the four personality dimensions commonly associated with the Myers-Briggs Type Indicator (MBTI). The program will present users with a series of age-appropriate questions about their preferences, behaviors, and ways of approaching different situations. Based on their responses, the program will process their answers and determine their preferences across four dimensions: Extraversion–Introversion (E/I), Sensing–Intuition (S/N), Thinking–Feeling (T/F), and Judging–Perceiving (J/P).

The program will then combine these results to generate a four-letter personality type and provide a brief explanation of the user's identified preferences. Rather than presenting the result as a fixed definition of who the user is, the program will encourage users to treat the result as a starting point for self-reflection and exploration.

Through this approach, MindType aims to provide teenagers with a simple, interactive, and accessible way to learn more about their personality preferences and reflect on how these tendencies may relate to their everyday experiences and interactions with others.

## USERS:
The primary target users of MindType are teenagers, particularly those between the ages of 13 and 19. The questions will be designed to be understandable and relatable to their age group and will focus on everyday situations involving social interaction, decision-making, information processing, and personal preferences.

The program is intended to help users explore their personality preferences, recognize possible strengths and tendencies, and reflect on how they interact with other people. It is designed to make personality exploration simple, engaging, and accessible.

Although teenagers are the primary target users, people of other age groups may also use the program if they are interested in exploring their personality preferences.

## OBJECTIVES:
The project aims to:
1.	Develop an interactive personality assessment that allows users to explore their personality preferences through a series of age-appropriate questions.
   
2.	Process and analyze users' responses to determine their preferences across four personality dimensions: Extraversion–Introversion, Sensing–Intuition, Thinking–Feeling, and Judging–Perceiving.
   
3.	Generate a four-letter personality type based on the user's calculated preferences.
   
4.	Provide users with a brief and understandable interpretation of their resulting personality preferences.
   
5.	Encourage self-awareness and self-reflection by allowing users to consider how their identified preferences may relate to their everyday behaviors and interactions.
   
6.	Apply computational thinking, modular programming, selection structures, data processing, input validation, and appropriate programming libraries in the development of the program.
    
## FEATURES:
1. Introduction and Instructions
The program will begin with an introduction explaining the purpose of MindType and instructions on how to answer the questions. It will also clarify that the result is intended for self-exploration and should not be treated as a definitive description or diagnosis of a person's identity.

2. Interactive Personality Questionnaire
Users will answer a series of multiple-choice questions based on common everyday situations and preferences. The questions will be written to be relatable to teenagers.

The questions will assess four personality dimensions:
•	Extraversion (E) / Introversion (I)
•	Sensing (S) / Intuition (N)
•	Thinking (T) / Feeling (F)
•	Judging (J) / Perceiving (P)

3. Input Validation
The program will check whether the user's input is valid before continuing to the next question. Invalid inputs include letters that are not included in the options, numbers, more than one letter, and other elements other than capital or small letter A and B. Invalid inputs will prompt the user to enter an acceptable response again.

This will prevent incorrect or unexpected inputs from affecting the calculated result.

4. Response and Score Storage
The program will temporarily store the user's responses and corresponding scores using appropriate variables and data structures.

The stored information will allow the program to process the user's responses after the questionnaire has been completed.

5. Personality Score Calculation
The program will count and compare the user's responses for each personality dimension.
For example:
•	E compared with I
•	S compared with N
•	T compared with F
•	J compared with P

The higher score in each pair will determine the user's preference for that dimension.

6. Personality Type Generation
The program will combine the four determined preferences into a four-letter personality type.
For example:
E + N + F + P = ENFP
The program will generate the appropriate combination automatically based on the user's responses.

7. Personality Result
After completing the questionnaire, the program will display:
•	The user's four-letter personality type
•	Their results for each personality dimension
•	A brief explanation of their identified preferences
•	Possible strengths or tendencies associated with the result
•	Reflection prompts that encourage users to think about whether the description relates to their own experience

8. Restart or Retake Function
The program may allow users to restart the questionnaire and take the assessment again. This will allow users to explore how different answers can affect their resulting personality preferences.

## INPUT, PROCESSING, AND OUTPUT
INPUT
The primary inputs of the program will be the user's preferred name or nickname for personalization and answers to the personality questionnaire.

PROCESSING
The program will:
1.	Receive and validate the user's answers.
2.	Store the responses.
3.	Assign corresponding scores to each personality dimension.
4.	Calculate the total score for each side of the four dimensions.
5.	Compare the scores within each dimension.
6.	Determine the user's four personality preferences.
7.	Combine the preferences into a four-letter personality type.
8.	Retrieve the corresponding personality description.
   
OUTPUT
The program will display:
•	The user's personality type
•	Their four personality preferences
•	A brief personality description
•	Possible strengths and tendencies
•	Self-reflection prompts

## DATA PROCESSING FLOW
The proposed flow of the program is:
User → Questions → Answers → Input Validation → Response Storage → Score Calculation → Personality Dimension Comparison → Four-Letter Type → Personality Interpretation → Output
This structure allows the program to demonstrate the data processing steps of collection, input, processing, and output.

## LOGIC PLAN 
Flowchart:
<img width="2801" height="1062" alt="CS2 drawio" src="https://github.com/user-attachments/assets/64783944-b145-46c7-b067-ae9ec720f441" />

Pseudocode:

## SCOPE AND LIMITATIONS
MindType will focus on personality preferences represented through the four MBTI-inspired dimensions. It will not attempt to diagnose mental health conditions, determine a user's psychological state, or provide professional psychological advice.
The program's results will depend on the user's responses to the questions. Since personality is complex and can vary depending on circumstances, the generated personality type should be treated as an exploratory result rather than a permanent or complete representation of the user.

The initial version of the program will focus on a text-based interactive assessment and its corresponding results.

## DEVELOPMENT CONSIDERATIONS
The project will apply concepts learned in Computer Science 2, including:
•	Data collection and processing
•	Variables and data structures
•	Modular programming using functions
•	Selection structures
•	Input validation
•	String processing
•	Appropriate programming libraries and methods
•	Debugging and testing
•	Code documentation
•	Version control using GitHub

The team will also provide appropriate citations for external sources used for the personality descriptions, questions, or other creative and technical content.

## CONCLUSION
MindType is proposed as an interactive personality exploration program designed primarily for teenagers. By combining an accessible questionnaire with automated data processing and personalized results, the program aims to provide users with a simple way to explore their personality preferences and encourage self-awareness.

The project also provides an opportunity to apply the programming concepts and computational thinking skills required in Computer Science 2 through the development of a practical, user-centered program.



