# GNL (GNL is not Langchain)

## Introduction
The current AI era is dominated by numerous large language models (LLMs). These LLMs are driven by APIs or local GPU or CPU-based systems, which are diverse and often unorganized. Historically, attempting to consolidate multiple systems into one solution has been challenging and often results in inefficiencies.

However, LLMs do not require strictly structured input/output formats, allowing for the integration of multiple LLM systems, as seen in frameworks like Langchain or LlamaIndex. Unfortunately, these systems can be difficult for users who cannot use Python or JavaScript, and their code can be complex and hard to understand.

This problem arises because users must choose the proper method to achieve their goals, which can be a hurdle for beginners and those accustomed to traditional coding. Considering that coding is evolving beyond human capabilities, we need a new approach.

Introducing GNL (GNL is not Langchain), a system that focuses on enabling LLMs to understand and create nodes or edges to form a cohesive LLM system. GNL aims to simplify the integration and usage of various LLMs without requiring extensive coding knowledge.

## Installation
To install GNL, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gnl.git
   ```
2. Install dependencies:
   ```bash
   cd gnl
   pip install -r requirements.txt
   ```

## Quick Start Guide
Here's a quick example to get you started with GNL:

```python
from gnl import GNL

# Initialize GNL
gnl = GNL()

# Example usage
response = gnl.query("Hello, GNL!")
print(response)
```

## Features
- **Easy Integration**: Seamlessly integrates various LLMs.
- **User-Friendly**: Requires minimal coding knowledge.
- **Scalable**: Compatible with API-based, local GPU, or CPU LLMs.
- **Flexible**: Allows dynamic creation of nodes and edges.

## Usage
To use GNL, follow these steps:

1. **Initialize GNL**:
   ```python
   gnl = GNL()
   ```
2. **Query GNL**:
   ```python
   response = gnl.query("Your query here")
   ```

## Examples
Here are some examples of how to use GNL in different scenarios:

### Example 1: Basic Query
```python
response = gnl.query("What is the capital of France?")
print(response)  # Output: "Paris"
```

## FAQ
### Q: Can I use GNL without Python?
A: Currently, GNL is designed for Python, but we are working on supporting other languages in the future.

## Contributing
We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) to get started.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact Information
For further questions or feedback, please contact us at [email@example.com](mailto:email@example.com).
