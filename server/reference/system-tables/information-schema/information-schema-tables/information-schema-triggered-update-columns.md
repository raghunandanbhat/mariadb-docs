# Information Schema TRIGGERED_UPDATE_COLUMNS Table

The [Information Schema](../) `TRIGGERED_UPDATE_TABLE` table contains information about columns specified in the update trigger. The trigger is fired only if a specified column is updated.

It has the following columns:
| Column                        | Description                                                                                                                                                                                                                                                                                                      |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TRIGGER\_CATALOG              | Always def.                                                                                                                                                                                                                                                                                                      |
| TRIGGER\_SCHEMA               | Database name in which the trigger occurs.                                                                                                                                                                                                                                                                       |
| TRIGGER\_NAME                 | Name of the trigger.                                                                                                                                                                                                                                                                                             |
| EVENT\_OBJECT\_CATALOG        | Always def.                                                                                                                                                                                                                                                                                                      |
| EVENT\_OBJECT\_SCHEMA         | Database name on which the trigger acts.                                                                                                                                                                                                                                                                         |
| EVENT\_OBJECT\_TABLE          | Table name on which the trigger acts.                                                                                                                                                                                                                                                                            |
| EVENT\_OBJECT\_COLUMN         | Column name.                                                                          |

A column is shown only if the user has non-SELECT privileges on the column.
