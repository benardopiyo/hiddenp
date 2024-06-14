# hiddenp

## Instructions

* The `hiddenp` program checks if the first string (s1) is hidden in the second string (s2). 
* A string s1 is considered hidden in s2 if it is possible to find each character from s1 in s2, in the same order as they appear in s1.

## Requirements

* If s1 is hidden in s2, the program displays 1 followed by a newline ('\n').
* If s1 is not hidden in s2, the program displays 0 followed by a newline.
* If s1 is an empty string, it is considered hidden in any string s2.
* If the number of arguments is different from 2, the program displays nothing.

## Usage

* To run the program, use the following commands in your terminal:

```bash
$ go run . "fgex.;" "tyf34gdgf;'ektufjhgdgex.;.;rtjynur6" | cat -e
1$
```

```bash
$ go run . "abc" "2altrb53c.sse" | cat -e
1$
```
```bash
$ go run . "abc" "btarc" | cat -e
0$
```

```bash
$ go run . "DD" "DABC" | cat -e
0$
```
```bash
$ go run .
$
```