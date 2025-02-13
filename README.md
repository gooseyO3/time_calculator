# **Time Calculator**

The `add_time` function helps calculate the time after adding a given duration to a starting time. It also accepts an optional day of the week argument, making it suitable for day-planning.

## **How It Works**

1. **Extracting and Converting Time**
- The function divides both the start time and duration into hours and minutes.
- The start time is also converted to a **24-hour format** for ease of calculations.

2. **Adding the Duration**
- The total minutes are obtained by adding the duration to the start time.
- It determines **how many full days** have passed and the hours left in the day.

3. **Finding the New Time**
- The process puts the hour and minutes in the right format.
- It converts the time to **AM/PM format** for accuracy.

4. **Handling the Day of the Week** *(Optional)*
- If a start day is given, the function calculates which day of the week it will be after the duration added.

5. **Formatting the Output**
- The final time is well formatted, including the **day of the week** if it applies.
- It also indicates if the outcome is on the **next day** or **several days after**.

## **Why It's Useful**

The `add_time` function is a simple function to have in most real-world scenarios, such as:

✅ **Event Planning** – Quickly determine when a meeting or event will end.
✅ **Travel and Logistics** – Determine times of arrival based on trip durations.
✅ **Project Management** – Track deadlines and plan task durations.
✅ **Daily Life & Reminders** – Figure out when you’ll finish an activity or when an alarm should go off.

Whether you’re organizing your schedule or just curious about what time it will be after a long flight, this function makes time math **quick, easy, and accurate**!
