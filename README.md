nameparts
=========

nameparts is a Python module that I wrote to address a problem splitting full names into individual
parts (first, middle, last, etc.)

You can use it like this:

      >>> from nameparts import Name
      >>> n = Name("Thurston Howel III")
      >>> n.first_name
      'Thurston'
      >>> n.last_name
      'Howel'
      >>> n.as_dict
      {'first_name': 'Thurston', 'last_name': 'Howel', 'middle_name': None, 'suffix': None, 'generation': 'III', 'salutation': None}
      >>> n = Name("Smith, John Paul")
      >>> n.first_name
      'John'
      >>> n.last_name
      'Smith'
      >>> n.middle_name
      'Paul'

License
-------
nameparts is released under the BSD license.

Comments/Questions/Improvements
-------------------------------
Any of the above are welcome.  Contact me at the email address in my profile.
