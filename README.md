Re-implementation of the email address picker of iCal (work in progress).

  - Currently supports only email picking but can be easily extended

![COPeoplePickerViewController](https://github.com/eaigner/COPeoplePickerViewController/raw/resources/resources/picker.png "COPeoplePickerViewController")

# This Fork

This fork differs from upstream slightly:

* Tokens display the name of ther person, not the email address.
* `COPerson` has a new property: `selectedEmail` which returns the specific email address that was selected.

If this functionality already existed, but I somehow missed it, please let me know.
