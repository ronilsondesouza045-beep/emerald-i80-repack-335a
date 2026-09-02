# Emerald i80 Repack — WoW 3.3.5a

> Repack para **testes locais** em World of Warcraft Wrath of the Lich King **3.3.5a (build 12340)**.  
> **O cliente WoW não está incluído.**

[⬇️ **BAIXAR O REPACK EM ZIP**](https://github.com/ronilsondesouza045-beep/emerald-i80-repack-335a/releases/latest)

## Sobre esta versão

Esta versão reúne o estado estável do Emerald i80 após os testes e correções realizados no servidor.

✅ Core limpo/addon compat confirmado pelo SHA-256.

### O que foi corrigido/testado

- Correção aplicada ao falso **kick/desconexão** observado no bloco compartilhado de validação de chat/addon.
- O problema havia sido reproduzido durante sincronização do addon **Transmorpher**.
- Depois da correção, o cenário foi testado com **3 contas simultâneas** sem reproduzir a queda que ocorria anteriormente.
- As configurações atuais do repack foram preservadas.
- O pacote é **server-only**: não inclui cliente WoW e não depende dos patches custom de armas que foram usados apenas em testes anteriores.

> A afirmação acima se refere aos testes feitos neste repack. Não significa que qualquer addon existente seja garantidamente compatível.

## Requisitos

- Windows.
- Cliente **WoW WotLK 3.3.5a / build 12340** obtido separadamente.
- Espaço livre para extrair o servidor.

## Como instalar

1. Vá em **Releases** ou clique em **BAIXAR O REPACK EM ZIP** acima.
2. Baixe $ZipName.
3. Extraia a pasta REPACK_EMERALD_I80.
4. Execute 1_ABRIR_SERVIDOR_COMPLETO.bat.
5. Aguarde MySQL, AuthServer e WorldServer iniciarem.
6. No cliente WoW, configure:
   ``text
   set realmlist 127.0.0.1
   ``
7. Abra wow.exe.

Dentro do repack também existe CONFIGURAR_WOW_LOCAL.bat, que faz backup do seu ealmlist.wtf e configura o endereço local automaticamente.

## Conta GM

A **conta GM permanece exatamente como estava no banco de dados** no momento da criação do release. O empacotador não troca usuário nem senha.

Por segurança, as credenciais não são publicadas neste README. Se o servidor for usado fora de um ambiente local, altere senhas e revise as permissões GM antes de expor qualquer porta.

## Integridade

SHA-256 do worldserver.exe deste release:

``text
F90B54ECEF2CA6D996E8DD8E262428896D20967280291F6D227370B124CBB5B6
``

O arquivo SHA256.txt anexado ao release contém o hash do ZIP completo.

## Screenshots

Imagens do projeto podem ser colocadas em docs/images/.

<!-- Exemplo:
![Emerald i80](docs/images/servidor.png)
-->

## Uso

Este projeto é disponibilizado para **testes locais, estudo e aprendizado**.

- Não inclui o cliente World of Warcraft.
- Não é afiliado nem endossado pela Blizzard Entertainment.
- Não utilize credenciais padrão ao expor o servidor à Internet.

## Versão

**v1.0.0**





