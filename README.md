# Contact Book Directory

A command-line Contact Book application built in Python using dictionaries. This application allows users to manage their contacts efficiently with features for adding, viewing, searching, updating, and deleting contact information.

## Features

- **Add Contacts**: Store contact information including:
  - Name
  - Phone Number
  - Email Address
  - Physical Address

- **View Contacts**: Display all stored contacts in a formatted list

- **Search Functionality**: Search contacts by name with partial matching support

- **Update Contacts**: 
  - Modify existing contact information
  - Skip unchanged fields
  - Selective field updates

- **Delete Contacts**: Remove contacts from the directory

## Installation

```bash
git clone https://github.com/rohithds/contact-book.git
cd contact-book
```

## Usage

Run the program using Python:

```bash
python contact_book.py
```

### Menu Options

1. Add Contact
2. View Contacts
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit

## Example Usage

```python
# Create a new contact
Enter name: John Doe
Enter phone number: 1234567890
Enter email: john@example.com
Enter address: 123 Main St

# Search for a contact
Enter name to search: John

# Update a contact
Enter name to update: John Doe
Enter new information (press Enter to keep current value)
```

## Data Structure

The application uses a nested dictionary structure:
```python
contacts = {
    "John Doe": {
        "phone": "1234567890",
        "email": "john@example.com",
        "address": "123 Main St"
    }
}
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- Data persistence (file storage)
- Multiple phone numbers per contact
- Contact categories/groups
- Export/import functionality
- Birthday reminders
- Contact favorites
- Contact notes/tags

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- [@rohithds](https://github.com/rohithds)

## Contact

Rohith DS - [@rohithds](https://github.com/rohithds)

Project Link: [https://github.com/rohithds/contact-book](https://github.com/rohithds/contact-book)

## Acknowledgments

- Built using Python's dictionary data structure
- Inspired by the need for a simple, efficient contact management system

---
⭐ Star this repo if you found it helpful!

Feel free to submit issues and enhancement requests!
