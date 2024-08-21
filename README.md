# Apriori Algorithm

## Introduction

The Apriori algorithm is a popular method used in data mining for finding frequent itemsets and generating association rules. It is widely used in market basket analysis to understand the relationships between different products purchased together by customers. The algorithm works by identifying the most frequent individual items in the dataset and then extending them to larger and larger itemsets, as long as those itemsets appear frequently enough in the dataset.

In this notebook, we will implement the Apriori algorithm from scratch in Python and apply it to a synthetic dataset. We will explore how the algorithm works step-by-step, printing the intermediate frequent itemsets generated at each stage. This hands-on approach will help us understand the inner workings of the Apriori algorithm and its application in data mining tasks.

## Dataset Description

We are using a synthetic dataset that simulates transactions in a grocery store. The dataset includes the following items:

- `milk`
- `bread`
- `butter`
- `beer`
- `diapers`
- `eggs`
- `cola`
- `chips`
- `chocolate`

A total of 100 transactions are generated, with each transaction containing a random selection of 2 to 5 items from the above list. This dataset allows us to explore how the Apriori algorithm identifies frequent itemsets and how it scales with a larger dataset.

## Objectives

1. **Understand the Apriori Algorithm**: By implementing the algorithm from scratch, we'll gain a deep understanding of how it works.
2. **Identify Frequent Itemsets**: We will identify the most frequent itemsets in the dataset and understand their importance in market basket analysis.
3. **Optimize with a Larger Dataset**: We will run the algorithm on a larger dataset to see how it performs with more data and higher support thresholds.

Let's begin by implementing the algorithm and applying it to our dataset.
