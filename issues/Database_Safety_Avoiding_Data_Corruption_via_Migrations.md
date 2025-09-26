### Problem Scenario
Restoring or migrating the database without caution can corrupt live user or shift data.

### Why Learn This?
This happens when you run migrations or restore backups without verifying data integrity. To avoid it, you need to understand how to safely restore a database, run migrations, and verify the result.

### Mini Project
1. Spin up a local database for the app (use a sample SQLite or MySQL DB).
2. Restore a provided SQL dump.
3. Run the app's migration scripts.
4. Query for user and shift counts before and after migration.
5. Create and then rollback a test migration.

#### Success Tips
- Always backup before running migrations.
- Use the database console to check data before and after changes.
- Document every step you take.

#### Success Metric
Able to restore the DB, run and rollback migrations, and verify data without errors.