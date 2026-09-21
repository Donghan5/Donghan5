# Donghan Kim

**Systems-oriented Software Engineering Student @ 42 Paris | ML & Distributed Infrastructure**

## About

I am a software engineering student at 42 Paris with a systems-oriented foundation in low-level programming, networking, and backend fundamentals. I am developing deeper capability in machine learning, infrastructure, and distributed systems, with a long-term interest in the systems that build, operate, and scale intelligent applications: **Distributed & AI Systems**.

## Foundation — 42 Paris

The [42 Paris Common Core](https://github.com/Donghan5/42_Course) is the engineering base for my later work. Through C/C++ and Unix/Linux projects, I built practical foundations in memory management, processes, concurrency, networking, algorithms, low-level programming, and HTTP/backend concepts.

Projects such as `minishell`, `philosophers`, `webserv`, `inception`, and `ft_transcendence` provided the systems context behind the ML and infrastructure work below.

```text
42 Paris Common Core
└── Systems / computer-science foundation
    ├── ML / AI: ft_linear_regression → multilayer_perceptron → total-perspective-vortex
    └── Systems / infrastructure: systems projects → networking & containers → inception-of-things

                         developing toward Distributed & AI Systems
```

## Featured Projects

### [total-perspective-vortex](https://github.com/Donghan5/total-perspective-vortex) — EEG motor-task classification

An end-to-end, subject-specific EEG motor-task classification pipeline built on the PhysioNet EEG Motor Movement/Imagery dataset. It filters recordings, extracts event epochs, uses CSP features with LDA classification, and evaluates on disjoint held-out runs to avoid train/test contamination. The CLI also replays epochs one by one and measures inference latency. This is my strongest applied ML project: a step from implementing algorithms toward evaluating an ML pipeline on real signal data.

### [multilayer_perceptron](https://github.com/Donghan5/multilayer_perceptron) — neural networks from scratch

A NumPy-only multilayer perceptron for breast-tumor classification. It implements forward and backpropagation, ReLU/sigmoid activations, softmax with cross-entropy, He/Xavier initialization, and SGD or Adam optimization. Mini-batch training, train/validation separation, early stopping, inference, and `.npz` model serialization make the training lifecycle explicit. It extends my ML foundations from basic optimization to how neural networks are trained.

### [inception-of-things](https://github.com/Donghan5/inception-of-things) — Kubernetes and GitOps practice

A hands-on infrastructure project that builds local Kubernetes environments with Vagrant and K3s, including server and worker nodes. It deploys applications through Kubernetes Deployments, Services, and Ingress; a further stage uses k3d and Argo CD to synchronize manifests from Git with automated sync, pruning, and self-healing. This demonstrates practical experience with the orchestration layer commonly used to operate distributed applications—not a claim of distributed-systems expertise by Kubernetes usage alone.

### [ft_linear_regression](https://github.com/Donghan5/ft_linear_regression) — ML optimization fundamentals

A linear-regression implementation built without high-level ML libraries. It implements prediction, mean-squared-error calculation, gradient descent, parameter updates, and model-parameter persistence. This project marks the beginning of my bottom-up approach to ML: understanding optimization mechanics before relying on higher-level frameworks.

## Other Systems Work

- [webserv](https://github.com/Donghan5/webserv) — C++98 HTTP/1.1 server work using sockets, `epoll`, non-blocking I/O, CGI, and process management.
- [inception](https://github.com/Donghan5/inception) — containerized system-administration work with Docker Compose, Nginx, WordPress, and MariaDB.
- [ft_transcendence](https://github.com/Donghan5/ft_transcendence) — real-time web application with a Fastify/WebSocket backend, Nginx gateway, Docker Compose, and optional observability services.

## Current Focus

I am continuing to develop in distributed systems, ML systems, system design, and infrastructure for AI workloads. My direction is to connect model understanding with the infrastructure, deployment, reliability, and operational concerns of intelligent applications.

## Core Technologies

**Used in projects:** C, C++, Python, TypeScript, Shell, Unix/Linux, NumPy, scikit-learn, Docker, Docker Compose, Vagrant, K3s/Kubernetes, k3d, Argo CD, HTTP, WebSockets.

**Exploring:** distributed-systems design, ML systems, AI-workload infrastructure, and scalable system architecture.
