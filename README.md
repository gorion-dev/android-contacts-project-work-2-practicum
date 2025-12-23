# Contacts UI Application — Project Work #2

**Forked from [Yandex Practicum Android Contacts](https://github.com/Yandex-Practicum/android-contacts)**

This is a learning project focused on Android development.  
It displays a list of contacts with filtering and sorting options.

The main goal of this project was to **refactor list item comparison**:

- Introduce a generic callback (`BaseListDiffCallback`) for list item comparison.
- Encapsulate comparison logic inside UI models via the `ListDiffInterface`.
- Make the code cleaner, safer, and more reusable.