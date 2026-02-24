
# JARVIS FULL CEO EDITION 🚀

Assistente virtual empresarial completo.

## Recursos:
- Reconhecimento de voz
- Respostas por voz
- Sistema de senha
- Interface de autenticação
- Modo produtividade (abre bloco de tarefas)
- Pesquisa automática
- Abertura de navegador

## Instalação

1. Instale Python 3.10+
2. Instale dependências:

pip install -r requirements.txt

Se houver erro com PyAudio no Windows:
pip install pipwin
pipwin install pyaudio

## Executar

python jarvis.py

## Transformar em .exe

pip install pyinstaller
pyinstaller --onefile --noconsole jarvis.py

O executável ficará dentro da pasta dist.

Senha padrão: 1234
Você pode alterar dentro do código.
