# funcao-para-url-amigavel
Um simples código para criar URL amigáveis perfeita para seu sistema


Possui problemas com funções para criar URL'S amigáveis? Eu também tinha, porém, com uma simples função agora você poderá realizar a limpeza de string e converter da forma que achar necessária para criar sua url amigável, e o melhor, de forma bem simples.

# Exemplos
você por exemplo, em uma loja virtual poderia usar da seguinte maneira
$url -> $id_produto.'-'.clean($nome_produto);
e sua url ficaria assim: Https://www.seusite.com.br/291-produto-com-url-amigavel-perfeita-sem-acentuacao-e-caracteres-especiais
onde o seu id do produto seria (291) e o nome do produto (Produto com url amigável perfeita sem acentuação e caracteres especiais)
a função clean() irá limpar as strings de onde você usa-lá
# Simples, não? Então aproveite :)
