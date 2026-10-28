DOE ESPERANÇA — INSTRUÇÕES

O QUE ESTÁ INCLUÍDO
- index.html: página da campanha
- styles.css: visual responsivo para celular e computador
- script.js: seleção de valor, forma de pagamento, menu e compartilhamento

IMPORTANTE SOBRE PAGAMENTOS
Este projeto NÃO processa pagamentos e não contém chaves PIX, credenciais, integração bancária ou dados fictícios de cobrança. O formulário deixa claro que o pagamento está desativado.
Para receber doações de verdade:
1. Escolha um provedor de pagamentos que opere no Brasil e aceite sua organização/atividade (por exemplo, um provedor com checkout hospedado e suporte a PIX e cartão).
2. Crie a conta diretamente no provedor e conclua a verificação de identidade/organização.
3. Configure o PIX com a chave oficial da campanha e/ou crie um checkout hospedado para cartão.
4. Implemente a integração usando o SDK/API oficial no servidor (backend), incluindo confirmação por webhook. Nunca coloque chaves secretas no JavaScript ou no HTML público.
5. Só informe que uma doação foi concluída depois de confirmação do provedor. Teste em ambiente de sandbox antes de ativar a produção.
6. Atualize a página com dados verdadeiros do responsável pela campanha, contato, política de privacidade e prestação de contas.

FOTOS E HISTÓRIAS
As fotos são carregadas de URLs do Unsplash e exigem internet. Elas são ilustrativas, não são apresentadas como animais reais resgatados pela campanha. Substitua por imagens autorizadas e histórias verificadas antes de publicar. Confirme os termos de uso/licença das imagens selecionadas.

COMO VISUALIZAR LOCALMENTE
1. Extraia o ZIP.
2. Abra index.html no navegador.
Não é necessário instalar dependências.

COMO PUBLICAR (OPÇÃO SIMPLES: GITHUB PAGES)
1. Crie uma conta no GitHub e um repositório público novo.
2. Envie index.html, styles.css, script.js e README.txt para a raiz do repositório.
3. Abra Settings > Pages.
4. Em Build and deployment, selecione Deploy from a branch; escolha a branch principal e a pasta /(root); salve.
5. Aguarde a publicação e abra o endereço mostrado pelo GitHub Pages.
Também é possível publicar os arquivos em serviços de hospedagem estática como Netlify ou Cloudflare Pages.

ANTES DE DIVULGAR
- Cadastre o responsável real pela campanha e um contato.
- Explique como o dinheiro será usado e como os resultados serão prestados contas.
- Revise privacidade e requisitos legais aplicáveis.
- Conecte um provedor de pagamento real antes de anunciar que PIX/cartão estão disponíveis.
