# Fluxo do Mentoria

Documentação de como funciona o fluxo do Mentoria (esse projeto).

## Issues

As issues precisam de organização e atualizações constantes para garantir que os usuários do projeto (Mentores, Pupilos e "visitantes") estão sendo bem atendidos.

### Fluxo

Quando chega uma issue nova e você começa alguma interação com ela, assine-a para você. Assim ninguém fecha essa issue antes de sua atualização.

Se uma issue já estiver assinada e você quiser contribuir, basta ir atualizando o responsável pela issue o mensionando.

**Labels**

Após abertura da issue devemos adicionar uma label com o assunto relacionado em seu conteúdo, por exemplo `need a mentor` e `javascript`. Sabemos que uma issue com essas labels é de alguém que busca mentoria para o assunto JavaScript.

Quando alguém abre uma issue desejando se tornar um(a) Mentor(a) devemos adicionar a label `mentor candidate` e os skills relacionados para facilitar que Mentores com as mesmas habilidades avaliem essa pessoa.

Caso seja o relato de um bug, solicitação de melhoria, usamos a label `enhancement` ou `bug`.

Quando forem dúvidas, temos a label `question`.

Caso a pessoa que abriu a issue seja meio doida, podemos usar a issue `this people are crazy`. :joy:

**Tempo de vida das issues**

As issues solicitando Mentoria devem ficar abertas até conseguirmos alguém para auxiliar quem as abriu e ambos atualizarem seus perfis no Mentoria (Mentor atualizar seu perfil e Pupilo criar o seu perfil).

As issues de candidatos(as) a Mentores(as) devem ficar abertas até o perfil ser aprovado e a pessoa enviar seu PR. Fechamos a issue adicionando um [comentário de fechamento de issue](https://help.github.com/articles/closing-issues-via-commit-messages/) relacionando a mesma.

Caso ambos não atualizem seus perfis a issue permanece aberta por até 10 dias e então é fechada.

**O que acontece se eu não criar/atualizar meu perfil?**

Além de ficarmos desapontados e tristes... :disappointed:

Se o Mentor já estiver atendendo o pupilo, seu perfil ficará desatualizado gerando problemas de comunicação entre Administradores e Pupilos/Mentores.

Já o Pupilo não receberá convite para participar do time [`pupils`](https://github.com/orgs/training-center/people) dessa organização o que fará com que o mesmo não receba notícias quando abrirmos uma issue invocando esse time, ex: https://github.com/training-center/mentoria/issues/150.

*Por esses motivos ambos devem cuidar para que seus perfis estejam atualizados.*

**Comentários nas issues**

Assim que uma pessoa abre uma issue deve ser recepcionada com um comentário parecido com:

**Para novos Pupilos >>**

```
Bem vindo(a) `usuário do github que abriu a issue`

Vamos ver se algum dos @training-center/mentors consegue te ajudar.

Enquanto isso leia o documento de [responsabilidades do pupilo](https://github.com/training-center/mentoria/blob/master/pupilos/responsibility.md)!! :smile:
```

OBS: A mention para o time mentors é para que todos sejam alertados do novo pupilo.

Assim que tudo estiver encaminhado, o(a) mentor(a) deve informar para o pupilo a necessidade de criar seu perfil no repositório da organização. Senão acontecer, devemos cobrar a cada 5 dias, passando > 10 dias a issue deve ser fechada, mesmo que o usuário não tenha criado o perfil.

Mensagem para quando estiver tudo correndo entre mentor(a) e pupilo:

```
Olá pessoal!

Não esqueçam de atualizar ou criar seus perfis no [repositório](https://github.com/training-center/mentoria/blob/master/helpers/README.md) e entrar no nosso [Slack](https://ctgroups.herokuapp.com/).
```

**Para novos Mentores >>**

```
Olá `usuário do github que abriu a issue`

Você já leu as [responsabilidades do mentor]((/mentores/responsibility.md)) e está de acordo com a ideia do projeto?
```

Caso o usuário informe que já leu:

```
OK!

Os @training-center/mentors irão avaliar seu perfil e logo te daremos uma resposta.

Obrigado pelo seu interesse em colaborar com a carreira de outras pessoas de maneira gratuita e sem pretenções.
```

As mensagens podem ser, ainda, personalizadas de acordo com que o moderador achar conveniente.

Após a aprovação pelos mentores:


```
Olá `usuário do github que abriu a issue`

Seu perfil foi aprovado pelos outros mentores.

Bem vindo ao time!

Agora você precisa criar seu perfi no [repositório](/helpers/README.md) e entrar no nosso [Slack](https://ctgroups.herokuapp.com/).

Depois é só pegar algum pupilo através dessas [issues](https://github.com/training-center/mentoria/issues?q=is%3Aissue+is%3Aopen+sort%3Acreated-asc+label%3A%22need+a+mentor%22).

OBS: busque das issues mais antigas primeiro. :)
```
