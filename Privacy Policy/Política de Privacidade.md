# Política de Privacidade

**Data de Vigência:** 07.08.2026  
**Controlador de Dados:** Tomasz Rutkowski, pessoa física com residência na Polônia, desenvolvedor independente do aplicativo "Chess M8".  
**Nome do Aplicativo:** ChessM8

---

## 1. Introdução
Respeitamos sua privacidade. Esta Política de Privacidade explica como o ChessM8 (o "Aplicativo") coleta, usa e protege informações. Ao usar o Aplicativo, você concorda com os termos desta política.

---

## 2. Coleta e Processamento de Dados (Arquitetura Local-First)
O Aplicativo foi projetado com abordagem "Local-First". Isso significa que priorizamos sua privacidade mantendo seus dados no seu dispositivo.

### A. Dados Pessoais
O Aplicativo obtém dados públicos de partidas de xadrez (arquivos PGN) de serviços de terceiros, que podem incluir:
* Nomes de usuário (por exemplo, Lichess.org ou Chess.com).
* Jogadas da partida, carimbos de data/hora e classificações.

Não armazenamos dados pessoais em nossos servidores; os dados são transmitidos diretamente do seu dispositivo para as APIs de terceiros mediante sua solicitação.

### B. Dados Técnicos
* **Endereço IP:** Quando o Aplicativo se conecta a APIs de terceiros, seu endereço IP fica visível para esses provedores (Chess.com/Lichess), mas não é enviado a nós nem armazenado por nós.

### C. Permissões do Dispositivo
Para funcionar, o Aplicativo requer:
* **Acesso à Internet:** Para conectar-se especificamente às APIs do Chess.com e Lichess.org.
* **Armazenamento (Leitura/Gravação):** Para salvar e recuperar arquivos PGN no seu dispositivo (quando aplicável).

---

## 3. Finalidades e Base Legal para o Processamento

### A. Usuários do Espaço Econômico Europeu (EEE) (GDPR)
Se você estiver localizado no EEE, processamos dados pessoais para as seguintes finalidades:
1. **Fornecimento do serviço e análise de partidas:** Permitir que você baixe suas partidas, as analise e exiba estatísticas dentro do Aplicativo.  
   *Base Legal:* Artigo 6(1)(b) do GDPR (execução de contrato para fornecer funcionalidades solicitadas).
2. **Garantia de funcionalidade técnica:** Uso de acesso à internet para comunicar-se com os servidores do Chess.com e Lichess.org de forma segura e confiável.  
   *Base Legal:* Artigo 6(1)(f) do GDPR (interesse legítimo em garantir funcionalidade e segurança adequadas).
3. **Armazenamento local para uso offline:** Salvar arquivos PGN no seu dispositivo para acesso sem conexão ativa.  
   *Base Legal:* Artigo 6(1)(b) do GDPR.

---

## 4. Serviços de Terceiros
O Aplicativo atua como uma interface cliente. Ao usar a funcionalidade "Importar", seu dispositivo conecta-se diretamente a:
* **Chess.com** (sujeito à sua Política de Privacidade)
* **Lichess.org** (sujeito à sua Política de Privacidade)

Não atuamos como intermediários. Seus cabeçalhos de solicitação (incluindo o User-Agent do Aplicativo) são visíveis a esses serviços durante a conexão.

---

## 5. Divulgações Regionais de Privacidade e Direitos do Usuário

Como não armazenamos seus dados em servidores externos, você mantém controle direto sobre suas informações, independentemente de onde reside.

### 5.1. Espaço Econômico Europeu (EEE) e Reino Unido (UK)
Sob o GDPR e o UK GDPR, você tem os seguintes direitos:
* **Acesso e Portabilidade:** Todos os dados são armazenados diretamente em seu dispositivo.
* **Exclusão:** Você pode excluir todos os dados a qualquer momento limpando o cache/dados do Aplicativo nas configurações do dispositivo ou desinstalando o Aplicativo.
* **Direito de Opor/Restringir:** Você pode parar o processamento a qualquer momento cessando o uso do Aplicativo ou desativando as funções de importação.

### 5.2. Califórnia / Estados Unidos (CCPA / CPRA)
* **Sem Venda ou Compartilhamento de Informações Pessoais:** Não vendemos nem compartilhamos informações pessoais, e não o fizemos nos 12 meses anteriores.
* **Informações Sensíveis:** Não coletamos nem processamos informações pessoais sensíveis que exijam controles de exclusão.
* **Exercício de Direitos:** Residentes da Califórnia podem exercer seus direitos gerenciando o armazenamento local do dispositivo ou entrando em contato conosco.

