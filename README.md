## Relatório Diário do Mercado Financeiro
Este projeto em Python coleta dados econômicos do mercado financeiro (cotações e taxas de juros) e gera gráficos para compor um relatório diário. Em seguida, o relatório é enviado por e-mail automaticamente.

## Funcionalidades
Coleta de dados da Selic, IPCA, CDI, IGP-M, Dólar, Euro e Libra através de APIs.
Geração de gráficos utilizando Matplotlib (com estilo Cyberpunk).
Criação de um relatório diário em HTML com gráficos embutidos.
Envio do relatório por e-mail utilizando o smtplib do Python.

## Pré-requisitos
Python 3.x
Bibliotecas Python:
requests
pandas
matplotlib
mplcyberpunk
python-bcb (para dados econômicos do Banco Central)
Instale as dependências com:

```bash
Copiar código
pip install requests pandas matplotlib mplcyberpunk python-bcb
```

## Configuração
Clone este repositório:

```bash
Copiar código
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
```

## Substitua os campos de email e senha no código:

```python
Copiar código
email = "seu_email@gmail.com"
senha_do_email = "sua_senha"
```

Caso prefira manter a senha do email em um arquivo senha.txt, crie um arquivo no mesmo diretório e adicione a senha.

Certifique-se de que as APIs estejam disponíveis e funcionando antes de executar o script.

## Resultados
Gráficos gerados:
  Gráfico da Taxa Selic ao longo do tempo.
  Gráfico comparativo do IPCA e IGP-M.
  Gráfico de cotações do Dólar e Euro.
Arquivos anexados ao e-mail:
  selic.png: Gráfico da Selic.
  inflacao.png: Gráfico comparativo do IPCA e IGP-M.
  grafico_dolar_euro.png: Gráfico das cotações do Dólar e Euro.
  cotacoes_dolar_euro.xlsx: Tabela de cotações do Dólar e Euro.
## Observações
  O código precisa ser adaptado para incluir seus dados de e-mail e senha, garantindo a segurança dessas informações.
  O envio de e-mails utiliza o servidor SMTP do Gmail (porta 465). Verifique as configurações de segurança da sua conta para habilitar o uso de aplicativos menos seguros.
  As APIs utilizadas para coleta de dados são públicas, mas podem ter limites de requisições por hora.

## Contato
Se você tiver alguma dúvida, feedback ou sugestão, não hesite em entrar em contato comigo:

E-mail: pablo.henriquelima07@gmail.com  
LinkedIn: https://www.linkedin.com/in/pablo-henrique-lima-542300164/    

Agradeço pela sua visita!
