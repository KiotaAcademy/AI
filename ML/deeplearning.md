# DEEP LEARNING

Neural networks are inspired by human brain cells.

A neural network uses electronic circuits insipired by way neurons communicate in the human brain.

in the brain, cells called Neurons are made of:

1. nucleus
2. long axon
3. terminals

![Neurons human neeurons](../resources/An-Easy-Guide-To-Neurons.webp)

Neurons communicate with each other by receiving signals into axon, alter those signals then transmit those signals through the terminal into other neurons

in a neural network, a building block called a `perceptron` which acts as an equivalent of a single neuron.

A perceptron has:

1. Input layer
2. Hidden layers
3. Output layer

A signal enters the input layer and the hidden layers run algorithms on the signal. Then, the result is passed to the output layer.

The hidden layers in a neural network resemble, as a group, the long cell body that connects dendrites to axons within a human brain cell. Those hidden layers contain nodes. Each node runs an algorithm and bits of additional code to test and adjust its result. When the value reaches a certain threshold, the node “fires”.

A node often uses a sigmoid function to determine whether or not to “fire”.

If there are other nodes connected to the node, they are activated when the signal reaches them. If the other nodes reach their own thresholds, then they fire. The signal cascades down through the hidden layers in a way that’s somewhat similar to how a signal passes down the body of a human brain cell.

The operation of a neural network is pure mathematics, he network isn’t “thinking”; it is calculating. But it’s using those calculations to create an output that humans can interpret as an answer or a recommendation.

Machine learning learns by `Trial and Error`

it continously adjusts itself

Once a neural network has ingested or already learned a certain amount of data, it stores the data in its “body of information”, called its `corpus`

If the network determines that the new data or results don’t match the patterns it has already established, it modifies those patterns for a better fit. Sometimes, to improve a single match, the network tests hundreds or thousands of modifications very rapidly and makes adjustments. Then, the network tests to determine if the match is improving. So, step by step, the machine learns.

It randomly makes its first guess, sets that guess as a variable, then tests how accurately the guess fits with both old and new data. Next, it makes an adjustment to the variable and tries again. Using mathematical processes to help it choose right-size adjustments, the system keeps on trying, getting closer and closer to perfection but never quite reaching it.
