
# To do List Version 3

It is a to do list web application, it is not a static application like the previous version of To Do List.
You can add your tasks that you have to do throughout the day and maintain separate work, home, school, etc to do list, hpwever you may want.
After you are done with a task you can mark it done. Click on the + button to add new tasks to the list.


## Authors

- [Aryan Shukla](https://www.github.com/aryannewyork)


## Deployment

The application is deployed on Heroku and it uses Mongo DB as database.
To access the application you can visit the following link

[To Do List](https://aqueous-meadow-94570.herokuapp.com/)

- It should look something like this

  ![UI_FIRST_PAGE](https://user-images.githubusercontent.com/79625246/175826217-4a2b667a-e3ec-4754-85cb-294ac34925a1.jpg)

- You can click on + button to add more items

  ![ADD_ITEM](https://user-images.githubusercontent.com/79625246/175826221-10babf4f-3e5b-4d49-be55-541f050f37b2.jpg)

- The new item is added to the database directly, and it persists.

  ![MONGODB_ADD_ITEM](https://user-images.githubusercontent.com/79625246/175826226-5135312e-8e8f-414a-b99b-730a627afe99.jpg)

- You can remove items by clicking on the checkbox and marking the item. And it will be removed from the list as well as the database.

  ![MONGODB_DELETED_ITEM](https://user-images.githubusercontent.com/79625246/175826216-7b7a9f45-d7bd-4625-8fc8-da6e0c92592c.jpg)

- You can add another new list by simply going to "/<ListName>" route. You can name your list accordingly in <ListName> field.

  ![HOME_UI](https://user-images.githubusercontent.com/79625246/175826225-14d62d69-c0f9-419a-9af3-3604ee8d6204.jpg)

  _I have already added an item, "Cook Food" in my home list_

- Before new list is added our database looked like this

  ![MONGODB_COLLECTIONS](https://user-images.githubusercontent.com/79625246/175826214-e483d21e-dfbe-40a4-8c3c-25ebc4a56d91.jpg)

- After adding the "Home" list, it has another collection added to it, containing all the different lists.

  ![ADD_LIST_COLLECTION](https://user-images.githubusercontent.com/79625246/175826222-3a776ae6-8dc0-4b05-bf08-348185f28377.jpg)

- In database this is how a list is represented

  ![MONGODB_ADD_ITEM_HOME_LIST](https://user-images.githubusercontent.com/79625246/175826228-f3aaac04-4202-4e02-a83f-d92333ba03d5.jpg)

