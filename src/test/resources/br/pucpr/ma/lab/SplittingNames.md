# Separação de Nomes

Para ajudar a personalizar nossos lista de e-mail, queremos ter o primeiro nome e sobrenome do cliente.
Infelizmente, os dados do cliente que são fornecidos apenas contém nomes completos.

O sistema, portanto, deve quebrar um nome completo fornecido em seus componentes dividindo
em torno do espaço em branco.

### Exemplo

O nome completo de [Marcelo Freitas](- "#name") é [separado](- "#result = split(#name)") 
com primeiro nome: [Marcelo](- "?=#result.firstName") e último nome: [Freitas](- "?=#result.lastName").