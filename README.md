This project is an Alexa skill that allows users to search for products and get recommendations using the RapidAPI Amazon Product Search API. 
The skill features product search capabilities where users can simply ask Alexa to find specific products, and it also provides product recommendations based on popular choices.
To set up this skill, Node.js installed on local machine.Set up the skill’s language model with the SearchIntent (including a slot for product) and RecommendIntent. Save and build the model.
AWS Lambda function is set up in the AWS Management Console.A new Lambda function is created using the Node.js runtime, and the code is copied from index.js into the Lambda function editor.
Lambda function is linked to Alexa skill in the Alexa Developer Console.
Once deployed, the skill is tested using the Alexa simulator or a physical Alexa device.
