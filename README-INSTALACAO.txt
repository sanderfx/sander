EJIGBO FOTOGRAFIA — VERSÃO GITHUB PAGES (SEM PHP)

1. Abra o seu repositório no GitHub.
2. REMOVA os arquivos PHP antigos: index.php, admin.php, functions.php, config.php.
   Remova também arquivos antigos que contenham senhas, credenciais ou dados privados.
   ATENÇÃO: arquivos secretos que já foram enviados ao histórico do GitHub podem continuar acessíveis.
   Se você publicou senhas, altere-as imediatamente e considere criar um repositório novo e limpo.
3. Envie TODOS os arquivos e pastas deste ZIP para a RAIZ do repositório (a mesma pasta de index.html).
4. Em Settings > Pages, selecione Deploy from a branch / main / (root) e Save.
5. Site: https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
6. Painel: https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/admin.html
7. Em github.com/settings/personal-access-tokens/new, crie token Fine-grained:
   - Repository access: Only select repositories > escolha APENAS o repositório do site
   - Repository permissions: Contents: Read and write
   - Configure uma expiração curta e renove quando necessário
8. No painel, informe seu usuário, repositório, branch main e token. O token não é
   gravado em localStorage, cookies, código ou arquivos. Ao atualizar a aba, conecte novamente.
9. Edite textos e fotos. Clique Publicar alterações. A publicação pode demorar alguns minutos.

OBSERVAÇÕES IMPORTANTES
- O painel admin.html é PÚBLICO como página, mas só quem tiver um token com permissão de escrita pode modificar o site.
- Nunca coloque seu token ou senhas no repositório ou em prints.
- As fotografias ficam públicas no repositório. O GitHub não é armazenamento privado.
- Remover uma foto do site não apaga seu arquivo antigo/histórico do GitHub.
- Evite publicar selfies/documentos de identidade de clientes ou dados pessoais sem autorização.
- GitHub Pages não executa PHP, e esta versão foi feita em HTML/CSS/JS + GitHub API.
- Para endereço personalizado, é necessário configurar DNS/CNAME no GitHub.
- O painel precisa de internet e requer permissões do navegador para acessar a API do GitHub.
