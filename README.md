# Project 1 - *Go! A Simple To Do List*

**Go! - A Simple To Do List** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Maverick Abreu**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

:heavy_check_mark:  User can **view a list of todo items**.  
:heavy_check_mark:  User can **successfully add and remove items** from the todo list.  
:heavy_check_mark:  User's **list of items persisted** upon modification and and retrieved properly on app restart.  

The following **optional** features are implemented:

:heavy_check_mark:  User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.

The following **additional** features are implemented:

:heavy_check_mark: Rebranding of the application's name and logo.  
:heavy_check_mark: Added a gradient background & removed the status bar to limit distractions and get "stuff" done!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='GO.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Some challenges I faced while creating this app, was dealing with a few syntax errors.
I also was having some difficulties wth the "FileUtils" class. My compiler wouldn't recognize my readLines & writeLines syntax. 
This was fixed by replacing "import android.os.FileUtils;" with "import org.apache.commons.io.FileUtils;".

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
