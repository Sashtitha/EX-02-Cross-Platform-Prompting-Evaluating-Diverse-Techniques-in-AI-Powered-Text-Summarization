# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:

Application Area: Customer Support Chatbots

An online shopping company uses an AI-powered customer support chatbot to handle customer queries related to orders, deliveries, refunds, and order tracking.

A customer contacts the chatbot because their parcel has been delayed by three days due to severe weather conditions.

The chatbot must understand the customer's problem, explain the reason for the delay, show empathy and apologize, provide useful options to the customer, maintain a professional tone, avoid making unsupported promises, follow the required response format, and produce a concise response of fewer than 150 words.

## PROBLEM STATEMENT

Design an effective prompt for an LLM-based customer support chatbot that can generate a professional, empathetic, accurate, structured, and actionable response to a customer whose order has been delayed.

The prompt should be progressively improved using the following techniques:

Basic Prompt → Role Prompt → Context Prompt → Constraint Prompt → Output Format Prompt → Optimized Prompt

## ALGORITHM

Start the customer support chatbot system.

Define the customer support problem.

The customer's parcel is delayed by three days due to severe weather.

Create a Basic Prompt that specifies only the task.

Generate the LLM response and record the output.

Add a Role Prompt by defining the AI as an experienced customer support executive.

Generate and record the improved response.

Add Context containing specific information about the customer's situation.

Generate the contextual response.

Add Constraints such as maximum word limit, professional tone, empathetic language, and avoidance of unsupported promises.

Generate the constrained response.

Add an Output Format specifying the required response structure.

Generate the structured response.

Combine all prompting techniques into a single Optimized Prompt.

Generate the final response.

Evaluate each response using relevance, accuracy, empathy, completeness, constraint compliance, format compliance, and actionability.

Compare the evaluation results using a comparison matrix.

Identify the prompt that produces the highest-quality response.

Draw the final conclusion based on the evaluation.

Stop.

## ALGORITHM FLOW

START

↓

Define Customer Support Problem

↓

Create Basic Prompt

↓

Generate Output

↓

Add Role

↓

Generate Output

↓

Add Context

↓

Generate Output

↓

Add Constraints

↓

Generate Output

↓

Add Output Format

↓

Generate Output

↓

Create Optimized Prompt

↓

Generate Final Output

↓

Evaluate All Outputs

↓

Compare Results

↓

Select Best Prompt

↓

Conclusion

↓

STOP

## INPUT

Customer Query:

"My package was supposed to arrive three days ago, but I still haven't received it. What happened?"

Known Information:

Issue: Delayed delivery

Delay: Three days

Reason: Severe weather

Customer requirement: Explanation and solution

Desired tone: Professional and empathetic

Maximum length: 150 words

Required format: Structured response

## BASIC PROMPT

Prompt:

"Answer a customer's question about a delayed order."

Output:

"We apologize for the delay in your order. Your package may have been delayed due to unforeseen circumstances. Please check your order tracking information for the latest update. If you need further assistance, please contact customer support."

Observation:

The response is relevant but generic. It does not contain specific information about the customer's situation, reason for the delay, or clearly defined solutions.

## ROLE PROMPT

Prompt:

"You are an experienced Customer Support Executive. Help a customer whose order is delayed."

Output:

"Hello,

We sincerely apologize for the delay in delivering your order. We understand how important it is to receive your package on time. Please check your order tracking information for the latest delivery status. If the package remains delayed, our support team can assist you with further options.

Thank you for your patience and understanding."

Observation:

The response becomes more professional and customer-oriented because the AI has been assigned a specific role.

## CONTEXT PROMPT

Prompt:

"You are a Customer Support Executive. The customer's parcel is delayed by three days due to severe weather. Explain the situation politely and offer solutions."

Output:

"Hello,

We sincerely apologize for the three-day delay in delivering your parcel. Severe weather conditions have affected transportation and caused delays in the delivery process. We understand how inconvenient this may be.

You can continue tracking your parcel using the tracking page. If the delay continues, our support team can assist you with available options.

Thank you for your patience and understanding."

Observation:

The response is more specific because the AI knows the actual reason for the delay. Providing context allows the model to generate a more relevant response.

## CONSTRAINT PROMPT

Prompt:

"Respond in under 150 words using a professional and empathetic tone."

Output:

"Hello,

We sincerely apologize for the three-day delay in delivering your parcel. Severe weather conditions have disrupted transportation and affected the delivery schedule. We understand how frustrating it can be to wait longer than expected for your order.

You can track the latest status of your parcel through the order tracking page. If the delay continues, please contact our support team for additional assistance and available options.

Thank you for your patience and understanding. We appreciate your continued trust in us."

Observation:

The response follows the specified length and maintains a professional and empathetic tone. Constraints provide greater control over the generated response.

## OUTPUT FORMAT PROMPT

Prompt:

"Organise the response into Greeting, Issue Summary, Explanation, Resolution and Closing."

Output:

Greeting:

Hello, and thank you for contacting our customer support team.

Issue Summary:

We understand that your parcel has been delayed by three days.

Explanation:

The delay has occurred because severe weather conditions have disrupted transportation and delivery operations.

Resolution:

You can track your parcel through the order tracking page. If the delivery is delayed further, our support team can help you explore the available options.

Closing:

We sincerely apologize for the inconvenience and appreciate your patience and understanding.

Observation:

The response is highly organized and ensures that all major components are included. Structured output makes the response easier to understand and provides consistency.

## FINAL OPTIMIZED PROMPT

Prompt:

