INSTALAÇÃO
pip install selenium
pip install webdriver-manager 

Ao instalar o webdriver-manager, outras bibliotecas neecessárias já serão incluídas
--> Caso haja erro e as bibliotecas nao sejam instaladas, adicione elas manualmente
Bibliotecas e suas versões necessárias:
    attrs==23.2.0
    certifi==2024.2.2
    charset-normalizer==3.3.2
    h11==0.14.0
    idna==3.6
    outcome==1.3.0.post0
    packaging==24.0
    PySocks==1.7.1
    python-dotenv==1.0.1
    requests==2.31.0
    selenium==4.19.0
    sniffio==1.3.1
    sortedcontainers==2.4.0
    trio==0.25.0
    trio-websocket==0.11.1
    typing_extensions==4.11.0
    urllib3==2.2.1
    webdriver-manager==4.0.1
    wsproto==1.2.0

Funcionamento
O código irá abrir o Whatsapp Web para escanear o qrcode. Após escanear aguarde o código enviar a mensagem para o contato
Caso ocorra algum erro no terminal, baixe a extensão Code Runner no VSCODE para executar o código / Selecione ''Code Run''(ctrl+alt+n)

DOCUMENTAÇÃO
Selenium:  https://selenium-python.readthedocs.io
Webdriver Manager: https://pypi.org/project/webdriver-manager/