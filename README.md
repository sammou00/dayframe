# Datecraft

The `Datecraft` class is a JavaScript class that provides methods for handling date and time.

## Installation

```bash
npm i datecraft
```

## Usage

```javascript
// Import the Datecraft class
import Datecraft from 'datecraft';

// Create an instance of the Datecraft class
const dateTime = new Datecraft();

// Get the current day
const currentDay = dateTime.getCurrentDay(); // ex: Sunday

// Get the current month
const currentMonth = dateTime.getCurrentMonth(); // ex: July

// Get the current formatted date and time
const formattedDateTime = dateTime.getFormattedDateTime(); // ex: 2023/10/10 12:33:00

// Get yesterday's date
const yesterday = dateTime.getYesterday(); // ex : 2023/10/09

// Get tomorrow's date
const tomorrow = dateTime.getTomorrow(); //ex :  2023/10/11

// Format a specific date and time
const specificDate = new Date('2023-01-01T12:30:00');
const formattedDate = dateTime.formatDate(specificDate); // ex: 2023/10/10
const formattedTime = dateTime.formatTime(specificDate); // ex: 12:33:00
```
