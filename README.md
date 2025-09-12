Mastering the AI Factory: An LLMOps Learning Adventure
Welcome, future AI operator! This repository is your training ground for mastering the art and science of Large Language Model Operations (LLMOps) on Red Hat OpenShift AI.

This is more than just a collection of scripts; it's a cohesive learning path designed to take you from basic model serving to running a sophisticated, efficient, and reliable "AI Factory."

The Mission
Your mission is to master the balance between the three critical pillars of production AI:

🚀 Performance: Is the model fast and responsive enough?

✅ Accuracy: Is the model smart and reliable enough?

💰 Cost: Is the service economically viable and efficient?

By completing the labs in this repository, you will gain the hands-on skills needed to manage these competing forces and deliver real business value.

The Learning Path
This repository contains a series of hands-on labs, each representing a core mission in your LLMOps journey. They are designed to be completed in order, as each lab builds upon the skills of the last.

Mission 1: Performance Benchmarking

Tool: GuideLLM

Objective: Learn to measure everything. Establish a data-driven performance baseline by testing for latency, throughput, and Time to First Token.

Mission 2: Accuracy Validation

Tool: lm-eval-harness & Trusty AI

Objective: Ensure your model is not just fast, but also correct. Validate its quality and reasoning capabilities against industry-standard benchmarks.

Mission 3: Performance Optimization

Tool: vLLM

Objective: Become a performance engineer. Systematically tune the vLLM inference engine to squeeze maximum efficiency from your hardware.

Mission 4: Model Quantization

Tool: LLM Compressor

Objective: Master the ultimate optimization. Use quantization to drastically reduce model size, unlocking massive cost savings and performance gains.

🤝 How to Contribute
This is a living project, and we welcome your contributions! Whether you've found a bug, have an idea for a new lab, or want to improve an existing one, your input is valuable.

Here are a few ways you can help:

Report a Bug: If you find something that's not working, please open an issue and let us know.

Suggest an Enhancement: Have an idea for a new feature or a better way to explain a concept? We'd love to hear it! Open an issue to start the discussion.

Submit a Pull Request: If you've fixed a bug or implemented a new feature, feel free to fork the repository and submit a pull request. We appreciate all contributions, big or small!

Getting Started
To begin your adventure, you will need:

Access to a Red Hat OpenShift AI cluster.

At least one available GPU node.

Familiarity with the oc and helm command-line tools.

Start with the first mission in the 01-performance-benchmarking directory and work your way through the path. Good luck!