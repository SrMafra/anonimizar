
---
## 💚 Gostou? Contribua com o projeto

**Teste primeiro.** Use o programa com seus processos, confira os resultados e veja se ele atende ao que você precisa.

Só se você gostou e ele resolveu o seu problema, considere fazer uma contribuição via **PIX**. É totalmente opcional, e qualquer valor ajuda a continuar o desenvolvimento.

**Chave PIX (e-mail):** `antonioaugusto96@gmail.com`


---
# Anonimizador de Processos Jurídicos

Programa gratuito para Windows que **esconde os dados pessoais de processos jurídicos em PDF**: nomes, CPF, RG, endereço, telefone, e-mail, dados bancários e outros. Ajuda a cumprir a LGPD antes de compartilhar um processo ou usá-lo com ferramentas de IA.

**Funciona 100% no seu computador.** Não precisa instalar nada, não usa a internet e nenhum documento sai da sua máquina.

---

## ⬇️ Download

**[Baixar o Anonimizador (Google Drive)](https://drive.google.com/drive/folders/1Ramj3ovLA7xXpHeWVKo-tHHFuioLxc6l?usp=sharing)**

Baixe o arquivo `.zip` da pasta (cerca de 625 MB).

**Requisitos:** Windows 10 ou 11 (64 bits) e cerca de 1,5 GB livres no disco.

---

## Como usar

1. **Descompacte o `.zip`** numa pasta do seu computador, por exemplo em Documentos. Não rode o programa de dentro do `.zip`.
2. **Abra o `Anonimizador.exe`.** A janela mostra "Carregando..." por alguns segundos. Na primeira vez, pode levar até 1 minuto.
3. Se o Windows mostrar o aviso **"O Windows protegeu o computador"**, clique em **"Mais informações"** e depois em **"Executar assim mesmo"**. O aviso aparece porque o programa ainda não tem assinatura digital paga.
4. Clique em **"Escolher PDF(s)..."**, selecione o processo e espere a barra de progresso chegar ao fim.
5. Clique em **"Ver resultado"**. O navegador abre com o **original de um lado** e o **texto anonimizado do outro**, para você conferir.

O resultado é gravado na mesma pasta do PDF, em dois arquivos terminados em `-anonimizado.html` e `-anonimizado.txt`.

### Exemplo

| Original | Anonimizado |
|---|---|
| Maria da Silva, CPF 123.456.789-09, residente na Rua das Flores, 100 | [AUTOR], CPF [CPF], residente na [ENDERECO] |
| Processo distribuído em 14/08/2026 à 2ª Vara Cível | Processo distribuído em 08/2026 à [VARA] Vara Cível |

*(Os dados do exemplo são fictícios.)*

---

## O que ele esconde

- **Pessoas:** nomes das partes, testemunhas, menores, médicos e demais envolvidos. Cada nome vira o papel da pessoa no processo, como `[AUTOR]`, `[RÉU]` e `[TESTEMUNHA 1]`, para o texto continuar compreensível. Nomes de advogados, juízes, servidores e peritos judiciais **ficam visíveis**, porque atuam em função pública ou profissional no processo.
- **Documentos:** CPF, CNPJ, RG, CNH, PIS/PASEP, CTPS, OAB, CRM, título de eleitor.
- **Contato e localização:** endereço, CEP, telefone, e-mail, naturalidade.
- **Dados financeiros:** conta bancária, agência, chave PIX, cartão de crédito.
- **Saúde e outros dados sensíveis:** prontuário, carteirinha de plano de saúde, Cartão SUS, escola de menores.
- **Números do processo:** número CNJ, protocolos, contratos, matrículas, códigos de verificação.
- **Datas:** a data de nascimento é escondida; a data de distribuição fica só com mês e ano.

---

## ⚠️ Importante: versão de teste

- **Sempre confira o resultado antes de usar.** O programa pode deixar passar algum dado. Ele ajuda, mas **não substitui a revisão humana**.
- **Páginas escaneadas (imagem) ainda não são lidas.** O programa avisa quando encontra uma.
- O arquivo `-anonimizado.html` contém **também o texto original**, para comparação. **Não envie esse arquivo para ninguém.** Depois de conferir, apague-o pelo botão "Apagar resultado".

---

## 💬 Feedback

Sua opinião ajuda a melhorar o programa. Conte o que funcionou, o que escapou e que melhorias você gostaria de ver:

- abrindo uma **[Issue](../../issues)** aqui no GitHub; ou
- mandando um e-mail para **antonioaugusto96@gmail.com**.

> **Nunca copie dados reais na mensagem.** Descreva só o **tipo** do dado.
> ✅ Certo: "página 3: um CPF sem pontos ficou visível"
> ❌ Errado: "página 3: o CPF 123.456.789-00 ficou visível"

---

## 💚 Gostou? Contribua com o projeto

**Teste primeiro.** Use o programa com seus processos, confira os resultados e veja se ele atende ao que você precisa.

Só se você gostou e ele resolveu o seu problema, considere fazer uma contribuição via **PIX**. É totalmente opcional, e qualquer valor ajuda a continuar o desenvolvimento.

**Chave PIX (e-mail):** `antonioaugusto96@gmail.com`

---

## Créditos

Este programa usa ferramentas e modelos de código aberto:

- [Microsoft Presidio](https://github.com/microsoft/presidio): detecção de dados pessoais
- [pypdfium2](https://github.com/pypdfium2-team/pypdfium2): leitura de PDF
- Modelo [ner-bert-base-cased-pt-lenerbr](https://huggingface.co/pierreguillou/ner-bert-base-cased-pt-lenerbr), de Pierre Guillou, treinado sobre o [BERTimbau](https://huggingface.co/neuralmind/bert-base-portuguese-cased) (NeuralMind) e o conjunto de dados [LeNER-Br](https://github.com/peluz/lener-br) (Luz de Araujo et al.)

---

*Este programa é fornecido "como está", sem garantias. O uso e a conferência do resultado são de responsabilidade de quem o utiliza.*
