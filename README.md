# Pizza-Chatbot-with-Amazon-Lex
## Description 
Hello! In this project, I will be creating a chatbot for an imaginary pizza shop using Amazon Lex. This project was a lot of fun and should be easy to follow.

## Set up Instructions

1. In the AWS Console, Navigate to Amazon Lex and select "Create Bot" 

<img width="1432" alt="Screen Shot 2024-05-19 at 12 07 58 PM" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/ab192745-6d2a-4772-9469-e6401b3459b4">

   
3. Give your bot a name

   <img width="1432" alt="step 2" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/34bee956-f071-479b-b480-df7b95c5e9bc">

4. Under "IAM Permissions" select Create a role with basic Amazon Lex Permissions

   <img width="1432" alt="step 3" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/3ea7a78e-f813-4b42-bd4b-ed44c52bd6a1">

5. Under "Children's Online Privacy Protection Act" select no and hit next

   <img width="1432" alt="step 4" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/bb571b40-0844-4112-bda0-06cb8c6ce3fa">

6. Select your language preference along with different voice options under "Voice Interact" then select done

<img width="1432" alt="Screen Shot 2024-05-19 at 12 11 07 PM" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/d8930efa-9fdb-4489-bbc4-eb975bb306b6">

   
7. Once your bot has been created, select intents under "English(US)" and select new Intent

   <img width="1432" alt="step 7" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/db363022-e9a0-415b-9795-8411856f315e">

8. Give your Intent a name, I chose "greetings"

   <img width="1432" alt="step 8" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/77ea3d36-55ee-4e06-9490-d82571ff0123">

9. Scroll down to Sample Utterances and create some utterances such as Hi, Hello, etc.

   <img width="1432" alt="step 9" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/185a7a64-b75d-42e2-b5d7-28446e5c21c0">

10. Once you have completed this step, scroll down to closing response and type in a message which will reflect how the bot responds to your customer.

    <img width="1432" alt="step 10" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/09982e2f-7249-4de0-8612-632256683de8">

11. You also have the option to add "Variants" under variations which is an alternate way for the bot to respond to your customers. Scroll down and select save intent

    <img width="1432" alt="step 11" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/fd813b94-6758-4c5f-8cc4-5f5e97b7d29a">

12. Select build at the top of the screen then select "test" to test your bot.

    <img width="1432" alt="step 12" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/8fd1a147-d1b7-441d-b488-226ebe5a9af9">

13. Below are screenshots of how the bot will respond in a conversational manner.

<img width="1432" alt="step 13" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/a536ea9d-8f56-459d-9edb-583be347747e">

    
14. Once you confirm the bot is working, head back to intents and create a new intent.
15. We will name this "Pizza ordering"
16. Once you complete naming your intent, head to sample utterances and type in some sample phrases like pictured below which will tell the bot you're wanting to order pizza.
17. Scroll down to initial response and type in a response that will reflect the bot understanding the customer wanting to order pizza then save intent.
  
  <img width="1432" alt="step 17" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/6039810e-9866-440b-bc9f-1ffc80d241b2">

18. On the left hand column, select slot types which is under intents and add slot type

<img width="1432" alt="Screen Shot 2024-05-19 at 12 36 39 PM" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/95c47bc4-6df6-4a6e-8748-be178e864c2f">

    
19. Name your slot type, in this scenerio, I will name it SizeType. This will help bring the ordering process together when the client is looking for a specific sized pizza.

     <img width="1432" alt="Screen Shot 2024-05-19 at 12 36 59 PM" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/7e024664-bbc1-42de-ab5a-63fa09c11e8f">

20. Add values, in this case we will add small, medium and large then hit save.

<img width="1432" alt="step 20" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/b9d806c6-13c3-4b88-b7fd-0e012db6706d">

    
21. Head back to slot types and add another slot. 
  <img width="1432" alt="step 21" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/c1ee8ac6-a3e9-4bb8-b574-acd60ff631f9">

22. We will name this ToppingType to help the bot distinguish what toppings the client wants for the pizza.

<img width="1432" alt="step 22" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/d4eb54e4-489d-44b4-b114-48f2c1ce4a6a">

