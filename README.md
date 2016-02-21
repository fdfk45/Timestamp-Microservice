# TIMESTAMP MICROSERVICE

### User Stories

- I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)

- If it does, it returns both the Unix timestamp and the natural language form of that date.

- If it does not contain a date or Unix timestamp, it returns null for those properties.

## Example Usage:

https://tranquil-lake-16661.herokuapp.com/june%2012%202016

https://tranquil-lake-16661.herokuapp.com/1465689600

## Example Output

{"unix":1465689600,"natural":"June 12th, 2016"}

