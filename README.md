# Notes about proto3

## Elements

### Scalar Types

- float
- double
- boolean
- enum
- repeated

### Tags

- 1 ~ 2^29-1 (536870911)
- cannot use 19000 through 19999
- 1 ~ 15 use 1 byte in space, so use them for frequently populated fields
- 16 ~ 2047 use 2 bytes
- reserved tag

### Repeated Fields

- a list or an array

### Default value of fields

- bool: false
- number: 0
- string: empty string
- bytes: empty bytes
- enum: first value*
- repeated: empty list

## Resources

- (proto3)[https://www.udemy.com/protocol-buffers/]
- (google api)[https://github.com/googleapis/googleapis/blob/master/google/type/date.proto]