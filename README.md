# openai-provider-metadata-extension-vercel-ai-sdk

The `openai-provider-metadata-extension-vercel-ai-sdk` is a custom OpenAI provider designed specifically for the Vercel AI SDK. It extends the functionality of the standard OpenAI provider by allowing arbitrary extra metadata to be passed into the body of the API request, providing developers with greater flexibility and customization options.

Key features:
1. Seamless integration with the Vercel AI SDK: This custom provider is built to work smoothly with the Vercel AI SDK, ensuring compatibility and ease of use.

2. Arbitrary metadata support: Developers can include any additional metadata they need in the API request body, enabling them to tailor the requests to their specific requirements.

3. Flexible metadata inclusion: The provider allows for dynamic inclusion of metadata based on the developer's needs, making it adaptable to various use cases.

4. Easy integration: Integrating this custom provider into your Vercel AI SDK project is straightforward, requiring minimal setup and configuration.

5. Extensible and customizable: Developers can easily modify and extend the provider to fit their specific needs, making it a versatile tool for enhancing the functionality of the Vercel AI SDK.

Usage:
To use this custom OpenAI provider, simply import it into your project and create an instance using the `createOpenAI` function. Pass in the necessary configuration options, including the base URL, API key, and any extra metadata you want to include.

See the vercel ai sdk docs for more details: [https://sdk.vercel.ai/providers/ai-sdk-providers/openai](https://sdk.vercel.ai/providers/ai-sdk-providers/openai)

Example:
```javascript
const openai = createOpenAI({
  baseURL: 'https://api.openai.com/v1',
  apiKey: 'YOUR_API_KEY',
  extraMetaData: {
    customField1: 'value1',
    customField2: 'value2',
    // Include any additional metadata fields as needed
  },
});
```

By leveraging this custom OpenAI provider, developers can easily extend the capabilities of the Vercel AI SDK and include arbitrary metadata in their API requests. This opens up new possibilities for customization, tracking, analytics, and more, empowering developers to build more advanced and tailored applications with the Vercel AI SDK.

Contributions, bug reports, and feature requests are welcome! Let's collaborate to make this custom provider even better and unlock the full potential of the Vercel AI SDK.