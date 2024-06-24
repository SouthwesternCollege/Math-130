# Project: Date
## Description
[ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) is an international standard covering the worldwide exchange and communication of date and time-related data. The standard uses the [Gregorian calendar](https://en.wikipedia.org/wiki/Gregorian_calendar). Calendar date representations are in the form YYYY-MM-DD (or YYYYMMDD).
In this project you will write a java class that validates and processes calendar dates in accordance to the ISO 8601 standard.
## Specifications
In `Date.java` do the following:
- Complete the `isValid` method so that it returns true if the given date is valid, other wise return false.
- Complete the `toString` method so that it returns a string in the YYYY-MM-DD format if the given date is valid. Otherwise, return `"invalid"`. For example, `toString(2024, 07, 04)` returns `"2024-07-04`.
- Complete the `monthString` method so that it returns a string that represents the given month in an abbreviated form, if the given month is valid. For example, `monthString(6)` returns `"JUN"`.

In `DateTest.java` do the following in the `main` method:
- Thoroughly test each method to verify that it works correctly.
## Submit
