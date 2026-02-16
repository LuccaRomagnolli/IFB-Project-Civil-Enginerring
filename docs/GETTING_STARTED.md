# Guia de Início Rápido

## Configuração Inicial

### 1. Ambiente Virtual

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# ou
venv\Scripts\activate  # Windows
```

### 2. Instalar Dependências

```bash
pip install -r requirements.txt
```

### 3. Explorar o Projeto

- **Análise de Dados**: Acesse `notebooks/` e execute os notebooks Jupyter
- **Código-fonte**: Implementações estão em `src/`
- **Testes**: Execute `pytest tests/` para validar a integridade

## Estrutura de Pastas Explicada

| Pasta | Descrição |
|-------|-----------|
| `datasets/` | Dados brutos e processados |
| `notebooks/` | Análise exploratória e visualizações |
| `src/` | Código-fonte principal do projeto |
| `tests/` | Testes unitários |
| `docs/` | Documentação |
| `config/` | Configurações do projeto |
| `results/` | Resultados e outputs |

## Próximos Passos

1. Leia a documentação em `docs/`
2. Explore os notebooks em `notebooks/`
3. Implemente suas funcionalidades em `src/`
4. Escreva testes em `tests/`

## Ajuda

Para dúvidas, abra uma Issue no repositório.
