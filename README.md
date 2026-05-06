# JSON Parser

A basic JSON parser made in Java. It is mainly exploratory and does not aim to provide full JSON specification support or high performance. Has support for objects and arrays.

## Main Files

### `JSONLexer.java`

Takes JSON as string input and converts it into tokenized data. Token types are stored in `TokenConstants.java` to avoid possible confusion.

### `JSONObject.java`

Converts the tokenized raw data into a Java object representing the JSON hierarchy. It contains fields for `type`, `value`, and a `Map` of child objects.
