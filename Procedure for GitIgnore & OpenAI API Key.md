# How To Create An OpenAI Key
How-To create an OpenAI key, you need to sign up on the OpenAI website and follow their process to generate an API key. Once you have the key, you can add it to your `.env` file and `.gitignore` as follows:

## Create an OpenAI API key:

1. **Create an OpenAI account**: Go to the OpenAI website and create an account if you don't already have one.

2. **Generate an API key**: Once you're logged in, navigate to the API section and generate a new API key.

## Zen & the Art of Preventing Security Leaks with Your User Account or Company Account (yeeps!): 

Once you have your OpenAI API key, you can add it to your `.env` file and `.gitignore` in your project directory like this **.env.example** screebshot (assuming you're using a Mac or Linux machine):
![alt text](<../SOP/Procedure for GitIgnore & OpenAI API Key-1.png>)
1. **Create a .env file**: In your project directory, create a file named `.env`. In this file, you can store your OpenAI key like this:

```bash
OPENAI_KEY=your_openai_key_here
```

Replace `your_openai_key_here` with your actual OpenAI key.

2. **Add .env to .gitignore**: To prevent your `.env` file from being tracked by Git (which is important because you don't want your secret keys to be public), you should add it to your `.gitignore` file. If you don't already have a `.gitignore` file, create one in your project directory. Then, add the following line to your `.gitignore` file:

```bash
.env
```

This tells Git to ignore the `.env` file, so it won't be included in your commits. **(Zen & the Art of Preventing Security Leaks)**

1. **Access the key in your code**: In your code, you can access the OpenAI key from the `.env` file using `process.env.OPENAI_KEY` (in Node.js). Remember to load the `.env` file at the start of your application. If you're using a package like `dotenv` in a Node.js application, you can load the `.env` file like this:

```javascript
require('dotenv').config();
```

Now, `process.env.OPENAI_KEY` will contain your OpenAI key.

Remember to never share your OpenAI key with others, and never include it in your Git commits.

![alt text](<../SOP/Procedure for GitIgnore & OpenAI API Key-2.png>)

End.

Author: [Amy Newkirk](https://www.linkedin.com/in/kiwi)			20 May 2024			APAC Gold Ltd.
