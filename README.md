# Loja ERP — canal de atualizações

Este repositório publica as versões do **Loja ERP** que os computadores das lojas baixam sozinhos.

- `versao.json` — versão atual, notas e SHA-256 do pacote, **assinado com Ed25519** pelo autor.
- `pacotes/LojaERP-x.y.z.zip` — arquivos do programa (código e interface). Nenhum dado de loja.

O programa só instala um pacote se a assinatura conferir com a chave pública embutida nele, se o SHA-256 bater e se a versão nova passar num teste antes da troca; a versão anterior fica guardada e volta sozinha se a nova não abrir.

O código-fonte e o histórico ficam no repositório privado do projeto. Uso, cópia e distribuição seguem a licença do Loja ERP (software proprietário).

Copyright © 2026 Victor Hugo Rebollo de Moura — Infinity Technology · victorhugormoura@gmail.com
