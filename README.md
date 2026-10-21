# Curriculum — João Gabriel de Castro

Projeto de currículo em HTML5 criado para a atividade prática de Git e GitHub.

## Arquivos

- `index.html`: currículo responsivo, com estilos CSS incorporados.
- Histórico Git: um branch de funcionalidade por seção, commits individuais e merges para `main`.

## Seções implementadas

1. Cabeçalho e contato
2. Resumo profissional
3. Experiência profissional
4. Formação acadêmica
5. Habilidades e competências
6. Certificações e cursos complementares
7. Idiomas

## Antes de entregar

- Confira se as descrições gerais de atividades profissionais correspondem às tarefas que você realmente realizava.
- Acrescente, se desejar, sua formação de ensino médio e o período/instituição, que não foram informados nos dados enviados.
- Troque os links genéricos de LinkedIn e GitHub pelos links dos seus perfis, caso tenha contas. Se não tiver, remova esses dois links.
- O currículo exibe apenas “Araras, São Paulo, Brasil”; o endereço residencial completo foi omitido para preservar sua privacidade.

## Publicar no GitHub

1. Crie no GitHub um repositório **público** chamado `curriculum`. Para usar este repositório local já versionado, não inicialize o repositório remoto com README, licença ou `.gitignore`.
2. Extraia o ZIP mantendo a pasta `curriculum` e seu diretório oculto `.git`.
3. Abra um terminal na pasta `curriculum` e execute, substituindo `SEU-USUARIO` pelo seu nome de usuário do GitHub:

```bash
git remote add origin https://github.com/SEU-USUARIO/curriculum.git
git push -u origin main
```

O histórico local contém o commit inicial e os commits de seção em branches individuais integrados por merge na `main`. Depois do push da `main`, esses commits e merges estarão visíveis no GitHub. Para também publicar os nomes das branches de desenvolvimento:

```bash
git push origin --all
```

Se a professora exigir um push remoto após cada merge, reproduza os merges no GitHub já conectado e execute `git push origin main` depois de cada merge. O histórico entregue já está integrado localmente; não foi possível fazer push nesta etapa porque não temos acesso à sua conta/repositório remoto.
