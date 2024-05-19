# Pizza-Chatbot-with-Amazon-Lex
## Description 
Hello! In this project, I will be creating a chatbot for an imaginary pizza shop using Amazon Lex. This project was a lot of fun and should be easy to follow.

## Set up Instructions

1. In the AWS Console, Navigate to Amazon Lex
2. Select "Create Bot" and give your bot a name
3. Under "IAM Permissions" select Create a role with basic Amazon Lex Permissions
4. Under "Children's Online Privacy Protection Act" select no and hit next
5. Select your language preference along with different voice options under "Voice Interact" then select done
6. Once your bot has been created, select intents under "English(US)" and select new Intent
7. Give your Intent a name, I chose "greetings"
8. Scroll down to Sample Utterances and create some utterances such as Hi, Hello, etc.
9. Once you have completed this step, scroll down to closing response and type in a message which will reflect how the bot responds to your customer.
10. You also have the option to add "Variants" under variations which is an alternate way for the bot to respond to your customers. Scroll down and select save intent
11. Select build at the top of the screen then select "test" to test your bot.
12. Below are screenshots of how the bot will respond in a conversational manner.
13. Once you confirm the bot is working, head back to intents and create a new intent.
14. We will name this "Pizza ordering"
15. Once you complete naming your intent, head to sample utterances and type in some sample phrases like pictured below which will tell the bot you're wanting to order pizza.
16. Scroll down to initial response and type in a response that will reflect the bot understanding the customer wanting to order pizza then save intent.
17. On the left hand column, select slot types which is under intents and add slot type
18. Name your slot type, in this scenerio, I will name it SizeType. This will help bring the ordering process together when the client is looking for a specific sized pizza.
19. Add values, in this case we will add small, medium and large then hit save.
20. Head back to slot types and add another slot. We will name this ToppingType to help the bot distinguish what toppings the client wants for the pizza.
21. Scroll down and add values. We will add pepperoni, chicken, veggie and sausage then hit save.
22. Head back to intent and select pizzaordering.
23. Scroll down to slots and select add slots. We will name our slot PizzaSize using the SizeType under the Slot type section and give it a prompt to help the bot complete your order.
24. Add another slot, we will repeat the steps above but this time we will be specific towards the pizza toppings.
25. Scroll down to confirmation section and under confirmation prompt, type a message that will have the bot confirm with the client regarding the pizza selections they've chosen.
26. Under decline response, if the client says no, we want the bot to also display a message. Write a custom message to display.
27. Scroll down to fulfillment and type in a success message confirming their order. See my custom message below. You will also want to create a message in case of a failure in the section underneath.
28. Once you have finished, scroll down and save intent. Select build at the top and select test to test out the bot's new features you have created. Look at the screenshots below to see the updates. Feel free to write scrambled messaging to see how the bot responds with a similar message and doesn't get lost in translation.
29. We now want to create a feature that allows the customer to order drinks from the bot so head back to intents and add new intent.
30. Name this intent DrinkOrdering and add some utterances similar to the above step to help the bot understand that the customer wants to order a drink(s).
31. Scroll down to initial responses and type in a message that the bot will respond back to the client to help them fulfill their drink order and save intent.
32. Navigate to slot types and add a new slot type. We will name this one DrinkType then select add.
33. Under slot type values, add the different drink options. In this lab, we added pepsi, sprite, dr.pepper and coke. Once you're finished, select add.
34. We want to order another slot type to help the bot understand how many drinks the customer wants. I named it NumberType and under slot type, select Amazon.Number, give it a unique prompt to help the bot ask the customer how many drinks they want and select add.
35. Scroll down to confirmation and type a confirmation prompt, See example below for what I used.
36. Scroll down to fulfillment and type in a successful fulfillment message along with a message in case of failure as pictured below. Scroll down and hit save intent.
37. Scroll up and select build. Once it's been successfully built, select test and test our your new bot prompts.
38. Once you successfully confirm your bots new responses, we will create one more intent for ordering desserts. Navigate back to intents and add a new intent
39. We will name this DessertOrdering. Once it's done, scroll down to sample utterances and type a few messages to help the bot understand that you want to order dessert then select save intent.
40. Navigate to slot types and create a new slot type. We will name this DessertType. Once created, add your values and select save slot type.
41. Once completed, Head back to Intents, select DessertOrdering and scroll down to slots and select add slots.
42. We will create our first slot to distinguish what type of desserts the customer is looking to order under DessertType in our Slot Type section with the appropriate prompts (see example below).
43. Once completed, we want to add a second slot to distinguish how many desserts the customer is looking to order by naming it NumberType and selecting Amazon.Number under Slot Type with the appropriate prompts (Pictured below).
44. Once completed, scroll down to confirmation and type in your confirmation prompt message followed by a decline response.
45. After you're finished, scroll down to fulfillment and type in the appropriate messages for "on successfull fulfillment" and "In case of failure" sections.
46. Once you're done, scroll down to save intent. Select build at the top, once you get a success message, select test  and start testing out your new bot responses.
47. Congratulations! You have successfully built a chatbot to help fulfill custom orders for the Awesome Pizza shop. I hope you had fun creating this project.
