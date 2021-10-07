[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Introduction to MongoDB: Assignment

## Problems

For this assignment we're going to use the `sample_training` dataset from the mongo archives we loaded.

For each query, make it work using the Mongo Shell then copy your answer below the query.

### 1: Explore and Schema

Explore the `companies` collection a bit then answer those questions:

- What's the type of the field `products` - what does it represent?
- What's the type of the field `tag_list` - what does it represent?
- 

### 2: Find

1. Get all companies from Belgium

```JavaScript
db.companies.find()
```

1. Get the last 20 companies founded

```JavaScript
db.companies.find()
```

1. Get all companies competing with "Joost"

```JavaScript
db.companies.find()
```

1. Get the name & tag list of all companies tagged with "social"

```JavaScript
db.companies.find()
```

### 3: Aggregate

1. Get the number of companies founded each year in Belgium, sorted by year

```JavaScript
db.companies.aggregate()
```

### 3: Aggregate

1. Get the three countries with the most funded companies in 2008

```JavaScript
db.companies.aggregate()
```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material