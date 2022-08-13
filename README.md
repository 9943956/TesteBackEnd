# Perguntas
## 1) Você acha que este código está estruturado, legível e escalável?
R:O código é bem estruturado, porém não possui comentários o que não é uma boa prática e dificulta a legibilidade, para se tornar um código escalável são necessários alguns atributos como organização, boa documentação, o código possui boas nomenclaturas, mas para determinar se um código é escalável é necessário ser analisado por algúem que tem forte dominio da tecnologia usada no desenvolvimento, pois não é algo fácil/óbvio de ser determinado. Além de tudo um iniciante no mundo de desenvolvimento procura primeiramente acertar para apenas depois de uma certa experiência começar a escrever um código escalável.


## 2) O que você mudaria nos arquivos e na estrutura de pastas para melhorá-lo nesse sentido?
R: Tentaria mudar alguns aspectos para tentar manter as coisas mais simples e legíveis possível, IF's também trazem complexidade ao código e devem ser evitados sempre que possível, problemas resolvidos superficialmente também trazem re-trabalho futuramente, então tentaria implementar uma solução mais conclusiva e gastaria um tempo a mais buscando a causa raiz do problema, invés de implementar uma solução temporária.


## 3) Quanto a arquitetura API e sua conteinerização, liste as brechas de segurança que você identificou neste código? Como você as resolveria?
R:Resolveria algumas brechas de segurança implementas algumas medidas, consigo visualizar uma implementação de Autorização e autenticação, talvez uma HTTP basic. Caso haja uma quebra na autenticação e falhas, é essencial aplicar uma criptografia, por exemplo protocolo HTTP. Monitoramento do desempenho e disponibilidade da API para identificar possíveis ameaças, aplicação de testes com uma certa recorrência também é uma maneira interessante de verificar se as informações do usuário estão sendo protegidas.


