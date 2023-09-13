# Ruby Todo CRUD App

This is a basic crud web application for a Todo list, built using Ruby on Rails. It allows users to perform create, read, update and destroy actions for a Todo model that contains a Title, a Description and a Completed boolean. 

## Features

- Creation of a Todo
- Read a Todo previously created
- Update a Todo
- Destroyu a Todo

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your system:

- Ruby (latest as of September 12, 2023)
- Ruby on Rails (latest as of September 12, 2023)
- Node.js and npm ((latest as of September 12, 2023))

### Installing

1. Clone the repository to your local machine:

```
git clone https://github.com/rdias66/ruby-todo-crud.git
```

2. Change into the project directory:

```
cd ruby-todo-crud
```

3. Install the required gems:

```
bundle install
```

4. Install JavaScript dependencies:

```
npm install
```

### Running the Application

Start the Rails server:

```
bundle exec rails server
```

Visit `http://localhost:3000` in your web browser to access the todo app.
Certainly! Here is the section of the README file adapted for the CRUD application you've created:

---

## Usage

1. **Creating a New Todo**:

   - Click on the "New Todo" link in the Todos list.
   - Fill in the "Title" and check the "Completed" checkbox if the task is already completed.
   - Click "Save" to add the new todo.

2. **Viewing a Todo**:

   - Click on the "Show" link next to a todo in the Todos list.
   - This will display the details of the selected todo.

3. **Editing a Todo**:

   - Click on the "Edit" link next to a todo in the Todos list.
   - Update the "Title" or toggle the "Completed" checkbox as needed.
   - Click "Save" to apply the changes.

4. **Deleting a Todo**:

   - Click on the "Destroy" link next to a todo in the Todos list.
   - Confirm the deletion in the prompt.

5. **Listing All Todos**:

   - The main page displays a list of all todos with their titles and completion status.

### Note:

As of now, the application does not perform validation on the input fields. It is recommended to ensure that valid data is entered to avoid potential issues.

---


## Acknowledgments

- [Ruby on Rails](https://rubyonrails.org/)
- [Node.js](https://nodejs.org/)