23. Scroll down and add values. We will add pepperoni, chicken, veggie and sausage then hit save.

    <img width="1432" alt="step 23" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/40607cb4-bf2b-4234-9a9a-897c1286fd3e">

24. Head back to intent and select pizzaordering.

    <img width="1432" alt="step 24" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/51642530-355e-4097-b0ba-e5339c3e7142">

25. Scroll down to slots and select add slots. We will name our slot PizzaSize using the SizeType under the Slot type section and give it a prompt to help the bot complete your order.

    <img width="1432" alt="step 25" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/a2ff840c-adf3-4fec-858d-e973f0b29815">

26. Add another slot, we will repeat the steps above but this time we will be specific towards the pizza toppings.

<img width="1432" alt="step 26" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/ab8182e9-0916-457a-97f9-b490ac6e20dd">

27. Scroll down to confirmation section and under confirmation prompt, type a message that will have the bot confirm with the client regarding the pizza selections they've chosen. Under decline response, if the client says no, we want the bot to also display a message. Write a custom message to display.

<img width="1432" alt="step 27" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/a7fc4b1c-acc6-4448-aedf-20fd3d0bf1b8">
    
28. Scroll down to fulfillment and type in a success message confirming their order. See my custom message below. You will also want to create a message in case of a failure in the section underneath.

<img width="1432" alt="step 28" src="https://github.com/Xalmonte/Pizza-Chatbot-with-Amazon-Lex/assets/169603464/435bf2b3-469d-49d9-ab14-0bd784f3b70c">

    
30. Once you have finished, scroll down and save intent. Select build at the top and select test to test out the bot's new features you have created. Look at the screenshots below to see the updates. Feel free to write scrambled messaging to see how the bot responds with a similar message and doesn't get lost in translation.
43. We now want to create a feature that allows the customer to order drinks from the bot so head back to intents and add new intent.
44. Name this intent DrinkOrdering and add some utterances similar to the above step to help the bot understand that the customer wants to order a drink(s).
45. Scroll down to initial responses and type in a message that the bot will respond back to the client to help them fulfill their drink order and save intent.
46. Navigate to slot types and add a new slot type. We will name this one DrinkType then select add.
47. Under slot type values, add the different drink options. In this lab, we added pepsi, sprite, dr.pepper and coke. Once you're finished, select add.
48. We want to order another slot type to help the bot understand how many drinks the customer wants. I named it NumberType and under slot type, select Amazon.Number, give it a unique prompt to help the bot ask the customer how many drinks they want and select add.
49. Scroll down to confirmation and type a confirmation prompt, See example below for what I used.
50. Scroll down to fulfillment and type in a successful fulfillment message along with a message in case of failure as pictured below. Scroll down and hit save intent.
51. Scroll up and select build. Once it's been successfully built, select test and test our your new bot prompts.
52. Once you successfully confirm your bots new responses, we will create one more intent for ordering desserts. Navigate back to intents and add a new intent
53. We will name this DessertOrdering. Once it's done, scroll down to sample utterances and type a few messages to help the bot understand that you want to order dessert then select save intent.
54. Navigate to slot types and create a new slot type. We will name this DessertType. Once created, add your values and select save slot type.
55. Once completed, Head back to Intents, select DessertOrdering and scroll down to slots and select add slots.
56. We will create our first slot to distinguish what type of desserts the customer is looking to order under DessertType in our Slot Type section with the appropriate prompts (see example below).
57. Once completed, we want to add a second slot to distinguish how many desserts the customer is looking to order by naming it NumberType and selecting Amazon.Number under Slot Type with the appropriate prompts (Pictured below).
58. Once completed, scroll down to confirmation and type in your confirmation prompt message followed by a decline response.
59. After you're finished, scroll down to fulfillment and type in the appropriate messages for "on successfull fulfillment" and "In case of failure" sections.
60. Once you're done, scroll down to save intent. Select build at the top, once you get a success message, select test  and start testing out your new bot responses.
61. Congratulations! You have successfully built a chatbot to help fulfill custom orders for the Awesome Pizza shop. I hope you had fun creating this project.
