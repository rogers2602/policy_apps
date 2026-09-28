# Termos de Uso e Política de Privacidade — Marques DSP

> **Última atualização:** 28 de setembro de 2026  
> **Versão dos Termos:** 1.2  
> **Aplicativo:** Marques DSP: Áudio & Equalizer (`com.devmarques.dsp`)  
> **Desenvolvedor:** Rogers Marques (Dev Marques)  
> **Contato para Privacidade / Suporte:** dev.marquess@gmail.com  

---

## 📋 Sumário
1. [Apresentação e Visão Geral](#1-apresentação-e-visão-geral)
2. [Conformidade com a LGPD e GDPR](#2-conformidade-com-a-lgpd-e-gdpr)
3. [Dados Coletados e Finalidades do Tratamento](#3-dados-coletados-e-finalidades-do-tratamento)
4. [Processamento de Áudio e Permissões Locais (Privacidade Absoluta)](#4-processamento-de-áudio-e-permissões-locais-privacidade-absoluta)
5. [Monetização, Licenças PRO e Faturamento](#5-monetização-licenças-pro-e-faturamento)
6. [Integrações de Terceiros e Subprocessadores](#6-integrações-de-terceiros-e-subprocessadores)
7. [Segurança da Informação e Armazenamento dos Dados](#7-segurança-da-informação-e-armazenamento-dos-dados)
8. [Direitos do Titular dos Dados (LGPD Art. 18)](#8-direitos-do-titular-dos-dados-lgpd-art-18)
9. [Retenção e Exclusão Definitiva de Dados](#9-retenção-e-exclusão-definitiva-de-dados)
10. [Termos de Uso e Licenciamento do Aplicativo](#10-termos-de-uso-e-licenciamento-do-aplicativo)
11. [Uso Seguro, Headroom e Isenção de Danos a Equipamentos](#11-uso-seguro-headroom-e-isenção-de-danos-a-equipamentos)
12. [Diretrizes da Comunidade Online de Presets](#12-diretrizes-da-comunidade-online-de-presets)
13. [Alterações nesta Política e Foro de Eleição](#13-alterações-nesta-política-e-foro-de-eleição)

---

## 1. Apresentação e Visão Geral

Bem-vindo ao **Marques DSP: Áudio & Equalizer** ("Aplicativo", "Software", "nós", "nosso"). Este documento estabelece os **Termos de Uso** e a **Política de Privacidade** aplicáveis ao download, instalação, compra e utilização do aplicativo em dispositivos Android.

Ao instalar, criar uma conta ou utilizar qualquer funcionalidade do aplicativo, você declara ter lido, compreendido e concordado integralmente com estes Termos. Caso não concorde com qualquer cláusula aqui descrita, você não deve utilizar o aplicativo.

---

## 2. Conformidade com a LGPD e GDPR

Esta Política foi elaborada em estrita conformidade com a **Lei Geral de Proteção de Dados Pessoais do Brasil (LGPD — Lei nº 13.709/2018)**, com o **Marco Civil da Internet (Lei nº 12.965/2014)** e, quando aplicável a usuários no exterior, com o **Regulamento Geral sobre a Proteção de Dados da União Europeia (GDPR — Regulation (EU) 2016/679)**.

### Papéis na Proteção de Dados
- **Controlador dos Dados:** Rogers Marques (Dev Marques), desenvolvedor responsável pelo projeto.
- **Encarregado de Proteção de Dados (DPO) / Suporte:** dev.marquess@gmail.com.

### Princípios Observados
Tratamos os seus dados pessoais com base nos princípios de boa-fé, finalidade, adequação, necessidade, livre acesso, qualidade dos dados, transparência, segurança, prevenção, não discriminação e responsabilização.

---

## 3. Dados Coletados e Finalidades do Tratamento

Coletamos apenas o volume estritamente necessário de dados para viabilizar as funcionalidades do aplicativo, autenticação, suporte e integridade das licenças.

| Categoria do Dado | Dados Específicos | Finalidade Principal | Base Legal (LGPD) |
| :--- | :--- | :--- | :--- |
| **Identificação e Cadastro** | E-mail, Nome de Exibição, Foto de Perfil (se autenticado com Google) e identificador único de usuário (`UID`). | Autenticação no Firebase Auth, sincronização de perfis personalizados na nuvem e identificação da autoria de presets na comunidade. | Execução de Contrato (Art. 7º, V) |
| **Licenças e Compras** | Identificador de transação do Google Play (`orderId`), `purchaseToken`, `productId`, data/hora da compra e estado de validação da licença. | Validação server-side de compras legítimas, liberação de recursos PRO Vitalício e suporte a estornos/reembolsos. | Execução de Contrato e Cumprimento de Obrigação Legal (Art. 7º, II e V) |
| **Concessões de Anúncios** | Contagem de anúncios assistidos (`adsWatchedCount`) e prazo de expiração da concessão (`expiresAt`). | Concessão temporária de 7 dias de acesso PRO via recompensas de anúncios (Google AdMob). | Execução de Contrato (Art. 7º, V) |
| **Perfis e Predefinições Acústicas** | Nomes de perfis criados, curvas de equalização (10 bandas), ganhos, filtros DDC e predefinições salvas. | Armazenamento local e backup privado na nuvem (Firestore) do usuário, além de compartilhamento opcional na comunidade. | Consentimento e Execução de Contrato (Art. 7º, I e V) |
| **Diagnóstico de Falhas e Telemetria (Crashlytics)** | Relatórios anônimos de travamentos (stack trace), modelo e fabricante do aparelho, versão do Android, arquitetura do processador e memória disponível. | Identificação de problemas técnicos, estabilidade da engine DSP e correção ágil de bugs. | Legítimo Interesse (Art. 7º, IX) |
| **Publicidade (Google AdMob)** | Identificador de publicidade do Google (GAID), endereço IP truncado e métricas de exibição de anúncios. | Monetização de usuários gratuitos e liberação de recompensas de 7 dias de PRO. Operado exclusivamente pelo Google. | Legítimo Interesse e Consentimento (Art. 7º, I e IX) |

> [!NOTE]
> **Dados Financeiros e de Pagamento:** Nós **NÃO** coletamos, não processamos e nunca temos acesso aos dados do seu cartão de crédito, conta bancária ou dados de faturamento. Todas as compras são geridas exclusivamente pela infraestrutura segura do **Google Play Billing**.

---

## 4. Processamento de Áudio e Permissões Locais (Privacidade Absoluta)

> [!IMPORTANT]
> **O MARQUES DSP NÃO GRAVA, NÃO ESCUTA E NÃO TRANSMITE ÁUDIO.**

1. **Privacidade Total de Mídia:** O aplicativo **NÃO** acessa o microfone do aparelho para fins de espionagem, gravação ou análise externa. Todo o processamento de equalização e DSP é estritamente matemático, executado pelo próprio subsistema de mídia e chip de áudio do sistema operacional Android.
2. **Integração Shizuku (Sem Root):** Quando o usuário conecta o aplicativo ao serviço **Shizuku**, essa comunicação ocorre exclusivamente via chamadas locais de IPC (Inter-Process Communication / Binder) com o Android. O Shizuku é utilizado exclusivamente para descobrir identificadores de sessão de áudio ativas (`AudioSessionId`) e permitir que o motor de áudio atue em tocadores de mídia que não abrem sessão global de equalização. Nenhuma informação pessoal ou arquivo de áudio é extraído ou enviado para a internet através do Shizuku.
3. **Arquivos Importados (.vdc / .irs):** Arquivos de compensação acústica e impulsos de convolução importados da memória do seu telefone permanecem estritamente no armazenamento privado do aplicativo no aparelho.

---

## 5. Monetização, Licenças PRO e Faturamento

O aplicativo adota o modelo **Freemium**, disponibilizando funcionalidades básicas gratuitas e recursos avançados ("PRO"):

### Modalidades de Acesso PRO
1. **Licença Vitalícia (Lifetime PRO):**
   - Adquirida por pagamento único diretamente no aplicativo através da **Google Play Store**.
   - Concede acesso permanente e perpétuo a todos os recursos avançados de estúdio, backup em nuvem ilimitado, além do exclusivo **Tema Dourado VIP** e do **Ícone Gold VIP**.
   - Não possui cobranças recorrentes nem assinaturas automáticas.
   - Vinculada à conta Google e ao login de usuário registrado.
2. **Acesso PRO Temporário por Recompensa (AdMob Rewarded):**
   - Obtido mediante a conclusão da visualização de 3 (três) anúncios premiados.
   - Concede 7 (sete) dias de acesso integral aos recursos técnicos de áudio DSP (Equalizador Multimodal, Speaker Optimization, Calibração DDC Manual, Presets da Comunidade e Backup em Nuvem).
   - O **Tema Dourado VIP** e o **Ícone Gold VIP** são cosméticos estritamente restritos à compra vitalícia e não são concedidos na modalidade de anúncios.
   - A concessão pode ser renovada assistindo a novos anúncios antes ou após o término dos 7 dias.

### Validação Server-Side e Proteção Antifraude
- Toda transação da Google Play é revalidada no servidor através de Cloud Functions que consultam a **Google Play Developer API v3**.
- **Detecção de Reembolsos e Estornos:** Se um usuário solicitar reembolso pela Google Play ou se a compra for cancelada pelo comerciante, a licença é automaticamente revogada no servidor e no aplicativo.
- **Proteção contra Adulteração Local (Anti-Root):** Dispositivos com permissões de ROOT que manipularem o armazenamento local (`SharedPreferences`) não têm acesso liberado à biblioteca pública do Firestore (`public_profiles`), pois a autorização de leitura e download é checada diretamente pelas regras de segurança de nuvem (`firestore.rules`).

---

## 6. Integrações de Terceiros e Subprocessadores

Para fornecer nossos serviços com máxima confiabilidade, utilizamos provedores de tecnologia e infraestrutura líderes do mercado:

1. **Google LLC (Google Play Services & Google Play Billing):**
   - Finalidade: Distribuição de compilações oficiais, licenciamento e processamento seguro de pagamentos.
   - [Política de Privacidade do Google](https://policies.google.com/privacy)
2. **Google Firebase (Firebase Auth, Cloud Firestore, Cloud Functions, Crashlytics):**
   - Finalidade: Armazenamento em nuvem, execução segura de scripts de validação de licença, login de usuários e relatórios de estabilidade de software.
   - [Privacidade e Segurança no Firebase](https://firebase.google.com/support/privacy)
3. **Google AdMob:**
   - Finalidade: Exibição de anúncios de recompensa para concessão de licenças temporárias gratuitas.
   - [Políticas do Google AdMob](https://policies.google.com/technologies/ads)
4. **Shizuku API (Open Source):**
   - Finalidade: Ponte de privilégios em nível de sistema Android para controle do equalizador global. Comunicação puramente local (off-line).

---

## 7. Segurança da Informação e Armazenamento dos Dados

Empregamos medidas técnicas e administrativas robustas para proteger seus dados contra acessos não autorizados, destruição, perda, alteração ou vazamento:

- **Criptografia em Repouso no Dispositivo:** Utilização da biblioteca `androidx.security:security-crypto` (`EncryptedSharedPreferences`), que criptografa os registros locais de licença com o algoritmo **AES-256-GCM** utilizando chaves do **Android KeyStore**.
- **Assinatura Digital SHA-256 Anti-Tamper:** Os dados cacheados possuem verificação de integridade criptográfica com sal secreto. Caso o arquivo de preferências seja adulterado externamente por ferramentas de modificação em ambientes ROOT, o aplicativo invalida o cache automaticamente.
- **Criptografia em Trânsito:** Todas as trocas de informações com os servidores do Firebase e do Google são realizadas exclusivamente via canais seguros protegidos por criptografia **HTTPS / TLS 1.3**.
- **Regras de Isolamento no Banco de Dados:** Nossas regras de segurança no Firestore garantem que apenas o próprio usuário proprietário da conta consiga ler e gravar seus perfis privados de áudio.

---

## 8. Direitos do Titular dos Dados (LGPD Art. 18)

Em conformidade com a LGPD e o GDPR, você possui os seguintes direitos em relação aos seus dados pessoais:

1. **Confirmação e Acesso:** Saber se tratamos seus dados e solicitar uma cópia das informações arquivadas.
2. **Correção:** Solicitar a retificação de dados incorretos, incompletos ou desatualizados.
3. **Anonimização, Bloqueio ou Eliminação:** Requerer a exclusão de dados excessivos ou tratados em desconformidade com a legislação.
4. **Portabilidade:** Solicitar a exportação dos seus dados de perfis em formato interoperável.
5. **Eliminação dos Dados:** Solicitar a exclusão definitiva da sua conta e de todos os seus perfis e predefinições salvas na nuvem.
6. **Revogação do Consentimento:** Revogar a autorização dada a qualquer momento de forma simples e acessível.

### Como Exercer seus Direitos
Para exercer qualquer um dos seus direitos, você pode:
- Gerenciar ou excluir seus perfis diretamente na aba de **Gerenciador de Perfis** do aplicativo;
- Efetuar logout ou excluir sua conta nas configurações do app;
- Enviar uma solicitação formal ao nosso Encarregado pelo e-mail: **dev.marquess@gmail.com**. As solicitações serão atendidas gratuitamente no prazo legal.

---

## 9. Retenção e Exclusão Definitiva de Dados

- Os dados vinculados à sua conta (perfis em nuvem e licença) são mantidos enquanto sua conta permanecer ativa.
- Caso o usuário solicite a exclusão de sua conta, todos os perfis privados no Firestore associados ao seu `UID` são imediatamente e permanentemente excluídos.
- Registros de transações fiscais ou confirmações de compra da Google Play poderão ser retidos exclusivamente pelo período estritamente exigido pela legislação tributária e comercial.
- Perfis compartilhados voluntariamente pelo usuário na Comunidade Pública (`public_profiles`) poderão ser excluídos pelo próprio autor a qualquer momento antes da desativação de sua conta através do botão de exclusão pública disponível no aplicativo.

---

## 10. Termos de Uso e Licenciamento do Aplicativo

### Concessão de Licença
O Desenvolvedor concede a você uma licença pessoal, revogável, não-exclusiva, intransferível e livre de royalties para baixar, instalar e utilizar o software Marques DSP em seus dispositivos compatíveis, estritamente de acordo com estes termos.

### Restrições de Uso
Você concorda expressamente em **NÃO**:
- Descompilar, realizar engenharia reversa, desmontar ou tentar derivar o código-fonte do aplicativo, exceto na extensão permitida por leis aplicáveis ou licenças de código aberto de componentes inclusos;
- Burlar, desativar ou tentar fraudar os mecanismos de segurança, checksums ou validações de licença do Google Play Billing e do Cloud Firestore;
- Utilizar o aplicativo para qualquer fim ilegal, difamatório ou fraudulento;
- Publicar predefinições na Comunidade que contenham títulos ofensivos, ilegais, difamatórios ou que violem marcas registradas de terceiros.

---

## 11. Uso Seguro, Headroom e Isenção de Danos a Equipamentos

> [!WARNING]
> **ATENÇÃO AUDIÓFILA E PREVENÇÃO DE DANOS:**
> O Marques DSP é uma suíte profissional de manipulação de áudio com capacidades avançadas de amplificação sonora, equalização cirúrgica e reforço de graves (*Clear Bass*, *Speaker Extra Volume*, *Manual DDC*).

1. **Volume Seguro:** A exposição contínua a níveis sonoros acima de 85 decibéis (dB) pode causar lesões auditivas irreversíveis e perda permanente de audição. Recomendamos sempre seguir os avisos de volume seguro do sistema operacional e da Organização Mundial da Saúde (OMS).
2. **Saturação Digital (Clipping):** Ao aplicar reforços substanciais em bandas de equalização (+6 dB a +12 dB), utilize sempre o controle deslizante de **Pre-Amp Gain (Headroom)** com valores negativos proporcionais para prevenir a distorção harmônica por corte digital (clipping).
3. **Isenção de Responsabilidade sobre Hardware:** Na máxima extensão permitida pela lei aplicável, o Desenvolvedor não se responsabiliza por eventuais danos materiais causados a fones de ouvido, drivers de alto-falantes, subwoofers ou componentes de amplificação física decorrentes do uso inadequado, distorção extrema ou operação em volumes excessivos promovidos pelo usuário.

---

## 12. Diretrizes da Comunidade Online de Presets

Ao compartilhar predefinições acústicas na biblioteca da comunidade online:
- Você concede uma licença perpétua e irrevogável para que os demais usuários do aplicativo possam visualizar, baixar e reproduzir as curvas de áudio compartilhadas;
- Você garante que o perfil acústico não contém códigos maliciosos nem textos depreciativos;
- O Desenvolvedor reserva-se o direito de moderar, ocultar ou remover sem aviso prévio qualquer preset da comunidade que viole direitos de terceiros ou estas diretrizes.

---

## 13. Alterações nesta Política e Foro de Eleição

### Atualizações Contratuais
Podemos atualizar estes Termos e a Política de Privacidade periodicamente para refletir melhorias no produto, mudanças regulatórias ou lançamentos de novas funcionalidades. Quando forem feitas alterações relevantes, a data no cabeçalho será atualizada e o aplicativo poderá exibir um comunicado em tela. O uso contínuo do aplicativo após a publicação das alterações constitui aceitação dos novos termos.

### Foro de Eleição
Estes Termos são regidos e interpretados exclusivamente de acordo com as **Leis da República Federativa do Brasil**. Fica eleito o Foro da Comarca de domicílio do Usuário (em conformidade com o Código de Defesa do Consumidor — Lei nº 8.078/1990) ou, subsidiariamente, o Foro da Comarca de domicílio do Desenvolvedor para dirimir qualquer controvérsia oriunda deste instrumento.

---

### Dúvidas ou Solicitações?
Se você tiver qualquer dúvida sobre esta Política de Privacidade, práticas do aplicativo ou quiser exercer seus direitos como titular de dados da LGPD/GDPR:

- 📧 **E-mail de Contato:** dev.marquess@gmail.com
- 💻 **Repositório Oficial do Projeto:** [github.com/rogers2602/equilizer](https://github.com/rogers2602/equilizer)
