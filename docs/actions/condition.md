# Condition Action

![Condition Node](assets/condition-node.png)

Depending on a condition, a "Condition action" will divide the flow into two new branches.

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Variable    | text | Variable to evaluate |
| Operation     | select | Equal, Not Equal, Greater Than, Greater Than Equal, Less Than, Less Than Equal |
| Condition     | text | Value for condition |
| AND     | button | Add a new condition |

## Outputs

This node has two outputs indicating if the condition evaluation result was

- true
- false