
# Sistema Gerenciador de Senhas com Generative AI

## Inspirado no curso de imersão Gemini AI da Alura.

Este projeto utiliza o poder do Gemini AI para gerenciar suas senhas de forma segura e inovadora. Através de um arquivo JSON criptografado, você pode armazenar suas senhas e recuperá-las facilmente utilizando o embedding do Gemini.
### Funcionalidades:
Criptografa um arquivo JSON ("vault.txt") contendo suas senhas, gerando um arquivo criptografado ("vault.cri") utilizando uma chave de criptografia ("chave.key") para garantir a segurança das informações.

Recupera senhas através da descrição da mesma, utilizando o Gemini AI para encontrar a senha correspondente no arquivo descriptografado.

Estrutura do arquivo:
### vault.txt

```
{
  "data": [
    {
      "key": "WhatsApp",
      "description": "Senha do WhatsApp",
      "value": "abcdef"
    },
    {
      "key": "Windows",
      "description": "Senha do Windows",
      "value": "ghijkp"
    },
    {
      "key": "Ubuntu",
      "description": "Senha do Ubuntu",
      "value": "papai_precisa"
    },
    {
      "key": "Alura",
      "description": "Senha da plataforma Alura",
      "value": "mamae_mandou"
    }
  ]
}

```

Uma vez gerado o arquivo "vault.cri", armazene os arquivos "vault.txt" e "chave.key" em um local seguro.

### Melhorias Futuras:

1. Implementar algoritmos de criptografia mais robustos, como AES.
2. Desenvolver interfaces gráficas intuitivas para o usuário.
3. Expandir a quantidade de informações armazenadas sobre cada senha.

### Como Usar:
Crie seu arquivo "vault.txt" seguindo a estrutura acima.
Execute o notebook Colab para gerar a chave de criptografia ("chave.key") e criptografar o "vault.txt" em "vault.cri".
Utilize o código fornecido para interagir com o arquivo "vault.cri", descriptografá-lo e recuperar senhas através do Gemini AI.

*__Contribuições:__
Sinta-se à vontade para contribuir com este projeto!*

