# Meridian Editor

Editor de vídeo gratuito e de código aberto em desenvolvimento. Este repositório prepara a **build de teste para Windows**, baseada no código-fonte do Meridian Editor v0.14.1.

## Gerar o instalador sem instalar Python

1. Baixe o pacote de código-fonte preparado: `Meridian_Editor_v0.14.1_WINDOWS_BUILD_READY.zip`, disponibilizado nesta conversa do ChatGPT.
2. Na página do repositório, clique em **Add file → Upload files**, selecione o ZIP **sem extrair** e clique em **Commit changes**.
3. Abra a aba **Actions → Build Meridian Windows installer** e acompanhe a execução que será iniciada automaticamente.
4. Quando estiver concluída, abra a execução e baixe o artefato **Meridian-Windows-v0.14.1** em *Artifacts*. Ele deverá conter `MeridianEditor_Setup_v0.14.1.exe` e a versão portátil.

**Importante:** o pacote é compilado no Windows do GitHub Actions. No computador que recebe o instalador não é necessário instalar Python, FFmpeg nem compiladores. Esta é uma **versão de testes** e ainda não foi validada em seu PC.

O código-fonte continuará sendo livre sob GPL-3.0. O FFmpeg e outras dependências de terceiros mantêm suas próprias condições de licença.

## Status

- [x] Repositório disponível
- [x] Workflow para build Windows configurado
- [ ] Upload do pacote de código-fonte v0.14.1
- [ ] Primeira execução da compilação em Windows
- [ ] Teste do instalador e do aplicativo

Não publique esta versão como build estável antes de validar a instalação e os fluxos de edição.
