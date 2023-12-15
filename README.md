Notes App Development Project

Overview

This project involves developing a notes application with specific functionalities and layout requirements. The app will feature a main screen with a list of notes and a separate fragment for adding or editing notes.

Main Screen (Home Screen)
Layout: Includes a RecyclerView and an "Add Note" button.
RecyclerView: Occupies all available space except for the button area, with a margin of 10dp.
Functionality:
Displays the titles of notes.

Saving a note stores it in a local database and returns it to the Main Activity.

The back button returns to the Main Activity without saving.

Data Storage

Database: Utilize the Room Library for data persistence.

RecyclerView Updates: Implement DiffUtil for efficient redrawing and updates.
Additional Considerations

Ensure smooth navigation between fragments.

Implement efficient data handling with Room Library.

Prioritize user experience in terms of interface design and responsiveness.
Include error handling, especially for database operations and fragment transitions.

## License

    Copyright [2023] [Akin Babatunde]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
