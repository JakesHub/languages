<pre>
```cobol
# COBOL Cheat Sheet

## IDENTIFICATION DIVISION

IDENTIFICATION DIVISION.
PROGRAM-ID. program-name.

## ENVIRONMENT DIVISION

ENVIRONMENT DIVISION.
CONFIGURATION SECTION.
SOURCE-COMPUTER. computer-type.
OBJECT-COMPUTER. computer-type.

## DATA DIVISION

### FILE SECTION

DATA DIVISION.
FILE SECTION.
FD file-name.
01 record-name.
   02 field-name PIC data-type.

### WORKING-STORAGE SECTION

WORKING-STORAGE SECTION.
01 variable-name PIC data-type [VALUE initial-value].

## PROCEDURE DIVISION

### PERFORM Statement

PERFORM procedure-name [THROUGH procedure-name]
      [UNTIL condition]
      [WITH TEST BEFORE/AFTER]

### IF Statement

IF condition
    [THEN statements]
    [ELSE statements]
END-IF

### EVALUATE Statement

EVALUATE variable-name
    WHEN value [OR value]...
        statements
    [WHEN OTHER
        statements]
END-EVALUATE

### MOVE Statement

MOVE value TO variable-name

### COMPUTE Statement

COMPUTE variable-name [ROUNDED]
    = arithmetic-expression

### DISPLAY Statement

DISPLAY variable-name

### READ Statement

READ file-name [AT END/NOT AT END]
    [INVALID KEY statements]

### WRITE Statement

WRITE record-name [FROM/THRU identifier]

## DIVISION TERMINATORS

END PROGRAM.
STOP RUN.
```
</pre>
