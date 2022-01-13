# boleto2net
Versão do Boleto2Net da OpenLine Sistemas baseado num fork do Boleto2net

### Carteiras Homologadas
* Banrisul (041) - Carteira 1
* Bradesco (237) - Carteira 09
* Brasil (001) - Carteira 17 (Variações 019 027)
* Caixa Econômica Federal (104) - Carteira SIG14
* Itau (341) - Carteira 109, 112
* Safra (422) - Carteira 1 e 2
* Santander (033) - Carteira 101
* Sicoob (756) - Carteira 1-01

### Carteiras Implementadas (Falta teste unitário)
* Sicredi (748) - Carteira 1-A

### Carteiras Implementadas (Não foi homologada. Falta teste unitário)
* Banco do Brasil (001) - Carteira 11 (Variação 019)

> Atenção: Para manter a ordem do projeto, qualquer solicitação de Pull Request de um novo banco ou carteira implementada, deverá seguir o formato dos bancos/carteiras já implementados e vir acompanhado de teste unitário da geração do boleto (PDF), arquivo remessa e geração de 9 boletos, com dígitos da linha digitável variando de 1 a 9, checando além do próprio dígito verificador, o cálculo do nosso número, linha digitável e código de barras.

### Pre requisitos
Visual Studio 2017 ou superior

### Por onde comecar
Olhe os projetos de testes, eles contem muita informacao sobre o uso do componente.

