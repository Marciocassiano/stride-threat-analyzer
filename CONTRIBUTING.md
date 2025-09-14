# 🤝 Guia de Contribuição

Obrigado pelo interesse em contribuir com o **STRIDE Threat Analyzer**! 🎉

## 📋 Como Contribuir

### 🐛 Reportar Bugs

1. Verifique se o bug já não foi reportado
2. Use o template de [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
3. Inclua informações detalhadas e passos para reproduzir

### ✨ Sugerir Novas Funcionalidades

1. Verifique se a funcionalidade já não foi sugerida
2. Use o template de [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)
3. Explique o problema que a funcionalidade resolveria

### 💻 Contribuir com Código

1. **Fork** o repositório
2. **Crie** uma branch para sua funcionalidade
3. **Faça** suas alterações
4. **Teste** as mudanças
5. **Submeta** um Pull Request

## 📏 Padrões de Código

### Python
```python
# Use black para formatação
black app/ tests/

# Use isort para imports
isort app/ tests/

# Use flake8 para linting
flake8 app/ tests/

# Use mypy para type checking
mypy app/
