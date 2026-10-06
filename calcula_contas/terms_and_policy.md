# Política de Privacidade - CalculaContas

**Última atualização:** 21 de julho de 2026

Esta Política de Privacidade descreve como o aplicativo **CalculaContas** coleta, usa, armazena e compartilha suas informações ao utilizar nossos serviços, em conformidade com as diretrizes da Google Play Store, Apple App Store e a Lei Geral de Proteção de Dados (LGPD).

---

## 1. Coleta de Informações e Dados

O CalculaContas coleta apenas as informações estritamente necessárias para o funcionamento dos recursos de controle financeiro, sincronização em nuvem e comunicação:

### A. Dados de Autenticação (Informações Pessoais)
Ao utilizar a sincronização em nuvem, o usuário realiza o login utilizando sua conta Google (via Google Sign-In e Firebase Auth). Coletamos:
* **Nome completo**
* **Endereço de e-mail**
* **Foto de perfil** (opcional, para exibição na interface do usuário)

### B. Dados de Lançamentos Financeiros
Para cumprir a função principal de controle e planejamento de contas, o aplicativo processa e armazena:
* **Nome/descrição dos lançamentos** (ex: "Aluguel", "Energia")
* **Valor das contas**
* **Data de vencimento/pagamento**
* **Status de pagamento** (Pago ou Pendente)
* **Categorias personalizadas de contas**

### C. Assinaturas e Compras no Aplicativo (Premium)
Oferecemos recursos Premium através de assinaturas processadas pelas lojas de aplicativos oficiais (Google Play Store e Apple App Store). 
* **O CalculaContas não coleta, processa ou armazena dados de cartão de crédito ou informações financeiras de pagamento.** 
* Apenas recebemos um "token" ou recibo de validação anônimo das lojas para liberar as funcionalidades Premium em sua conta.

### D. Notificações e Identificadores de Dispositivo
Para o envio de alertas de vencimento e comunicações:
* **Tokens de Notificação (Push Tokens)**: Coletamos tokens de dispositivo gerados pelo Firebase Cloud Messaging (FCM) para enviar lembretes.
* **Informações Básicas de Dispositivo**: Podemos coletar modelo do aparelho e versão do sistema operacional para diagnosticar erros e garantir a compatibilidade do aplicativo.

### E. Armazenamento Local
Para permitir o funcionamento totalmente offline e rápido, as informações são salvas localmente no dispositivo do usuário utilizando o banco de dados interno e seguro **Hive**.

---

## 2. Permissões Solicitadas

O aplicativo pode solicitar permissões específicas do sistema operacional para executar suas funções:

| Permissão | Finalidade |
| :--- | :--- |
| `INTERNET` | Necessária para realizar a autenticação, sincronizar as contas de forma segura com a nuvem (Firebase Firestore) e validar assinaturas. |
| `READ/WRITE_EXTERNAL_STORAGE` | Utilizada para exportar, selecionar e restaurar arquivos de backup local no armazenamento do dispositivo (em versões do Android onde aplicável). |
| `POST_NOTIFICATIONS` | (Android 13+) Necessária para exibir alertas visuais e lembretes de contas perto do vencimento. |
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | Utilizada para agendar as notificações locais nos horários exatos definidos pelo usuário. |
| `WAKE_LOCK` / `RECEIVE_BOOT_COMPLETED` | Necessárias para reconfigurar os lembretes automáticos após o dispositivo ser reiniciado. |

---

## 3. Uso das Informações

Os dados coletados são usados exclusivamente para:
* Prover o controle financeiro pessoal e visualização gráfica de gastos.
* Sincronizar dados entre múltiplos dispositivos do mesmo usuário através da nuvem.
* Processar a validação de assinaturas Premium.
* Enviar lembretes e alertas de contas a vencer.
* Permitir a criação de cópias de segurança (backups) locais e em nuvem.
* Manter a conta do usuário segura.

**Importante:** Nós não vendemos, alugamos ou compartilhamos seus dados financeiros ou pessoais com terceiros para fins publicitários ou comerciais.

---

## 4. Serviços de Terceiros

O aplicativo utiliza serviços de terceiros confiáveis para infraestrutura, autenticação e pagamentos, que podem coletar informações de acordo com suas próprias políticas de privacidade:
* **Google Play Services / Google Sign-In** ([Política de Privacidade do Google](https://policies.google.com/privacy))
* **Firebase Authentication e Cloud Firestore** ([Privacidade e Segurança no Firebase](https://firebase.google.com/support/privacy))
* **Firebase Cloud Messaging** (Para envio de notificações push)
* **Google Play Billing / Apple In-App Purchases** (Para o processamento seguro de assinaturas)

---

## 5. Segurança dos Dados

Empregamos medidas técnicas e administrativas apropriadas para proteger seus dados financeiros e pessoais contra acessos não autorizados, alteração, divulgação ou destruição. A transmissão de dados com os servidores do Firebase e lojas de aplicativos é criptografada via protocolo HTTPS/TLS de ponta a ponta.

---

## 6. Exclusão de Dados e Direitos do Usuário

Em conformidade com a LGPD e as regras de segurança de dados das lojas de aplicativos, você possui total controle sobre seus dados e pode gerenciar ou excluí-los a qualquer momento:
* **Exclusão direta pelo aplicativo**: Você pode apagar permanentemente todas as suas contas, lançamentos e categorias locais e na nuvem, ou excluir definitivamente sua conta de usuário acessando a seção **"Conta e Dados"** ou **"Perfil"** nas configurações do aplicativo. Ao excluir sua conta, os dados são removidos de nossos servidores.
* **Solicitação via e-mail**: Caso prefira, você também pode solicitar a exclusão total de seus dados e de sua conta enviando um e-mail para **dev.marquess@gmail.com**. A exclusão será processada e confirmada em até 48 horas.
* **Limpeza local**: A remoção das informações locais do dispositivo pode ser feita desinstalando o aplicativo ou limpando os dados de armazenamento do app nas configurações do sistema.

---

## 7. Contato e Suporte

Caso tenha dúvidas sobre esta Política de Privacidade, solicitações sobre assinaturas, reclamações ou deseje solicitar a exclusão manual de seus dados, entre em contato diretamente pelo e-mail: **dev.marquess@gmail.com**.
