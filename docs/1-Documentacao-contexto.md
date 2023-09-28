# 1. Introdução

Gerenciamento de abrigo de animais (adoções, animais, estoque) 

CLIENTE:
Gabriel Coetti


#### 1.1 Entidades Encontradas
Animal, Tutor, Estoque, Doadores, Produto.


#### 1.2 Contexto das Entidades
Animais: Destinada aos animais resgatados pela instituição.

Tutores: Representa os adotantes dos animais.

Estoque: A entidade e usada para um controle de produtos doados e consumidos pelos animais.

Doadores: Seu contexto se resume a aqueles que ajudam o abrigo por meio de doações.

Produtos: Recebe da entidade Doadores, o produto doado.

#### 1.3  Levantamento Inicial Entidades x Atributos
| Entidade              | Atributos |  
| :----------------: | :------: | 
| Animais       |   • Nome <br> •Raça <br> •Cor <br> •Data do resgate <br>• Observação <br>•  | 
|Estoque          |  •Nome do produto <br>•Código do doador <br>•Quantidade doada <br>•   | 
| Tutores     | •Nome do tutor <br>•Endereço <br>•Telefone    | 
|  Produtos |  •Nome do produto <br>•Quantidade de produtos   | 

Animais: Entidade reponsvél pelos atributos dos animais para adoção. ou seja, abrangindo especie (responsavél pela diferença entre cães e gatos) sáude, idade, porte, castração e sexo.

Adotantes: 

