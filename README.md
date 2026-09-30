# ADA.IA | Apresentação web interativa V2

Microsite responsivo de apresentação comercial, reconstruído a partir da apresentação ADA.IA e da identidade visual fornecidas pelo projeto. O site não é uma transposição de slides em imagem.

## Como visualizar

Abra `index.html` no navegador. Para testar com um servidor local (recomendado):

```bash
cd ADAIA_Apresentacao_Web_V2
python3 -m http.server 8080
```

Acesse `http://localhost:8080`.

Não exige npm, compilação, login, API nem instalação de bibliotecas. A fonte Figtree é solicitada ao Google Fonts quando há conexão; o sistema utiliza fontes substitutas quando não há.

## Interações

- Modo Explorar: página responsiva com capítulos e rolagem.
- Modo Apresentar: clique em `Apresentar` e navegue com botões ou setas esquerda/direita. `Esc` sai do modo. `?modo=apresentar&cap=4` abre o quarto capítulo.
- Gargalos: selecione cada um para ver impacto e abordagem.
- Método A.D.A.: selecione Analisar, Desenhar ou Acelerar.
- Fluxo: alterne Empresa e Prefeitura; explore as cinco etapas. Todos os textos são exemplos ilustrativos.
- Diagnóstico: o formulário gera um briefing local copiável. Nenhuma informação é enviada a servidor nesta versão.

## Para publicar

1. Confirmar e configurar o canal comercial real em `config.js` e integrar o formulário se quiser receber solicitações automaticamente. A versão atual somente prepara e copia o briefing, com aviso visível para o visitante.
2. Substituir o bloco de monograma RT por foto real aprovada do fundador, se desejar.
3. Inserir cases, portfólio e números somente quando houver material verificável e autorização de uso.
4. Validar marca, nomenclatura contratual do ADA Core, segurança, proteção de dados e a adequação de cada funcionalidade antes de anunciá-la como disponível.
5. Configurar domínio, URL canônica, imagem Open Graph real, analytics, consentimento e eventuais integrações de CRM antes da publicação.
6. Executar testes finais no servidor de produção e revisar contraste, acessibilidade e performance nos dispositivos-alvo.

## Identidade

Cores: verde `#4CD091`, grafite `#3A3D44`, azul-claro `#E9EDF3`, branco. A marca PNG deriva do original enviado pelo usuário. A variante clara altera somente a cor escura da palavra para facilitar leitura em fundo escuro.

## Sobre a solução

ADA OS é a fonte interna de orientação estratégica. ADA Core é a experiência de operação e relacionamento da ADA, oferecida sobre infraestrutura licenciada ou integrada. Esta apresentação não afirma propriedade do código-base, integração testada, resultados garantidos, métricas sem fontes, SLA ou conformidade legal não verificada.

## Arquivos principais

`index.html`: conteúdo e estrutura, `styles.css`: direção visual e responsividade, `app.js`: interações, `config.js`: pontos de configuração, `assets/`: marcas utilizadas.