"You are a senior customer support executive for an e-commerce company. A customer's parcel is delayed by three days because of severe weather. Generate a polite and empathetic response in fewer than 150 words. Include a greeting, issue summary, clear explanation of the delay, apology, available options such as tracking the package or contacting support, and a professional closing. Do not make unsupported promises about the delivery date, refund, or compensation."

Final Output:

Greeting:

Hello, and thank you for contacting our customer support team.

Issue Summary:

We understand that your parcel has been delayed by three days.

Explanation:

The delay is due to severe weather conditions that have disrupted transportation and delivery operations.

Resolution:

We sincerely apologize for the inconvenience. You can track the latest status of your parcel through the order tracking page. If you need further assistance, our support team can help you with the available options.

Closing:

Thank you for your patience and understanding. We appreciate your continued trust in us.

## COMPREHENSIVE COMPARISON MATRIX

Criteria | Basic | Role | Context | Constraint | Output Format | Optimized

Task Understanding | Moderate | Good | Excellent | Excellent | Excellent | Excellent

Relevance | Moderate | Good | Excellent | Excellent | Excellent | Excellent

Specificity | Low | Moderate | Excellent | Excellent | Excellent | Excellent

Empathy | Moderate | Good | Good | Excellent | Excellent | Excellent

Professionalism | Moderate | Excellent | Excellent | Excellent | Excellent | Excellent

Completeness | Low | Moderate | Good | Good | Excellent | Excellent

Format Compliance | Low | Low | Low | Moderate | Excellent | Excellent

Actionability | Low | Moderate | Good | Good | Excellent | Excellent

Consistency | Low | Good | Good | Excellent | Excellent | Excellent

Overall Quality | Moderate | Good | Very Good | Excellent | Excellent | Excellent

EVALUATION METRICS

Relevance:

Measures whether the response directly addresses the customer's delayed-order problem.

Accuracy:

Measures whether the response correctly uses the information provided in the prompt without introducing unsupported information.

Empathy:

Measures whether the chatbot acknowledges the customer's inconvenience and communicates respectfully.

Completeness:

Measures whether the response includes the required elements such as greeting, issue summary, explanation, apology, resolution, and closing.

Constraint Compliance:

Measures whether the generated response follows explicit requirements such as word limits, professional tone, empathetic language, and restrictions against unsupported promises.

Format Compliance:

Measures whether the response follows the requested structure.

Actionability:

Measures whether the customer receives useful next steps, such as tracking the parcel or contacting customer support.

Overall Quality:

The overall quality is determined by considering relevance, accuracy, completeness, empathy, constraint compliance, format compliance, and actionability.

## RESULTS

The experiment was successfully completed. The outputs generated using progressively improved prompts showed a clear improvement in relevance, specificity, professionalism, empathy, completeness, consistency, and format compliance.

The Basic Prompt produced a general response with limited context. The Role Prompt improved professionalism and customer-oriented communication. The Context Prompt produced a more specific response. The Constraint Prompt improved control over tone and response length. The Output Format Prompt improved organization and consistency.

The Optimized Prompt produced the most complete response by combining role, context, constraints, output structure, and safety instructions.

## TECHNICAL TAKEAWAYS

Prompt structure directly influences LLM output quality.

Basic prompting defines only the task.

Role prompting controls the behavior and expertise of the model.

Context prompting improves relevance and specificity.

Constraint prompting controls tone, length, and limitations.

Output Format prompting improves consistency and readability.

Optimized prompting combines multiple techniques to produce a controlled and reliable response.

Prompt engineering is an iterative optimization process rather than a one-time instruction.

Detailed prompts reduce ambiguity and help the LLM understand the intended task.

Providing relevant context allows the model to generate situation-specific responses.

Explicit constraints improve controllability and reduce undesirable outputs.

Structured formats ensure that important information is presented systematically.

Prompt engineering does not guarantee factual accuracy, so generated responses should still be evaluated.

Customer support prompts should prevent the chatbot from inventing delivery dates, refund guarantees, or compensation.

Complex or unresolved customer issues should be escalated to a human support representative.

## ETHICAL CONSIDERATIONS

Customer support chatbots should be designed responsibly.

Privacy should be protected and the chatbot should not unnecessarily request sensitive customer information.

The chatbot should avoid generating false or misleading delivery information.

Customers should be informed when they are interacting with an AI system where appropriate.

Responses should be fair and consistent across customers.

Customer information should be securely handled.

Complex issues should be transferred to human customer support when necessary.

The chatbot should not make unsupported promises regarding delivery dates, refunds, compensation, or other company policies.

ADVANTAGES OF THE OPTIMIZED PROMPT

The optimized prompt provides better task understanding, improved relevance, professional communication, consistent tone, controlled response length, structured output, better customer experience, reduced ambiguity, reduced risk of unsupported claims, and easier integration into chatbot systems.

## RESULT

The experiment successfully demonstrated that progressive prompt refinement improves the quality of LLM-generated customer support responses.

The combination of Role, Context, Constraint, Output Format, and safety instructions produced the most effective response.

The final chatbot response was professional, empathetic, concise, structured, relevant, and actionable while avoiding unsupported promises.

## CONCLUSION

Advanced prompt design techniques enable Large Language Models to generate more reliable and useful responses for real-world customer support applications. Starting from a simple Basic Prompt, the addition of Role, Context, Constraints, and Output Format progressively improved the chatbot's response.

The final optimized prompt successfully generated a professional, empathetic, concise, structured, and actionable response while preventing unsupported promises.

Therefore, structured and iterative prompt engineering is an effective approach for developing reliable LLM-powered customer support chatbots.

REFERENCES

Brown et al. (2020). Language Models are Few-Shot Learners.

OpenAI. Prompt Engineering Guide.

Wei et al. (2022). Chain-of-Thought Prompting Elicits Reasoning in Large Language Models.


