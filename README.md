# AI Tools

A collection of AI-powered development tools for rapid prototyping and automated workflows.

## 🛠 Available Tools

### [UI Mock Generation Tools](./tools)

A Python-based utility for generating high-quality UI mockups and design inspiration using the Gemini API.

**Key Features:**

- **Batch Mode:** Generate multiple images simultaneously (ideal for rapid iteration and cost efficiency).
- **Single Mode:** Refine specific prompts with immediate feedback.
- **Support for Reference Images:** Use existing designs as inspiration for image generation.
- **Custom Configuration:** Fine-tune model selection, aspect ratios, and resolution (4K supported).

---

## 🚀 Quick Start

### Prerequisites

- Python 3.9+
- [Gemini API Key](https://aistudio.google.com/apikey)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ivanovishado/ai-tools.git
   cd ai-tools
   ```

2. Set up the environment (see [tools/README.md](./tools/README.md) for detailed instructions):

   ```bash
   cd tools
   python -m venv venv
   source venv/bin/activate  # Windows: .\venv\Scripts\Activate.ps1
   pip install -r requirements.txt
   ```

3. Configure your API key:
   Create a `.env` file in the `tools` directory:
   ```env
   GEMINI_API_KEY=your_actual_api_key_here
   ```

---

## 📂 Project Structure

```text
ai-tools/
├── tools/                # Collection of script-based tools
│   ├── batch_image_gen.py # UI mock generation script
│   └── README.md         # Detailed tool documentation
├── LICENSE               # MIT License
└── README.md             # This file
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Ivan Galaviz**

- GitHub: [@ivanovishado](https://github.com/ivanovishado)
