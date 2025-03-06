# roxinha.vis 🟣📊

O **roxinha.vis** é um projeto pessoal desenvolvido para realizar análises de streamers da Twitch 🟣, comparando o desempenho de canais de um mês para outro. Ele gera gráficos 📈 e relatórios em formato **.docx** que mostram o crescimento de seguidores, tempo assistido, tempo streamado, e muito mais.

Este projeto foi feito para facilitar a visualização de desempenho de streamers 🎮, melhorar apresentações/relatórios mensais 📑 e para auxiliar em escolhas estratégicas para campanhas 🎯.

---

### Tecnologias Usadas ⚙️

Este projeto foi desenvolvido usando as seguintes tecnologias e bibliotecas:

- **Python 🐍**: Linguagem de programação usada para implementar a lógica e manipulação de dados.
- **Flask 🚀**: Framework para criar a aplicação web.
- **Pandas 🧑‍💻**: Biblioteca para manipulação e análise de dados em formato de tabelas (DataFrames).
- **Matplotlib 📊**: Biblioteca para gerar gráficos.
- **python-docx 📄**: Biblioteca para criar documentos no formato **.docx**.
- **Requests 🌐**: Biblioteca para fazer requisições HTTP e baixar imagens.

---

### Funcionalidades 🔧

O **roxinha.vis** permite comparar dados de streamers de dois meses diferentes. Ele gera:

- **Relatórios de Crescimento 📈**: Mostra a evolução do número de seguidores, horas assistidas e horas streamadas entre dois meses.
- **Gráficos 📊**: Gera gráficos de pizza mostrando o tempo assistido dos 10 principais streamers de cada mês.
- **Relatórios em formato .docx 📑**: Gera relatórios completos que podem ser baixados e compartilhados.

---

### Importante ⚠️

Pro projeto funcionar corretamente, os arquivos inseridos devem ser da plataforma [Sullygnome🌐](https://sullygnome.com/), que coleta números de streamers da Twitch. Por lá, você encontrará os jogos desejados e poderá filtrar por mês para gerar o CSV.

---

### Como Rodar o Projeto 🚀

Certifique-se de ter o [PyCharm](https://www.jetbrains.com/pycharm/download/?section=windows) instalado em sua máquina.

**Versão Python: [3.9.12](https://www.python.org/downloads/windows/)**

### → Passo 1: Clonar o Repositório 🧑‍💻

Primeiro, é necessário clonar o repositório para sua máquina local. Para isso, abra o terminal e execute o seguinte comando:

```bash
git clone https://github.com/vanessayukari/roxinha-vis.git
```
```
cd roxinha-vis
```

### → Passo 2: Criar um Ambiente Virtual (opcional, mas recomendado) 🌱

É uma boa prática usar um ambiente virtual para o seu projeto. Isso ajuda a isolar as dependências do projeto e evita conflitos com outros pacotes que você possa ter instalado globalmente.

Crie um ambiente virtual com o seguinte comando:

```
python -m venv .venv
```

### → Passo 3: Ativar o Ambiente Virtual 💻

Após criar o ambiente virtual, ative-o:

No Windows:
```
.venv\Scripts\activate
```

No macOS/Linux:
```
source .venv/bin/activate
```

### → Passo 4: Instalar as Dependências 📥

Agora que o ambiente virtual está ativado, instale as dependências do projeto:

```
pip install -r requirements.txt
```

### → Passo 5: Rodar a Aplicação ⚙️

Com as dependências instaladas, você pode iniciar a aplicação Flask. Execute o seguinte comando no terminal:

```
python app.py
```

### → Passo 6: Acessar a Aplicação 🌐

Abra o navegador e acesse a URL: http://127.0.0.1:5000/

No site, você poderá fazer o upload de dois arquivos CSV contendo os dados dos streamers que deseja analisar.

### → Passo 7: Fazer o Upload dos Arquivos ⬆️

1. Selecione os arquivos CSV para o **Mês 1** e **Mês 2**;
2. Escolha os meses e anos que você está comparando;
3. Preencha o **jogo** para a análise;
4. Clique no botão para gerar a análise e fazer o download do arquivo gerado;

Após isso, você verá os resultados da comparação entre os streamers dos dois meses, juntamente com gráficos gerados e a opção de baixar os dados em formato **.docx**.

### → Passo 8: Baixar os Resultados 📥

Após a análise ser gerada, você poderá baixar o arquivo de resultados (que será compactado em um arquivo **.zip**) contendo:

- O arquivo **.docx** com a análise detalhada.
- Os gráficos gerados no formato **.png**.

Isso pode ser feito clicando no link de download disponível.

Agora é só guardar a pasta compactada com os arquivos para auxiliar em suas estratégias, apresentações etc. 🙂

---

### Não sou dev, e agora? 🌟
Você, **Influencer Manager**, precisa de ajuda para que o projeto funcione corretamente no seu PC? Entre em contato comigo por e-mail: vaneyukari@outlook.com

Vai ser um prazer te ajudar (=ↀωↀ=)
