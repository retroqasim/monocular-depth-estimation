# 🤝 Contributing to Monocular Depth Estimation with MiDaS

Thank you for your interest in contributing! Here's how you can help.

## 📋 How to Contribute

### Reporting Bugs

1. Check the [Issues](../../issues) page to see if the bug has already been reported
2. If not, open a new issue with:
   - A clear, descriptive title
   - Steps to reproduce the problem
   - Expected vs. actual behavior
   - Screenshots if applicable
   - Your environment details (Python version, GPU, OS)

### Suggesting Features

1. Open a new issue with the `enhancement` label
2. Describe the feature and why it would be useful
3. Include examples or mockups if possible

### Submitting Changes

1. **Fork** the repository
2. **Create** a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes with clear messages:
   ```bash
   git commit -m "Add: brief description of what you added"
   ```
4. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open** a Pull Request with a clear description of the changes

## 💡 Ideas for Contributions

- Add support for additional depth estimation models (e.g., ZoeDepth, Depth Anything)
- Create a Gradio or Streamlit web interface
- Add 3D point cloud generation from depth maps
- Implement depth-based image effects (bokeh, fog, relighting)
- Add quantitative evaluation metrics (RMSE, AbsRel, etc.)
- Improve video processing performance
- Add support for webcam/real-time depth estimation

## 📐 Code Style

- Follow [PEP 8](https://pep8.org/) for Python code
- Use clear, descriptive variable names
- Add comments for non-obvious logic
- Keep notebook cells focused and well-documented

## 📄 License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
