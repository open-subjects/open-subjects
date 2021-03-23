# Common Validation rules

## Validation request requirements

In order to ease reviewing validation requests, ensure you match the following
requirements before applying for a review.

??? success "Why the requirements?"

    These requirements 

The repository must conform to the following:

proper documentation must be easily accessible (i.e.: README.md, mkdocs, ...)

- validation request must conform to the constraints defined in the subject
  - program should be able to execute the example
  - program should accept input given in the subject description excepted
  if adapting the format is relevant
  - program may output information in other format than specified in the subject
- repository must conform to at least one (1) community linter
- at least one (1) method of packaging must be made available

## Detailed requirements

### Packaging

Code or application **must** be packaged and easily installable.

Any packaging method relevant to the chosen ecosystem can be fit this requirement.

Most common might be Docker

### Linting

- must be documented
- should be a common linter
- may tweak configuration in certain parts (line length up to 110 chars)

### Documentation

- Describe program
- Describe installation process (generate executable or install in system)
- Describe usage
- May provide examples
- Should list additional features
