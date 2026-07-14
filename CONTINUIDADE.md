# Continuidade do Portfólio Profissional

## Fonte oficial

- Repositório: `cristianohsm/portfolio`
- Branch: `main`
- Visibilidade: pública
- Projeto Vercel: `cristiano-portfolio`
- URL de produção: `https://cristiano-portfolio-five.vercel.app/`

O GitHub público é a fonte oficial do código deste portfólio.

Toda mudança validada deve ser enviada ao repositório e não pode existir somente no deploy.

## Procedimento de atualização

1. Trabalhar em uma cópia local do repositório.
2. Alterar somente arquivos públicos e sanitizados.
3. Abrir o site localmente e revisar desktop e celular.
4. Executar as verificações de HTML, links, UTF-8, segurança e `git diff --check`.
5. Criar um commit descritivo e fazer push normal para `main`.
6. Publicar o mesmo commit no projeto Vercel `cristiano-portfolio`.
7. Confirmar HTTP 200 e comparar o deploy com o commit remoto.

Nunca usar `force push` e nunca manter uma correção somente no deploy.

## Currículo profissional

- Status: ativo;
- caminho público: `assets/docs/curriculo-cristiano-silva.pdf`;
- botão de visualização e download: habilitado na seção de contato.

Para atualizar o currículo, substitua o PDF no mesmo caminho, sem alterar o nome do arquivo e sem publicar fontes editáveis como DOCX. Valide o documento e o link localmente, crie um commit, faça push para `origin/main` e gere um novo deploy no projeto Vercel existente. Confirme HTTP 200 para o site e para o PDF.

Em caso de problema, reverta a mudança por meio de um novo commit baseado no commit anterior estável, faça push normal e publique novamente. Não reescreva o histórico.

## Testes mínimos

- HTML sem erros estruturais relevantes;
- layout sem overflow horizontal em 360 px, tablet e desktop;
- navegação por teclado e foco visível;
- contraste e texto alternativo da foto;
- links externos e âncoras internas;
- ausência de erros no console;
- UTF-8 estrito e `git diff --check`;
- varredura de segredos, IPs, telefones e caminhos de produção;
- HTTP 200 em produção.

## Rollback

1. Identificar no GitHub o último commit estável.
2. Criar um novo commit que reverta a alteração problemática, preservando o histórico.
3. Fazer push normal para `main`.
4. promover ou gerar um novo deploy do commit revertido na Vercel.
5. Confirmar novamente o HTTP e os testes mínimos.

Não reescrever o histórico e não usar `force push`.

## Pendências

- Confirmar a situação da formação em Administração;
- conectar domínio próprio;
- criar projetos demonstrativos públicos.
