# Qosf Screening Task
# Task1
Author:YuChao,Hsu

This method was inspired by this paper https://arxiv.org/pdf/2303.07120.pdf, and I used the QFT method to improve the Task1 example.

![截圖 2024-04-10 下午11 51 09](https://github.com/HSUYUCHAO/Qosf/assets/76589481/55fde4dd-c48c-439e-ace6-0b343c6262e0)


This method less_than_k uses the principle of quantum computing to find all the numbers in the given list list_n that are less than a specific value k by constructing a quantum circuit. First, the required number of qubits is determined based on the maximum value of list_n and k, and then the quantum Fourier transform (QFT) and conditional phase rotation are used to encode conditions smaller than k. Through quantum measurement, a list of numbers that meet the conditions is finally obtained.
