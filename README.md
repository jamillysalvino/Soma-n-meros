```
soma-numeros/
│
├── README.md
├── .gitignore
└── soma.py
```

```markdown
# Soma de Números

```bash
python soma.py
```
```

```
__pycache__/
*.pyc
```

- **soma.py**: O script Python que realiza a soma.

```python
# soma.py

def somar(a, b):
    return a + b

if __name__ == "__main__":
    try:
        num1 = float(input("Digite o primeiro número: "))
        num2 = float(input("Digite o segundo número: "))
        resultado = somar(num1, num2)
        print(f"A soma de {num1} e {num2} é {resultado}.")
    except ValueError:
        print("Por favor, insira apenas números.")
```# Soma-n-meros
