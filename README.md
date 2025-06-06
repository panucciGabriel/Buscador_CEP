# Buscador de CEP

Buscador de CEP é um projeto Java simples que permite consultar endereços brasileiros a partir de um CEP, consumindo a API pública do ViaCEP e salvando o resultado em um arquivo JSON.

---

## Funcionalidades

- Consulta o endereço completo a partir do CEP informado pelo usuário.
- Consome a API ViaCEP para obter dados atualizados e confiáveis.
- Gera um arquivo JSON formatado contendo as informações retornadas para fácil consulta futura.
- Tratamento básico de erros para CEPs inválidos ou falha na consulta.

---

## Tecnologias

- Java SE 24
- Biblioteca Gson para manipulação JSON

---

## Como executar

1. Clone este repositório.
2. Compile o projeto:
   ```bash
   javac *.java 
