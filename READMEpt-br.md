# 🔐 Caesar's Encryption - Cifra de César com Substituição de Símbolos

## 📌 Visão Geral
Este projeto desenvolvido em Python implementa a clássica **Cifra de César** com uma camada adicional de segurança através de substituição por símbolos. Ele permite criptografar e descriptografar mensagens de forma interativa, com opção de salvar os resultados em arquivo.

## ✨ Funcionalidades Principais
- **Criptografia avançada**: Combina deslocamento alfabético com substituição por símbolos
- **Processo interativo**: Interface amigável via linha de comando
- **Armazenamento seguro**: Salva textos criptografados automaticamente
- **Descriptografia precisa**: Recupera a mensagem original com a chave correta

## 🛠️ Como Funciona

### 🔒 Criptografia
1. Usuário insere o texto a ser criptografado
2. Fornece uma chave numérica (inteiro)
3. O programa:
   - Desloca cada letra pelo valor da chave (ex: chave 3: 'a' → 'd')
   - Realiza substituições adicionais por símbolos especiais
   - Salva o texto cifrado em arquivo (na pasta de documentos)

### 🔓 Descriptografia
1. Usuário fornece o texto criptografado
2. Informa a mesma chave usada na criptografia
3. O programa:
   - Reverte as substituições de símbolos
   - Aplica o deslocamento inverso (subtrai a chave)
   - Exibe a mensagem original no console

## ⚙️ Tecnologias Utilizadas
- **Python 3** (linguagem principal)
- **Bibliotecas padrão**: os, string, etc.
- **Armazenamento**: Arquivos TXT na pasta de documentos


## 📚 Documentação Adicional
- A cifra mantém a capitalização das letras originais
- Caracteres não-alfabéticos permanecem inalterados
- O sistema é circular (após 'z' volta para 'a')

## 👨‍💻 Desenvolvedor
**Heitor Carnielo Janko**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heitor-carnielo-janko-873bb1348/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HelloBigBoi124)

---

> "A criptografia é a arte de proteger informações - uma necessidade na era digital."  
> 🔐 Segurança digital começa com algoritmos simples!
