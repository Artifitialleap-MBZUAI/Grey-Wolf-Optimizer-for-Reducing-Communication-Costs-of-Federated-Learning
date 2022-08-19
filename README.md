# Grey-Wolf-Optimizer-for-Reducing-Communication-Costs-of-Federated-Learning

**Abstract**

Federated learning (FL) is a type of machine learning (ML) technique in which only learnt models are stored on a server to sustain data security. The approach does not gather server-side data but rather directly shares only the models from scattered clients. Due to the fact that clients of FL frequently have restricted connection bandwidth, it is necessary to optimize the communication between servers and clients. Clients of FL frequently interact through Wi-Fi and must operate in uncertain network situations. Nevertheless, the enormous number of weights transmitted and received by existing FL aggregation techniques dramatically degrade accuracy in unstable network situations. We propose a federated GWO (FedGWO) algorithm to reduce data communication. The proposed approach improves performance under unstable network conditions by transferring score principles rather than all client models' weights. We achieve a 13.55% average improvement in the global model's accuracy while decreasing the data capacity required for network communication. Moreover, we show that FedGWO achieves a 5% reduction in accuracy loss compared to  FedAvg and FedPSO methods when tested on unstable networks.

**Dataset:** https://www.cs.toronto.edu/~kriz/cifar.html

**Authors:**

Ammar Kamal Abasi, Mohamed Bin Zayed University of Artificial Intelligence (MBZUAI), UAE. E-mail:ammar.abasi@mbzuai.ac.ae

Moayad Aloqaily, Mohamed Bin Zayed University of Artificial Intelligence (MBZUAI), UAE. E-mail: maloqaily@ieee.org

Mohsen Guizani, Mohamed Bin Zayed University of Artificial Intelligence (MBZUAI), UAE. E-mail: mguizani@ieee.org
