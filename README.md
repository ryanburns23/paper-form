# \<paper-form\>

## Fields
 - paper-input
 - paper-textarea
 - gold-email-input
 - vaadin-date-picker
 - paper-time-picker
 - paper-radio-buttons
 - paper-dropdown-menu
 - paper-checkbox
```javascript
[
  {
    "type": "input",
    "label": "input",
    "value": "Ryan Burns"
  },
  {
    "type": "textarea",
    "label": "textarea",
    "value": "Yo this is a cool textarea\nyooooooo"
  },
  {
    "type": "email",
    "required": true,
    "label": "email",
    "value": "ryan@ryanburns.io"
  },
  {
    "type": "date",
    "year": true,
    "label": "date",
    "value": "2017-03-03"
  },
  {
    "type": "time",
    "label": "time",
    "hour": "4",
    "min": "03",
    "value": "4:03 AM",
    "amPm": "AM"
  },
  {
    "type": "radio",
    "label": "radio buttons",
    "items": [
      "Option 1",
      "Option 2",
      "Option 3"
    ],
    "value": "Option 2"
  },
  {
    "type": "dropdown",
    "label": "dropdown",
    "items": [
      "Option 1",
      "Option 2",
      "Option 3",
      "Option 4"
    ],
    "value": "Option 4"
  },
  {
    "type": "checkbox",
    "label": "checkbox",
    "items": [
      "Option 1",
      "Option 2",
      "Option 3",
      "Option 4"
    ],
    "selectedValues": [
      "Option 2",
      "Option 1"
    ]
  }
]
```
