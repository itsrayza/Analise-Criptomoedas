# Analise-Criptomoedas
🪙 Análise de Preços de Criptomoedas com Médias Móveis
🚀 Este projeto coleta preços de Bitcoin e Ethereum em tempo real usando a API do CoinGecko e gera gráficos com médias móveis para análise de tendências.

📌 Funcionalidades
✅ Coleta automática de preços do Bitcoin e Ethereum
✅ Armazena os preços em um arquivo CSV para análise histórica
✅ Gera gráficos da variação dos preços com médias móveis de 7 e 30 dias
✅ Salva o gráfico como imagem para futuras referências

🛠 Tecnologias Utilizadas
🔹 Python 🐍
🔹 Pandas (manipulação de dados)
🔹 Matplotlib (visualização de dados)
🔹 Requests (requisições à API CoinGecko)

📦 Instalação e Execução
1️- Clone este repositório:
git clone https://github.com/itsrayza/projeto-cripto.git
cd projeto-cripto
2- Crie um ambiente virtual (opcional, mas recomendado):
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
3️- Instale as dependências:
pip install -r requirements.txt
4️- Execute o script:
python main.py


⏳ Automatização (Opcional)
Se quiser rodar o script automaticamente todos os dias, você pode usar o Agendador de Tarefas (Windows) ou Crontab (Linux/Mac).

Exemplo de execução diária no Linux:
crontab -e

Adicione esta linha para rodar o script todo dia às 9h da manhã:
0 9 * * * /usr/bin/python3 /caminho/para/main.py

🤝 Contribuição
Sinta-se à vontade para contribuir! Se tiver sugestões ou melhorias, abra um Pull Request ou entre em contato.
💡 Este projeto foi criado com o objetivo de aprender, evoluir e compartilhar conhecimento. Se ele te ajudou de alguma forma, deixe uma ⭐ no repositório! 
📬 Dúvidas, sugestões ou ideias? Fique à vontade para entrar em contato ou contribuir!
📄 Licença
Este projeto está sob a licença MIT.

"O aprendizado é contínuo. Cada linha de código escrita hoje é um degrau para um futuro brilhante." ✨
Um abraço. Ray.






