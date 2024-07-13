 * Challenge:
 * 1. Ask OpenAI to explain something complicated 
 *    to you. For example Quantum Computing.
 * 
 * Prompt Engineering Stretch Goals
 * - See if you can control the level of complexity of 
 *   the generated content, for example is this for 
 *   10-year-olds or college kids?
 * - See if you can control the length of the output.
 * 

1. You will need to set up a new instance of OpenAI and remember to set dangerouslyAllowBrowser.

2. You will need to call the chat.completions.create endpoint and pass in an array of messages and a model.

3. The array of messages needs two objects, both with 'role' and 'content' keys. The 'system' object should hold an instruction. The 'user' object should hold the data that is coming in to fetchReport as a parameter. 

4. You might have to experiment with the instructions you give the model to get a report you are happy with. For now, don't worry too much about the quality of the report as we will do some tweaking later. 

5. Call renderReport with the text you get back from the OpenAI API.

6. For bonus points, use a try catch to handle errors.


![stock_ai_app](https://github.com/user-attachments/assets/80402054-ec66-4867-a847-156dc0dcd74f)
# stock-predicition-ai-app
