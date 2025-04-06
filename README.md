# Contact Book App (Python Console Application)

This is a simple yet functional *Contact Book application* built using Python. It allows users to manage personal contacts through a console-based interface, making it easy to store, update, and retrieve contact information.

---

## Features

- *Create Contact*: Add a new contact with name, age, email, and mobile number.
- *View Contact*: Display the details of a specific contact.
- *Update Contact*: Modify an existing contact’s information.
- *Delete Contact*: Remove a contact from the contact book.
- *Search Contact*: Search for contacts by name (supports partial matches).
- *Count Contacts*: Show the total number of saved contacts.
- *Exit*: Close the application gracefully.

---

## How It Works

All contacts are stored in a Python *dictionary*, where the contact name is the key and the value is another dictionary containing:

```python
{
  'age': 25,
  'email': 'example@email.com',
  'mobile': '9876543210'
}
