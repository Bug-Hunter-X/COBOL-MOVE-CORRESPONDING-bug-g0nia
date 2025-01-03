# COBOL MOVE CORRESPONDING Bug

This repository demonstrates a common error in COBOL programs involving the `MOVE CORRESPONDING` statement.  The `MOVE CORRESPONDING` statement is used to transfer data between records with similar structures, but it can lead to unexpected results if the structures aren't identical.  This example shows how data truncation or incorrect data transfer may occur when using `MOVE CORRESPONDING` with records of different structures.  The solution demonstrates the proper technique using individual `MOVE` statements for precise data transfer.

## Bug
The bug lies in using `MOVE CORRESPONDING` without careful consideration of structure differences. This can lead to data corruption and unexpected program behavior.