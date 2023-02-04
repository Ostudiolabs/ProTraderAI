## AI Trading Engine

A custom-built AI system that leverages Binary Decision Trees and combines technical, fundamental, and market sentiment analysis to make informed trading decisions. This AI system uses machine learning algorithms to analyze vast amounts of market data, including investor sentiment, and predicts future stock prices. It utilizes technical analysis to identify trends and make short-term trades, while relying on fundamental analysis for long-term investment decisions. Market sentiment analysis is used to evaluate the overall market mood and investor confidence in a particular stock or market. The Binary Decision Trees evaluate the risk and reward of different trading strategies based on historical data, allowing the AI system to make quick, accurate trades in real-time. The integration of these advanced technologies provides a cutting-edge solution for automating the stock trading process, helping traders maximize profits and minimize losses by considering multiple factors, including market sentiment, through the power of AI.

### Concepts

1) ***Condition*** - A condition can be any expression that return a boolean. The condition is evaluated for taking binary decision at each branching point (Node).
2) ***Action*** - An action can be any set of instruction that will be executed. For example, sending a notification.
3) ***Node*** - This is the atomic unit in the bot. A node is a branch point of the tree. It consists of 2 nodes (left and right),
a condition and a list of actions.
4) ***Tree*** - This consists of a current node and traverses the tree based on that node. On each traversal, it check the condition
of the current node, if it is true then moves on to left node other moves to the right node. If this is a leaf node, then executes all the actions in the current node.
5) ***Farm*** - A farm consists of a mapping of ticker names and their corresponding Trees. The farm can also iterate over each tree based on the current data.
6) ***Accountant*** - Keeps a log of all the decisions made and any event triggered (like buy or sell).

#### More Info and Usage coming soon
