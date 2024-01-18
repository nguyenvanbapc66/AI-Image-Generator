![ai-powered-image-generator-app-with-react-dall-e](https://github.com/olawanlejoel/ai-img-generator/assets/57611810/cb765f8b-4eab-49b9-9f08-7d97b9837112)

# Building a React Application for AI-Powered Image Generation Using OpenAI DALL-E API

In this project, learning how to build an AI image generator application using React, Node.js, and the OpenAI API.

1. Clone or fork the repository.

### Dependency Management

Installs dependencies defined in your `package.json` file during the deployment process.

### Environment Variables

When deploying, add the OpenAI API key as an environment variable using the following variable name:

```
OPENAI_API_KEY = 'YOUR_API_KEY'
```

### Port

Sets the `PORT` environment variable.

### Start Command

Use `npm run build && npm run start` as the start command.

### Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit), the `npm run build && npm run start` commands are run.
