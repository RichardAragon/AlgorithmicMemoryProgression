# AlgorithmicMemoryProgression
Based on the scientific article, 'New Theory Challenges Classical View On Brain's Memory Storage


The equation for a model that progressively processes memories based on their generalizability could be something like this:


generalizability(memory) = sum(similarity(memory, otherMemory) * usefulness(otherMemory)) / numMemories


Where:

* `generalizability(memory)` is the generalizability of the memory
* `similarity(memory, otherMemory)` is the similarity between the memory and the other memory
* `usefulness(otherMemory)` is the usefulness of the other memory
* `numMemories` is the number of memories in the model

This equation would calculate the generalizability of a memory by summing the similarity of the memory to all other memories in the model, weighted by the usefulness of those other memories. The usefulness of a memory could be determined by a number of factors, such as how often the memory has been accessed in the past or how important the memory is to the model's goals.

The model could then use the generalizability of each memory to determine how much to process that memory. For example, the model could spend more time processing memories that are more generalizable and less time processing memories that are less generalizable.

The algorithms that could be used to implement this model include:

* **Genetic algorithm:** The genetic algorithm could be used to evolve the weights of the similarity and usefulness functions. This would allow the model to learn how to measure the similarity and usefulness of memories in a way that is optimal for the model's goals.
* **Classification algorithm:** The classification algorithm could be used to classify memories into different categories based on their generalizability. This would allow the model to quickly identify memories that are more likely to be useful and focus on processing those memories.
* **Prediction algorithm:** The prediction algorithm could be used to predict how useful a memory is likely to be in the future. This would allow the model to prioritize the processing of memories that are more likely to be useful.

The genetic algorithm, classification algorithm, and prediction algorithm could be used together in a sequence to implement the model. The genetic algorithm could be used to evolve the weights of the similarity and usefulness functions. The classification algorithm could then be used to classify memories into different categories based on their generalizability. Finally, the prediction algorithm could be used to predict how useful a memory is likely to be in the future.

The model could also use loops to implement the generalizability-based processing of memories. For example, the model could start by processing the memories that are most generalizable. The model could then use the prediction algorithm to predict which of the processed memories are most likely to be useful in the future. The model could then focus on processing those memories. This process could be repeated until all of the memories have been processed.
