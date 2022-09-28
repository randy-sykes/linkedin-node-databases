# Document Databases
## When not to use
1. Highly structured data
2. Data integrity is key and has to be enforced at any given time
3. Many different applications manipulate the data, and consistency is enforced at the db level.

## When to use
1. Data is unstructured or semi-structured
2. High write performance (possibly sacrificing consistency?)
3. Scaling out to cluster-like systems
