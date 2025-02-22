# Chatbot Acadêmico - Kinho

Protótipo de chatbot de uso acadêmico. Projetado para embarcar em sistema Linux.

![Kinho chatbot](images/chatbotEmFuncionamento.png)

Para visualizar o projeto, execute o comando:

```
python3 interface.py
```

## Caso não consiga executar

Kinho pode estar exigindo algumas bibliotecas que não estão instaladas na sua máquina. Os requisitos de software são:

* python 3.6.9 - Acesse [este link](https://www.python.org/downloads/) para fazer o download

As seguintes bibliotecas são necessárias para executar o projeto:

* numpy==1.19.5
* nltk==3.6.7
* sklearn==0.24.2
* tkinter==8.6
* simpleaudio==1.0.4
* SpeechRecognition==3.8.1
* PyAudio==0.2.11

Para instalá-las, digite os comandos no terminal:

```
sudo apt-get install python3.6-tk
pip3 install numpy==1.19.5
pip3 install --user -U nltk==3.6.7
pip3 install -U scikit-learn==0.24.2
pip3 install SpeechRecognition==3.8.1
pip3 install simpleaudio==1.0.4

```

* Por fim, descomente as linhas de código do arquivo `IFCEbot.py`:

```
nltk.download('omw-1.4') # for first-time use only.
nltk.download('punkt')   # for first-time use only
nltk.download('wordnet')    # for first-time use only
```

Caso você ainda não conseguir executar este projeto, pode entrar em contato através do meu email.

## Autores

Ana Carolina Silva Abreu - ana.carolina.silva05@aluno.ifce.edu.br

Erik Jhones Freitas do Nascimento - erik.jhones06@aluno.ifce.edu.br

Filipe de Almeida Lira - filipe.almeida.lira04@aluno.ifce.edu.br

Sandro César Silveira Jucá - sandrojuca@ifce.edu.br

Anderson de Castro Lima - anderson@ifce.edu.br
