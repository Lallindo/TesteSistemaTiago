# TesteSistemaTiago

Ramo "BEB" -> BackEnd Branch;
Ramo "FEB" -> FrontEnd Branch;

O motivo deste repositório é experimentar com o sistema de Merging do gitHub. Foram criados dois ramos cujos nomes são expostos acima, esses ramos foram preenchidos com arquivos NÂO FUNCIONAIS que IMITAM a estrutura comum de um sistema. O Merge foi feito com arquivos README diferentes em cada branch para testar o funcionamento da ferramenta de solução de conflitos. As branches criadas não foram excluidas para que possam ser avaliadas posteriormente.

Passo a passo utilizado:
1 - O repositório foi criado a partir da plataforma on-line do github que dá a opção de gerar automáticamente o arquivo README.md;
2 - O repositório foi clonado usando **git clone endereço_do_repositório**;
3 - Foram criados dois ramos: BEB que representa mudanças ao BackEnd e FEB que representa mudanças ao FrontEnd;
4 - Nas branches, o arquivo README.md foi alterado para ser visto pelo comando **git status** como não rastreados. Cada README foi alterado de modo diferente para gerar um conflito com o objetivo de testar o que aconteceria nesse caso;
5 - Os arquivos foram adicionados em pastas para melhor organização dos dados e para conseguir chegar ao mínimo de 5 commits por ramo; 
5.1 - Os commits foram feitos usando a sequência: **git status**, **git add .**, **git commit -m "mensagem"** e **git push origin ramo**;
6 - Após todos os commits serem feitos a um ramo, foi utilizado o comando **git checkout nome_do_outro_ramo** para alterar o ramo. Após isso faremos o passo 5.1 novamente até que todos os arquivos sejam adicionados ao repositório;
