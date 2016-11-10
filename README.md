# 1MNEWS
## 1 Maio News
	
Bem vindos(as) ao repositório do 1MNEWS, se vocês estão vendo este arquivo então quer dizer 
que se intereçaram em contribuir conosco, aqui estão alguns detalhes técnicos de criação
 e manutenção deste repositório e detalhes de como o site é feito.

> Desenvolvedor de Infra: Magno Reis

### Detalhes

- Estes códigos estão sob **The MIT License (MIT)**;
- Caso utilizem estes códigos dê um **fork**;
- O 1MN é administrado por alunos do Colégio Estadual 1º de Maio;
- A equipe do 1MN exime-se de qualquer atitude provocada pelo conteúdo, o 1MN apenas comunica
 os fatos, caso tenha algum conteúdo que lhe causa incômodo por favor entre em contato conosco;
- O 1MN é mantido por equipes responsáveis por áreas do 1MN;

# Equipe
Legendas:
- Responsável: Lidera/Gerencia a equipe, responsável por coordenar os integrantes do mesmo.
- Integrante: Executa a função daquela equipe, subordinado ao Responsável da equipe.

 
### Core team
> Equipe principal, responsável por supervisionar as outras equipes, gerenciamento de membros, 
além  de tomar decisões importantes.

- Magno Reis
- Lorena Carvalho
- Caroline Souza

## Desenvolvimento
> **Responsável por**: Criar, editar e idealizar códigos, ferramentas e design do 1MN. Mantém o
 site funcionando realizando manutenções, administra as dependências do repositório. 
Gerencia a infraestrutura.

### Responsável
- Magno Reis

### Integrante
- Vago
- Vago

##Conteúdo
> **Responsável por**: Criar, editar e moderar do conteúdo do 1MN. Publicações são passadas
 para aprovação da equipe de Conteúdo.

### Responsável
- Lorena Carvalho

### Integrante
- Vago
- Vago
- Vago
- Vago

## Imagem
> **Responsável por**: Publicar, editar ou até criar imagens/fotografias para o 1MN. Fotos serão 
passadas para uma aprovação pela equipe de Imagem.

### Responsável
- Caroline de Jesus

### Integrante
- Vago
- Vago

# Contribuindo

O 1MN é uma comunidade aberta onde qualquer pessoa poderá contribuir seguindo as normas:
	1. Ser um membro do C.E. 1º de Maio;
	2. Não violar nenhum direito constitucional ou regional/estadual/nacional;
	3. Aceitar de que sua contribuição será passada por avaliação;
	4. Responsabilizar-se de qualquer ato cometido;
**Obs.:** Estas normas podem ser alteradas a qualquer momento, mantenha-se informado 
sobre as mudanças.



# Desenvolvimento

	A equipe de desenvolvimento criou uma série de normas de Infraestrutura, para o repositório 
trabalhar com êxito e não obtermos falhas.

#### Branches
	**beta:** Estágio de desenvolvimento.
	**aurora:** Quando os arquivos são desenvolvidos, são mandados para a Aurora onde serão feitas
as alterações finais, correções e melhorias.
	**haskell:** Exclusivo para equipe de Imagem e Conteúdo, publicações e imagens são idealizadas
nesta branch onde será passada para o próximo estágio.
	**nightly:** Onde os arquivos finais são testados e passados para a aprovação ou descartados pelo 
Responsável da equipe, os arquivos descartados são excluídos da branch e não serão repassados para
 o estágio final.
	**nemerle:** É o estágio final, onde os arquivos passados por aprovação são alocados para serem 
lançados. A nemerle nos dá uma última chance de repensarmos e também uma ótima segurança no código 
fonte (source).
	**gh-pages:** Branch responsável pelo conteúdo lançado no 1MN.

#### Estágio de desenvolvimento


|- Conteúdo
|--- haskell |
|----------- nightly (opcional) |
|---------------------------- nemerle |
|---------------------------------------> gh-pages

|- Imagem
|--- haskell |
|---------------------------- nemerle |
|---------------------------------------> gh-pages

|- Desenvolvimento
|-- beta |
|-------- aurora |
|--------------- haskell |
|----------------------- nightly |
|------------------------------- nemerle |
|----------------------------------------> gh-pages



	
