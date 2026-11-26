# CPU-VS-GPU-VS-TPU-VS-NPU
Assignment 2

Assignment Topic: Comparative Analysis of Modern Processing Units: CPU, GPU, TPU, and NPU

Program: Bachelor of Information Technology Management (BITM) – 1st Semester

Submitted By: Kismat Shrestha

Roll No: 14

Date: November 26, 2026

1. Introduction
Modern computing relies on specialized hardware to handle increasingly complex workloads. While early computers depended almost entirely on a single processor to execute every task, the rise of high-definition graphics, big data, and Artificial Intelligence (AI) has led to specialized processing units. Understanding the architectural differences between a CPU, GPU, TPU, and NPU is essential for IT managers and professionals when making decisions about hardware procurement, cloud computing, and system optimization. 

2. Overview of Processing Units
A. Central Processing Unit (CPU)
Definition: Often called the "brain" of the computer, the CPU is a general-purpose processor designed to handle a wide variety of computing tasks.
Architecture: Features a few powerful cores (typically 4 to 64 in consumer/server chips) with high clock speeds and large cache memories. It excels at sequential processing, complex logic, and branching.Primary Applications: Running operating systems, managing databases, executing office software, and handling system orchestration.
Key Manufacturers: Intel, AMD, Apple, Qualcomm.
B. Graphics Processing Unit (GPU)
Definition: A specialized electronic circuit originally designed to accelerate computer graphics and image processing.
Architecture: Consists of thousands of smaller, simpler cores built for massive parallel processing. Instead of doing one complex task quickly, it performs thousands of simple mathematical calculations simultaneously.
Primary Applications: 3D video rendering, gaming, video editing, scientific simulations, and training large AI/Deep Learning models.
Key Manufacturers: NVIDIA, AMD, Intel. 
C. Tensor Processing Unit (TPU)
Definition: An Application-Specific Integrated Circuit (ASIC) developed specifically by Google to accelerate machine learning and neural network workloads.
Architecture: Built around a systolic array of Multiply-Accumulate (MAC) units. This design allows massive amounts of matrix and tensor data to flow directly from one compute unit to the next without repeatedly accessing main memory, maximizing speed and energy efficiency.
Primary Applications: Cloud-based AI training and inference, natural language processing (e.g., powering Large Language Models), and Google Search/Translate algorithms.
Key Manufacturer: Google (primarily accessed via Google Cloud).
D. Neural Processing Unit (NPU)
Definition: A dedicated, low-power microprocessor designed specifically to accelerate AI and machine learning algorithms directly on consumer edge devices.
Architecture: Optimizedm for lower-bit integer math (such as INT8 or INT4). It integrates directly into a device's System-on-Chip (SoC) to deliver high performance-per-watt without draining battery life.
Primary Applications: On-device AI tasks like smartphone facial recognition (e.g., Face ID), real-time camera background blur, voice assistants, and local AI features on modern laptops (such as Copilot+ PCs).
Key Manufacturers: Apple (Neural Engine), Qualcomm (Hexagon), Intel, AMD, Samsung.

3. Comparative Analysis
Feature / Attribute	CPU (Central Processing Unit)	GPU (Graphics Processing Unit)	TPU (Tensor Processing Unit)	NPU (Neural Processing Unit)
Core Design	Few complex, high-speed cores	Thousands of small, parallel cores	Matrix-based systolic arrays	Low-power neural compute engines
Processing Style	Sequential / Low-latency	Massively parallel	Specialized tensor/matrix flow	Parallel quantized inference
Flexibility	Very High (General purpose)	Moderate (Graphics & parallel math)	Low (Strictly ML/Tensor workloads)	Low (Strictly edge AI models)
Power Consumption	Moderate to High	Very High (Requires heavy cooling)	High (Optimized per watt in data centers)	Very Low (Single-digit watts for batteries)
Deployment Environment	All computers, servers, phones	Gaming PCs, workstations, data centers	Cloud servers & enterprise data centers	Smartphones, laptops, IoT, smart cars
Primary Strength	System control & complex logic	Heavy graphics & AI model training	Ultra-fast, large-scale cloud AI	Battery-efficient, private on-device AI

4. Business & IT Management Perspective (Why It Matters in BITM)
From an Information Technology Management standpoint, selecting the right processor architecture directly impacts cost, scalability, and data privacy:
1.Cost Optimization: Using a high-end GPU for basic web hosting wastes money and electricity, whereas using a CPU to train a deep learning model takes too long and inflates operational costs. 
2.Cloud vs. Edge Strategy: Businesses deploying massive AI applications rely on GPUs and TPUs in the cloud for heavy computation. Conversely, companies building mobile apps leverage NPUs on users' devices to run AI locally—reducing cloud server expenses and keeping user data private.

5. Conclusion
No single processor makes the others obsolete; instead, modern systems rely on heterogeneous computing—combining multiple processor types on a single System-on-Chip (SoC) or server. The CPU acts as the orchestrator managing the operating system, the GPU handles heavy parallel rendering and model training, the TPU accelerates massive cloud-scale AI, and the NPU brings fast, power-efficient intelligence directly to everyday mobile devices. 
