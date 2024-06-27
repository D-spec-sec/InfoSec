Atomicity (A): This property ensures that a database transaction is treated as a single, indivisible unit. Either all operations within the transaction are completed successfully, or none of them are. If any part of the transaction fails, the entire transaction is rolled back to its initial state.

Isolation: (I) This property ensures that the concurrent execution of transactions does not result in interference. Each transaction is executed in isolation from others, and their intermediate states are not visible to other transactions until they are committed.

Consistency (C): Ensures that a transaction brings the database from one valid state to another. The database must satisfy certain integrity constraints before and after the transaction.

Durability (D): Guarantees that once a transaction is committed, its effects are permanent, and they survive subsequent system failures. The changes made by committed transactions are stored in a durable and persistent way.
