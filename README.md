# Pre-work - *ToDoList*

**ToDoList** is a simple android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Elija Agyapong**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/agyapongeli77/SimpleToDo/raw/master/ToDoList%20walkthrough.gif' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** [I believe Android app development is a major component in the software engineering industry because of it's large reach
and penetration in the world. The Android ap development platform helps you to understand so many key concepts in the industry. I 
have been using Android all my life but I have played with other platforms and I think the android and user interface beats them
all. The layouts are not complex, they are easy to interact with and talk about the Android material design, it even gets better].

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** [From the powerful Model-View-Controller design concept, the model in the pre-work is the arraylist which contains
the list of items and the ArrayAdapter is what makes it possible for us the see the list of items on the screen/view. It wires
the model to the view. An adapter is so important in the Android app development because whether it's a listview or gridview, the
adapter is the intermediary or bridge between the data source and the view or UI the user interacts with.

Because the sizes of mobile screens cannot show a lot of list of items at the same time, the 'convertView' in the 'getView()' 
method makes it possible for old views to be recycled and reused for newer ones without having to create new instances of
listviews. This helps in the saving the computer's memory resources].

## License

    Copyright [2018] [Elija Agyapong]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