### 5.3. Brasil (LGPD)
Sob a Lei Geral de Proteção de Dados (LGPD):
* **Bases Legais:** O processamento para análise de partidas e armazenamento local é realizado nos termos do Artigo 7(V) da LGPD (execução de contrato). Conexões técnicas a APIs externas são realizadas com base no Artigo 7(IX).
* **Direitos:** Você pode exercer seus direitos de confirmação, acesso ou exclusão diretamente gerenciando o armazenamento local no seu dispositivo.

### 5.4. Índia (DPDP Act 2023)
Sob a Lei de Proteção de Dados Pessoais Digitais de 2023:
* **Direitos do Titular:** Você tem o direito de solicitar a exclusão e retirar consentimento para o processamento.
* **Execução:** Como todos os dados residem localmente em seu dispositivo, você pode exercer esses direitos limpando os dados do Aplicativo ou desinstalando-o.

### 5.5. Outras Jurisdições
Se você reside em outra jurisdição (como Canadá, Austrália, Suíça, Japão ou Singapura), você mantém plenos direitos de acessar e apagar seus dados locais diretamente no seu dispositivo.

---

## 6. Transferências Internacionais de Dados
Ao usar as funções de importação, seu dispositivo conecta-se diretamente a servidores de terceiros:
* **Chess.com:** Servidores podem estar localizados nos Estados Unidos. A conexão com o Chess.com faz com que seu dispositivo envie solicitações de rede padrão (incluindo seu endereço IP e nome de usuário solicitado) diretamente a esses servidores.
* **Lichess.org:** Infraestrutura baseada na União Europeia (França/Alemanha).

Se você acessar o Aplicativo de fora dos Estados Unidos ou da União Europeia, iniciar uma importação resultará na transmissão direta dos dados de conexão para esses servidores de terceiros através de fronteiras internacionais.

---

## 7. Análises, Perfilamento e SDKs de Terceiros
* **Sem SDKs de Rastreamento:** O Aplicativo não utiliza SDKs de análise, publicidade ou relatórios de falhas (como Google Analytics, Firebase ou AdMob).
* **Sem Perfilamento ou Decisões Automatizadas:** Não fazemos perfilamento, avaliação ou decisões automatizadas com base em seus dados pessoais ou histórico de jogo.
* **Sem Telemetria:** Nenhum dado sobre sua interação com o Aplicativo é transmitido para nós.

---

## 8. Segurança dos Dados
Como os dados são armazenados localmente, a segurança dos seus dados depende da segurança do seu dispositivo. Recomendamos:
* Usar código de acesso do dispositivo ou bloqueio biométrico.
* Manter o sistema operacional atualizado.
* Evitar o uso do Aplicativo em dispositivos comprometidos ("rooted" ou "jailbroken").

---

## 9. Privacidade de Crianças
O Aplicativo não é direcionado a crianças menores de 16 anos (ou a idade mínima exigida pela legislação local, se menor — mas não abaixo de 13).

Não permitimos de forma intencional o uso do Aplicativo por crianças abaixo dessa idade nas funcionalidades de importação. O uso de serviços de terceiros (Chess.com e Lichess.org) via Aplicativo continua sujeito às políticas de idade desses serviços.

---

## 10. Lei Aplicável e Resolução de Disputas
Esta Política de Privacidade e quaisquer disputas decorrentes dela serão regidas e interpretadas de acordo com as leis da Polônia, sem considerar conflitos de leis.

---

## 11. Direito de Apresentar Reclamação (Usuários do EEE)
Se você está localizado no EEE e acredita que seus direitos de privacidade foram violados, você pode apresentar uma reclamação à sua autoridade de proteção de dados local ou ao nosso supervisor principal:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warsaw, Poland  
Website: https://uodo.gov.pl

---

## 12. Alterações nesta Política
Podemos atualizar esta Política de Privacidade periodicamente para refletir mudanças em nossas práticas ou nas leis aplicáveis. Avisaremos sobre mudanças publicando a nova Política de Privacidade no Aplicativo ou em nosso repositório.

Se fizermos alterações materiais na forma como processamos seus dados (por exemplo, mudando da arquitetura local-first), forneceremos um aviso mais destacado, como uma notificação no aplicativo, antes de quaisquer alterações entrarem em vigor.

---

## 13. Contate-nos
Para quaisquer questões relacionadas à privacidade ou para exercer seus direitos de dados, entre em contato com o Controlador de Dados:

**Email:** wottomekr@gmail.com
*Endereço postal completo e detalhes adicionais de identificação estão disponíveis mediante solicitação por escrito em conformidade com o Artigo 13 do GDPR.*
