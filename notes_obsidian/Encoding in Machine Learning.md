## Why is Encoding Necessary?

Machine learning models work with numerical data. Since real-world datasets often contain categorical variables, we need to convert them into numerical representations to use them in our models. This process is called **encoding**.

Different encoding techniques are used depending on the type of categorical variable:

- **Nominal (No Order)**: Categories have no intrinsic order (e.g., colors: Red, Green, Blue).
    
- **Ordinal(Ordered Categories)**: Categories have a meaningful order (e.g., Education Level: High School, Bachelor's, Master's, PhD or low, medium, high).


## Choosing the Right Encoding Method

| Variable Type        | Recommended Encoding Methods                                                        |
| -------------------- | ----------------------------------------------------------------------------------- |
| **Nominal**          | [[One-Hot Encoding]], [[Binary Encoding]], [[Hash Encoding]]                        |
| **Ordinal**          | [[Ordinal Encoding]], [[Label Encoding]]                                            |
| **High Cardinality** | [[Binary Encoding]], [[Target Encoding]], [[Frequency Encoding]], [[Hash Encoding]] |
