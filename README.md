![Uploading Decodificador de texto.PNG…]()


# Challenge Decodificador de Texto - ONE | Alura
O projeto envolve a criação de um decodificador de texto,  desenvolvido como parte de um desafio do programa Oracle Next Education em colaboração com a Alura. O projeto visa criar uma aplicação capaz de criptografar e descriptografar mensagens de texto, oferecendo uma oportunidade prática para aplicar conhecimentos técnicos em uma situação próxima à realidade profissional.

## ⚙ Features

* Criptografia por Substituição de Vogais

  * Letra "e" é substituída por "enter"
  * Letra "i" é substituída por "imes"
  * Letra "a" é substituída por "ai"
  * Letra "o" é substituída por "ober"
  * Letra "u" é substituída por "ufat"

* Conversão de Caracteres Especiais para Espaços em Branco

  * O texto digitado é normalizado para decompor caracteres acentuados em suas partes básicas. Em seguida, os acentos são removidos, transformando caracteres como "é" em "e". Após a remoção dos acentos, o texto é processado novamente para eliminar todos os caracteres que não sejam letras (a-z, A-Z), números (0-9) ou espaços. Isso inclui pontuação, símbolos matemáticos, monetários e outros caracteres especiais. O texto processado, agora sem acentos e caracteres especiais, é atualizado no campo de texto, garantindo que o conteúdo fique limpo e conforme esperado.
  
  * Exemplos dos caracteres especiais:
    * Pontuação: !, @, #, $, %, ^, &, *, (, ), _, +, -, =, {, }, [, ], |, \, :, ;, ", ', <, >, ,, ., ?, /
    * Acentos e diacríticos: á, é, í, ó, ú, à, è, ì, ò, ù, â, ê, î, ô, û, ä, ë, ï, ö, ü, ã, ñ, õ, ç
    * Símbolos matemáticos: +, -, =, *, /, %, √, ∞, ≈, ≠, ≤, ≥
    * Símbolos monetários: $, €, £, ¥, ¢, ₹
    * Outros símbolos: ©, ®, ™, §, ¶

* Conversão de Letra Maiúscula para Letra Minúscula
  
  * A conversão de letras maiúsculas para minúsculas foi feita através da estilização CSS no elemento de campo de texto. Isso é realizado utilizando a propriedade text-transform: lowercase; aplicada ao ID text__area, que é o campo onde o usuário digita o texto.
 
* Botões Funcionais
  * <b>Encrypt</b>: Criptografa o texto inserido no campo de entrada. Após a criptografia, o texto é transferido para o campo de saída.
  * <b>Decrypt</b>: Descriptografa o texto inserido no campo de entrada. Após a descriptografia, o texto é transferido para o campo de saída.
  * <b>Copy</b>: Copia o conteúdo do campo de saída para a área de transferência.

* Validações de Entrada
  * <b>Desativação dos Botões</b>: Os botões Encrypt e Decrypt são desativados se o campo de entrada estiver vazio ou contiver apenas espaços em branco.
  * <b>Exibição de Alerta</b>: Um alerta é exibido ao usuário quando tenta acionar os botões Encrypt ou Decrypt sem fornecer um texto válido.
 
## 🛠️ Ferramentas Utilizadas
* JavaScript: Utilizado para implementar a lógica de criptografia e descriptografia, manipulando e validando o texto inserido pelo usuário.

* HTML: Estrutura a interface do usuário, incluindo os campos de entrada e saída de texto, bem como os botões de ação.

* CSS: Responsável pela estilização da aplicação, garantindo uma interface visualmente agradável e responsiva.

* Git: Utilizado para controle de versão, permitindo acompanhar o desenvolvimento do projeto e gerenciar alterações no código.
* Visual Studio Code: Editor de código escolhido para escrever e depurar o código-fonte, aproveitando suas funcionalidades como extensão de plugins e integração com Git.

## 💡Funcionalidade
O codificador de texto é projetado para trabalhar exclusivamente com letras minúsculas, números e espaços, excluindo acentos e caracteres especiais.

* Filtragem de Entrada: O sistema permite apenas letras minúsculas, números e espaços. Qualquer caractere diferente, como acentos e símbolos especiais, é removido automaticamente.

* Remoção de Acentos: Quando o texto é digitado, ele é normalizado para decompor caracteres acentuados. Por exemplo, "é" é transformado em "e" sem acento. Em seguida, os acentos são removidos, resultando apenas nas letras básicas.

* Remoção de Caracteres Especiais: Após a remoção dos acentos, todos os caracteres que não sejam letras, números ou espaços são eliminados. Isso remove pontuações e símbolos não permitidos.

* Atualização do Campo de Texto: O texto limpo, agora livre de acentos e caracteres especiais, é exibido no campo de texto. Apenas letras minúsculas, números e espaços são permitidos.

* Criptografia: Após a limpeza e normalização do texto, ele é criptografado usando um algoritmo específico. O texto criptografado é então exibido no campo apropriado. A criptografia garante que o texto original seja transformado em uma forma segura e ilegível. 

* Colar e Descriptografar: Usuários podem colar texto no campo que já foi criptografado anteriormente. O sistema aplica as mesmas regras de filtragem para garantir que o texto colado esteja em conformidade com os requisitos, permitindo uma descriptografia correta.

Deploy: https://gustavo21ferreira.github.io/decodificador--texto/

