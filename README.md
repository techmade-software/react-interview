# Statement

## Question 1.

Write a function that takes unknown amount of numbers and returns their sum. The amount of numbers ranges from 1 to 10

## Question 2.
Write a function getDuplicatedArray() which returns an array of at least length 5 if it's length is lesser than 5. It just duplicates the array element within array if the length is lesser than 5


# Statement

## Question 3.

1. Write a component that fetches data from the API and lists all the items on the DOM. Also, implement filtering based on categories present in the data and sort it based on price.
2. Filter component should be responsible for filtering the data.

3. Sort Component should be responsible for sorting the data.

**Hint**: Pass props from DataCards to Filter and Sort components. Make sure that filter and sort are pure components.

API endpoint: [https://weak-gray-tortoise-fez.cyclic.app/touristDestinations] (Returns data of tourist destinations)

Sample Response:

```json
{
  "name": "CELLULAR JAIL, PORT BLAIR",
  "info": "It has been an important historical part of Port Blair. Notable freedom fighters such as Veer Savarkar, Jogendra Shukla, Batukeshwar Dutt, and Babarao Savarkar were some of the inmates here. Don’t miss the light and sound show (Monday, Wednesday, and Friday) when you visit Cellular Jail.",
  "images": "https://www.holidify.com/images/cmsuploads/compressed/3616_20190213160612jpg",
  "location": "https://www.google.co.in/maps/place/Cellular+Jail+National+Monument/@11.6738247479768,15z/data=!4m2!3m1!1s0x0:0x616a8c6623fdba3f?ved=2ahUKEwihqtPEuvPlAhU4IbcAHThdBsAQ_BIwJnoECA4QCA",
  "id": 2,
  "price": "676.9",
  "ratings": "1.6",
  "recommended": true,
  "trending": true,
  "state": "Andaman & Nicobar",
  "duration": 7
}
```
