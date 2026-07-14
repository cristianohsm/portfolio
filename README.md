# Cristiano Silva — Portfólio Profissional

Site estático público para apresentar a trajetória, as áreas de atuação e estudos de caso anonimizados de Cristiano Silva.

## Objetivo

Reunir, de forma profissional e acessível, experiências em operações automotivas, produção, supervisão, automação de processos, dados e inteligência artificial aplicada.

O GitHub público é a fonte oficial do código deste portfólio. Toda mudança validada deve ser enviada ao repositório e não pode existir somente no deploy.

## Estrutura

- `index.html`: conteúdo, semântica e metadados do site;
- `styles.css`: identidade visual e responsividade;
- `assets/`: foto profissional, favicon e documentos públicos;
- `robots.txt` e `sitemap.xml`: indexação;
- `CONTINUIDADE.md`: operação, atualização, testes e rollback.

## Execução local

Não há dependências ou etapa de compilação. Abra `index.html` diretamente no navegador ou sirva a pasta com qualquer servidor HTTP estático.

Exemplo com Node.js:

```bash
npx serve .
```

## Edição dos textos

Os textos ficam em `index.html`. Preserve a estrutura semântica, os textos alternativos, a navegação por teclado e as informações de SEO ao editar.

## Foto

O site usa `assets/cristiano-silva.png`. A imagem publicada é uma cópia otimizada para web; o arquivo original deve permanecer preservado fora do repositório.

Ao substituir a foto, mantenha o nome do arquivo, o enquadramento quadrado e o texto alternativo existente. Nunca utilize imagens de terceiros sem origem e autorização confirmadas.

## Currículo

O currículo publicado fica em `assets/docs/curriculo-cristiano-silva.pdf`.

Para atualizá-lo, substitua o PDF nesse mesmo local e mantenha obrigatoriamente o nome `curriculo-cristiano-silva.pdf`, preservando o caminho usado pelo site. Valide o arquivo antes de criar o commit e confirme o link após o deploy. Arquivos editáveis, como DOCX, não devem ser publicados no repositório.

## Deploy

O deploy de produção utiliza um projeto Vercel separado. Consulte `CONTINUIDADE.md` para o identificador e o procedimento atualizado.

## Segurança

- Não incluir `.env`, tokens, chaves ou credenciais;
- não publicar bancos, logs, backups ou dados operacionais;
- não copiar código de repositórios privados;
- não expor informações empresariais, pessoais ou de clientes;
- não publicar nomes internos, placas, valores ou métricas sem comprovação.
