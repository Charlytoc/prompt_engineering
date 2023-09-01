<style>
h1 {
    color: #58d5c4;
}

p {
    color: rgba(181, 181, 181, 0.384);
}

b,
strong {
    color: rgb(50, 113, 147);
}
h2,h3,h4,h5,h6 {
    color: red !important;
}
</style>


# Professional prompting guide


When developing a prompt for a language model, it's important to be as clear and specific as possible. Here are some steps you can follow:


## Prompt principles
A prompt can be as simple as a single letter, it can also generate a response from the LLM. This principles are widely recommended when developing a good prompt.

​1. **Define the Task Clearly**: Start by clearly defining what you want the model to do. This could be anything from writing a paragraph on a specific topic, generating a list of ideas, or answering a question.

​2. **Be Specific**: The more specific your prompt, the better the model will be able to understand what you're asking for. For example, instead of asking the model to "write a story," you might ask it to "write a short story about a young girl who discovers she has magical powers."

3.**Provide Context**: If necessary, provide some context to help the model understand the task. For example, if you're asking the model to continue a story you've started, make sure to include the beginning of the story in the prompt.

​4.**Use the Right Language**: Language models are trained on a wide variety of texts, so they can understand many different styles and tones. However, they tend to respond best to prompts that are written in a clear, straightforward style.\

​5. **Test and Refine**: Finally, remember that developing a good prompt often involves some trial and error. Don't be afraid to test out different prompts and refine them based on the results.

Remember, the goal is to write an instruction that the model can understand and respond to effectively. With a bit of practice, you'll be able to develop prompts that get the results you're looking for.

## Prompt Variables

In a language model, prompts can have various types of variables that affect the final result. Here are some examples:

​**1. Format instruction:** This is not a dinamic variable, its static, it is the shape of the desired response, how it would looks like. It can be an statement inside the prompt that can be used in different prompts, for example: markdown, json, a certain object structure.

**2. Response length:** These variables can be used to set the number of words or the number of times something repeats in the desired text structure. For example, you can specify that the model should generate a paragraph with exactly 100 words or repeat a certain phrase three times.


**​3. Character:** Language models can analyze words and extract meaning from them. They can also interpret a certain character, acting as a experienced teacher, or maybe a powerful programmer.


​**4. Meaningful variables:** These variables are closely related to be objective of the prompt, are customizable, can be any kind of text format. A json, a word, a sentence, a song, and anything related to these ones.

​**5. Examples:**
If you want to dramatically increase the performance of a prompt, add it a succesful example. The LLM will understand the pattern because you are adding words like: Succesful, example.

**6. Negative variables:**
You can also request to avoid certain responses. Let your imagination fly with this.


For example, in a prompt like: 
```
Write a story about {about} with up to {number_of_words} words in a {narrative} narrative.
Write the story in {language}

Avoid using too much technical words.
```
We can see that we have different types of variables. Try executing this prompt and generating awesome stories! Feel free to customize it.

It's important to note that every word given in a prompt can potentially affect the final result. The more specific and clear the prompt is, the better the model will be able to understand and generate the desired output. 


## This are three good prompt examples:


```
1. Write a paragraph about {topic} in {language} using {number_of_words} words. Make sure to include {specific_detail}.
```
```
2. Generate a list of {number_of_items} ideas for {purpose}. Each idea should be described in {number_of_sentences} sentences.
```
```
​3. Answer the following question: {question}. Provide a detailed explanation in {number_of_paragraphs} paragraphs.
```
