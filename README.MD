# Rodar o Projeto de Classificação de Imagens

Este guia explica como preparar o ambiente e executar o notebook principal do projeto.

## 1. Criar um Ambiente Virtual

É recomendado criar um ambiente virtual para garantir que as dependências do projeto não conflitem com outras instalações do sistema.

No terminal, execute:

```bash
# Criar o ambiente virtual (nome sugerido: venv)
python -m venv .venv

# Ativar o ambiente virtual
# Windows
.venv\Scripts\activate

# Terminal Bash
.venv/Scripts/activate
```

> Após ativar o ambiente virtual, você verá o nome do ambiente (por exemplo, `(venv)`) no início do prompt do terminal.

## 2. Instalar Dependências

Com o ambiente virtual ativado, instale todas as dependências necessárias listadas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 3. Rodar o Notebook

O notebook principal do projeto está localizado na pasta `notebook` com o nome `image_classification_sequencial.ipynb`. Para abri-lo e executar:

```bash
# Navegar até a pasta do notebook
cd notebooks

# Iniciar o Jupyter Notebook
jupyter notebook
```

Isso abrirá uma interface no navegador. No navegador, abra o arquivo `image_classification_sequencial.ipynb` e execute as células **na ordem sequencial**.

