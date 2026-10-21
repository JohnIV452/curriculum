# Curriculum — João Gabriel de Castro

Projeto de currículo em HTML5 criado para a atividade prática de Git e GitHub.

## Arquivos

- `index.html`: currículo responsivo, com estilos CSS incorporados.
- `publicar-github.bat`: publica cada etapa da linha principal com um push separado e, depois, envia as branches de desenvolvimento.
- Histórico Git: um branch de funcionalidade por seção, commits individuais e merges para `main`.

## Seções implementadas

1. Cabeçalho e contato
2. Resumo profissional
3. Experiência profissional
4. Formação acadêmica
5. Habilidades e competências
6. Certificações e cursos complementares
7. Idiomas
8. Atualização da formação: Ensino Médio Completo, concluído em 2020
9. Confirmação do curso de Almoxarifado realizado no SENAI
10. Ajuste do cabeçalho de contato, removendo perfis que não possui e alinhando os dados de contato
11. Detalhamento dos cursos de Excel básico no SENAI (2026), Inglês básico na Prime Cursos (2021) e conclusão do Tiro de Guerra (2022)
12. Padronização visual dos cursos, exibindo “Inglês básico — Prime Cursos” na mesma linha do título, como nos cursos do SENAI.

## Antes de entregar

- Confira se as descrições gerais de atividades profissionais correspondem às tarefas que você realmente realizava.
- A formação “Ensino Médio Completo” foi incluída com conclusão em 2020; a instituição não foi informada.
- O curso de Almoxarifado foi realizado no SENAI e está registrado com conclusão em 2026, conforme confirmado.
- O curso de Excel básico foi realizado no SENAI e concluído em 2026.
- O curso de Inglês básico foi realizado na Prime Cursos e concluído em 2021; a instituição aparece ao lado do nome do curso, seguindo o mesmo padrão visual do SENAI. A seção Idiomas também indica Inglês básico.
- O Tiro de Guerra, no Exército Brasileiro, está registrado com conclusão em 2022.
- Os links de LinkedIn e GitHub foram removidos do cabeçalho porque você informou que não possui esses perfis.
- O currículo exibe apenas “Araras, São Paulo, Brasil”; o endereço residencial completo foi omitido para preservar sua privacidade.

## Publicar no GitHub conforme o fluxo solicitado

1. No GitHub, crie um repositório **público** chamado `curriculum`. Deixe o repositório remoto vazio: não marque as opções para adicionar README, licença ou `.gitignore`.
2. Extraia `curriculum_projeto.zip` e entre na pasta `curriculum`. **Não apague a pasta oculta `.git`**, pois ela contém os commits e branches já preparados.
3. Abra o Prompt de Comando ou terminal integrado do VS Code nessa pasta e conecte o remoto, substituindo `SEU-USUARIO` pelo seu usuário do GitHub:

```bash
git remote add origin https://github.com/SEU-USUARIO/curriculum.git
```

4. No Windows, execute o script abaixo no Prompt de Comando:

```bat
publicar-github.bat
```

O script envia primeiro o commit inicial, depois cada merge da `main` em sequência, e por último publica todas as branches de desenvolvimento. Assim, cada avanço de `main` é enviado separadamente, como pede a atividade. O push exige autenticação válida no GitHub.

Se preferir não usar o script, a publicação final simples é `git push -u origin main` e depois `git push origin --all`; porém, ela não envia cada avanço da `main` em pushes separados.
