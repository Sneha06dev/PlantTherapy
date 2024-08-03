# PlantTherapy

Welcome to PlantTherapy, an innovative website designed to provide comprehensive guidance on various plant-related topics. Our platform utilizes the advanced capabilities of the Gemini AI API to offer accurate and reliable information to users seeking answers to common questions about plants, gardening, and herbal remedies.

## Overview

PlantTherapy is a resourceful platform dedicated to:
- **Finding Solutions to Health Problems**: Leveraging the power of plants and herbs, we offer insights into natural remedies for common health issues. Whether you're looking for the best herb to alleviate a toothache or a plant to soothe a rash, PlantTherapy provides scientifically-backed information to help you make informed decisions about your health.
- **Exploring the Plant World**: Our platform encourages users to dive into the fascinating world of plants. Learn about different species, their unique properties, and how they contribute to our well-being and the environment.
- **Nurturing and Caring for Plants**: At PlantTherapy, we believe in the importance of nurturing plants. Our guides and resources are designed to help you grow and care for your garden, whether it's a small kitchen garden or a larger outdoor space. Discover tips and techniques for maintaining healthy plants and ensuring they thrive.

Our goal is to empower users with practical and reliable information to enhance their gardening and herbal remedy practices.



## Usage

PlantTherapy relies on the Gemini AI API provided by Google to deliver accurate plant-related information. Here is how to use the platform:

**API Key Setup**: Obtain your Gemini AI API key from the [Google Developers website](https://developers.google.com). Add your API key to the environment variables:
    ```bash
    API_KEY=your_api_key_here
    ```

## API Testing

Before integrating the Gemini API into PlantTherapy, we tested the API key using Postman to ensure it was accepting POST requests correctly. Here’s how you can do it:

1. **Set Up Postman**:
   - Open Postman and create a new POST request.
   - In the URL field, enter the Gemini API endpoint provided by Google.

2. **Add Headers**:
   - Add the required headers, such as `Content-Type: application/json` and `Authorization: Bearer your_api_key_here`.

3. **Send a Request**:
   - Construct the body of your request with the necessary parameters and data.
   - Send the request and check the response to verify that the API key is working correctly.

This step is significant as it ensures that the API integration will function smoothly within the PlantTherapy platform.


## Example Queries
- "What are the best vegetables to grow in a small space?"
- "How do I start a kitchen garden from scratch?"
-  "What is the best herb for a toothache?"
- "Which plants have anti-inflammatory properties?"
