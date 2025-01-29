# Web-Scraping

Este projeto foi desenvolvido para automatizar a busca de vagas de emprego na área de Dados em diferentes empresas. Utilizando web scraping e threading, a automação busca vagas em múltiplos sites ao mesmo tempo, otimizando a execução e oferecendo uma resposta rápida.

A automação acessa sites de empresas como Ifood, Nubank, C6 Bank, PicPay, Itaú, e Santander, realizando pesquisas específicas e extraindo o número de vagas abertas para cargos relacionados a dados, como Analista de Dados, Engenheiro de Dados, Analytics Engineer, entre outros.

# 🛠️ Tecnologias Utilizadas

Python: Principal linguagem utilizada para desenvolvimento da automação.
Selenium: Ferramenta utilizada para realizar web scraping, interagindo com as páginas de emprego.
Threading: Utilizado para executar as buscas simultaneamente, otimizando o tempo de execução.
Re: Usado para filtrar e tratar as ocorrências de palavras-chave nos textos extraídos das páginas.

# ⚙️ Como Funciona
Configuração do Navegador: A automação configura o Selenium para abrir as páginas das empresas e realizar buscas no campo de vagas.
Execução das Buscas: Para cada site, são feitas buscas específicas para identificar vagas abertas relacionadas à área de dados.
Exibição dos Resultados: Os resultados são exibidos de forma formatada, com a quantidade de vagas encontradas em cada empresa, usando cores para destacar a disponibilidade de vagas (verde para muitas vagas, laranja para poucas e vermelho para nenhuma).

![image](https://github.com/user-attachments/assets/5a9de281-fef0-4534-8382-63980c938bd3)

# 🔥 Desafios
Peculiaridades de cada site: Cada empresa tem uma estrutura diferente e exige um tratamento específico no código. Alguns sites exigem rolar a página, enquanto outros carregam novas abas com os resultados.
Desempenho: No início, o código estava executando as buscas de forma sequencial, o que resultava em um desempenho mais lento. Após a implementação de threading, consegui otimizar o processo e rodar múltiplas buscas simultaneamente.

# 👨‍💻 O que Aprendi
Este projeto me ajudou a melhorar minhas habilidades com Selenium, além de ter me ensinado a otimizar código utilizando threading para lidar com tarefas simultâneas. Aprendi a trabalhar com diversos tipos de sites, lidando com a forma como cada um estrutura suas páginas.

