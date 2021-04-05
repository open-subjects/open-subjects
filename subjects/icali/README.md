# Icali

**Goal**: Develop a CLI program that creates icals from csv files.

```console
$ icali my-events.csv
created 3 events:
- event A (2021-02-28)
- event B (2021-03-07)
- event C (2021-02-27
```

## Input

The program **must** implement the `--date` and the `--title` flag.
The program **must** take one (1) or more files as csv inputs to process.

The dates **must** match the [ISO 8601][iso-8601]

Date: Specify the column name from which the program will load the event date ("date")
Title: Specify the column name from which the program will load the event title ("title")

More flag **may** be implemented, such as (`--description` for the description, `--end`
for end date field if implemented, `--duration`...).

## Output

One (1) or multiple `.ics` files ready to be imported in your favourite calendar.

The output file **must** match the [RFC5545][rfc-5545]

## Data

exemple file:

```csv
title,date,description
event A, 2021-02-28, do some stuff
event B, 2021-03-07, do some other stuff
event C, 2021-02-27, nice event
```

exemple file 2:

```csv
e,ref,description
data A, 2022-02-28, do some stuff
event C, 2021-02-27, nice event
```

## Additional targets

- Documentation
- Unit tests
- Specify date and time in events
- Implement duration processing: end date can be computed from column

[iso-8601]: https://en.wikipedia.org/wiki/ISO_8601
[rfc-5545]: https://tools.ietf.org/html/rfc5545

## Submissions

- [@nicolasdecorbez/icali](https://github.com/nicolasdecorbez/icali)
