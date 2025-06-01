# DDoS Attack Detection on Controller Based on Machine Learning Methods in Software-Defined Networks

In software-defined networks (SDN) the key network control functions are concentrated in the control plane (or SDN controller). Controller supports and monitors an actual global network view that includes the state of network devices, links, hosts and topology. Based on this global network view the controller with its applications is carrying out the logically centralized control of network devices' configurations and data flows in the network.

But one of the serious security threats of the SDN network is DDoS-attack on the control plane (or controller). Such attacks can lead to temporary or complete controller unavailability for switches in the network. Also, DDoS attacks could flood the control plane, the data plane, or the communication channels between controller and switches. Thus, DDoS attacks on the control plane can lead to network failure or failures in its operation, to failures in the operation of user services, and unavailability of services for end users.

This research compares the implementations of the proposed machine learning methods (logistic regression, Decision Tree, Random Forest, KNN, SVM, RNN, CNN) to detect DDoS attack on controller, using:
* open available datasets: DDoS-SDN and InSDN
* generated dataset SDN-Controller-DDoS, using Mininet environment and controller RUNOS 2.0
