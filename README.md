# LangGraph - Double Number Example

A simple LangGraph example demonstrating the basic concepts of:

- State
- Nodes
- Edges
- Conditional Edges
- START
- END
- State Updates
- Looping

## How It Works

The graph starts with a number and keeps **doubling it** until the number becomes greater than or equal to `100`.

```text
             START
               |
               v
           [ DOUBLE ]
               |
               v
          [ DECISION ]
           /        \
          /          \
    < 100             >= 100
      |                  |
      |                  v
      |               [ FINISH ]
      |                  |
      |                  v
      └───────────────> END
