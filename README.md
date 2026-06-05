# 🏦 Bank C

Simulação de um sistema bancário simples construído em **C**, rodando direto no terminal. Permite criar contas, realizar saques, depósitos e transferências entre contas — tudo em memória.

### 📸 Preview

![Preview do sistema](assets/preview.PNG)

### 🚀 Funcionalidades

- ✅ Criar conta com dados do cliente
- ✅ Efetuar saque (com suporte a uso de limite)
- ✅ Efetuar depósito
- ✅ Efetuar transferência entre contas
- ✅ Listar todas as contas cadastradas
- ✅ Data de cadastro gerada automaticamente pelo sistema

### 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| C | Linguagem principal |
| GCC / MinGW | Compilador |
| Windows API | `Sleep()` e suporte ao console |

### ⚙️ Como rodar

1. Clone o repositório

```bash
git clone https://github.com/ericktechx/banco-simples-c.git
cd Banco-simples-C
```

2. Compile

```bash
gcc src/main.c -o src/output/main.exe
```

3. Execute

```bash
./src/output/main.exe
```

### 📌 Observações

- Os dados existem apenas em memória — ao fechar o programa, tudo é perdido.
- O sistema suporta até **50 contas** simultâneas.
- Ao realizar um saque ou transferência com saldo insuficiente, o valor restante é descontado do limite da conta.
- Projeto desenvolvido com fins de aprendizado de structs, funções e lógica de programação em C.

### 🤝 Contribuindo

Projeto simples e em desenvolvimento, toda contribuição é bem-vinda!

- 💡 Sugestões e ideias
- 🔧 Melhorias no código
- ⭐ Se gostou do projeto, deixa uma estrela!
