# Credit Card Fraud Detection using Autoencoders in Keras

The dataset contains 31 feautures. The idea is to find anomaly using the concept called auto-encoders. The autoencoders tries to re-create the input x^ or x cap from the the input x. Since unusual transaction or the fraudulant transaction happens quite rare it is a bit difficult to reconstruct them to than reconstructing normal transactions.

The anomalous transaction would have a bigger re-construction error than the usual transaction. Hence if the re-construction error crosses a particular threshold for a particular transaction. We can send it for manual analysis.
