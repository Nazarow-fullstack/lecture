# What is new Date in JavaScript?
+ In JavaScript, you use either the new Date() or Date() constructor to get your dates (either current date or a specific date). The new Date() constructor returns a new Date object, while the Date() constructor returns a string representation of the current date and time.
![](https://aliyev.dev/storage/app/uploads/public/665/9bb/613/6659bb613fc0b807368823.jpg)

+ When you use new Date(), it creates a new Date object. This object has methods and properties
that you can use to manipulate and format the date. For example, you can use the get
FullYear(), getMonth(), getDate(), getHours(), getMinutes(), getSeconds(),

1. getFullYear(): This method returns the full year (e.g., 2024).


```javascript
const currentDate = new Date();
const currentYear = currentDate.getFullYear();
console.log(`Current year: ${currentYear}`);
```

2. getMonth(): The getMonth() method returns the month (0-indexed, where January is 0 and December is 11).
```javascript
const currentMonthIndex = currentDate.getMonth();
const currentMonth = currentMonthIndex + 1; // Adjust for 0-based index
console.log(`Current month: ${currentMonth}`);
```

3.getDate(): This method retrieves the day of the month (1–31).
```javascript
const currentDayOfMonth = currentDate.getDate();
console.log(`Current day of the month: ${currentDayOfMonth}`);
```

4. getHours(), getMinutes(), and getSeconds(): These methods give you the hour (0–23), minute (0–59), and second (0–59) components of the current time.
```javascript
const currentHour = currentDate.getHours();
const currentMinute = currentDate.getMinutes();
const currentSecond = currentDate.getSeconds();

console.log(`Current time: ${currentHour}:${currentMinute}:${currentSecond}`);
```



## Get metods of date in JavaScript

![](https://www.oreilly.com/api/v2/epubs/9780133410877/files/graphics/02tab05.jpg)
1. getFullYear(): Returns the full year (e.g., 2024)

```javascript
const currentDate = new Date();
const currentYear = currentDate.getFullYear();
console.log(`Current year: ${currentYear}`);
```

2. getMonth(): Retrieves the month (0-indexed, where January is 0 and December is 11)

```javascript
const currentMonthIndex = currentDate.getMonth();
const currentMonth = currentMonthIndex + 1; // Adjust for 0-based index
console.log(`Current month: ${currentMonth}`);
```

3. getDate(): Returns the day of the month (1–31)

```javascript
const currentDayOfMonth = currentDate.getDate();
console.log(`Current day of the month: ${currentDayOfMonth}`);
```

4. getHours(), getMinutes(), and getSeconds(): These methods provide the hour (0–23), minute (0–59), and second (0–59)

```javascript
const currentHour = currentDate.getHours();
const currentMinute = currentDate.getMinutes();
const currentSecond = currentDate.getSeconds();

console.log(`Current time: ${currentHour}:${currentMinute}:${currentSecond}`);
```


## Set metods of date in JavaScript
![](https://cdn.goconqr.com/uploads/media/image/17500326/desktop_a4a1c94e-a3d1-4bd2-a1ba-3fbea8fdc15f.png)
+ The Date object in JavaScript has several set methods that allow you to modify the date and time values of 
a Date object. These set methods are useful when you need to update the date or time components of
a Date object programmatically. Here are some of the commonly used set methods in JavaScript:

1. setFullYear(year, [month], [date]): Sets the year of a date object. You can optionally specify the month and day as well.

```javascript
const currentDate = new Date();
currentDate.setFullYear(2024); // Set the year to 2024
console.log(`Updated year: ${currentDate.getFullYear()}`);
```

2. setMonth(month, [date]): Sets the month of a date object (0-indexed, where January is 0 and December is 11).

```javascript
currentDate.setMonth(11); // Set the month to December
console.log(`Updated month: ${currentDate.toDateString()}`);
```

3. setDate(date): Sets the day of the month (1–31).

```javascript
currentDate.setDate(15); // Set the day to 15
console.log(`Updated day of the month: ${currentDate.toDateString()}`);
```

4. setHours(hour, [min], [sec], [ms]): Sets the hours of a date object (0–23).

```javascript
currentDate.setHours(22); // Set the hour to 22 (10:00 PM)
console.log(`Updated time: ${currentDate.toTimeString()}`);

```

5. setMinutes(min, [sec], [ms]): Sets the minutes of a date object (0–59)

```javascript
currentDate.setMinutes(30); // Set the minutes to 30
console.log(`Updated time: ${currentDate.toTimeString()}`);
```

6. setSeconds(sec, [ms]): Sets the seconds of a date object (0–59)

```javascript
currentDate.setSeconds(30); // Set the seconds to 30
console.log(`Updated time: ${currentDate.toTimeString()}`);
```
