# Contributing to k8s-pod-analyzer

Thanks for your interest in contributing! 🎉

## 🚀 Quick Start

```bash
# Fork and clone the repo
git clone https://github.com/YOUR_USERNAME/k8s-pod-analyzer.git
cd k8s-pod-analyzer

# Install dependencies
go mod tidy

# Build
go build -o pod-analyzer .

# Run tests
go test ./...
```

## 🎯 How to Contribute

### 🐛 Report Bugs
- Open an issue with `bug` label
- Include: OS, Go version, steps to reproduce
- Add logs/screenshots if possible

### 💡 Suggest Features
- Open an issue with `enhancement` label
- Describe the use case
- Explain why it's useful

### 🔧 Submit PRs
1. Fork the repo
2. Create feature branch: `git checkout -b feature/amazing-feature`
3. Commit: `git commit -m 'feat: add amazing feature'`
4. Push: `git push origin feature/amazing-feature`
5. Open PR

## 📝 PR Guidelines

- Follow existing code style
- Add tests for new features
- Update documentation
- Keep PRs focused (one feature per PR)

## 🏷️ Commit Convention

```
feat:     New feature
fix:      Bug fix
docs:     Documentation
style:    Formatting
refactor: Code restructuring
test:     Adding tests
chore:    Maintenance
```

## 🎯 Good First Issues

Looking for where to start? Check these:

- [ ] Add `--output yaml` format
- [ ] Implement `--label-filter` flag
- [ ] Add `--since` time filter
- [ ] Create Helm chart for deployment
- [ ] Add more unit tests

## ❓ Questions?

Open a discussion or reach out on LinkedIn!

---

Thanks for contributing! 🙌
