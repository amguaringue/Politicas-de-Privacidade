# Política de Privacidade do App Esculápio

**Última atualização: 02 de Fevereiro de 2026**

A sua privacidade é uma prioridade para nós. Esta política de privacidade explica como o aplicativo **Esculápio** (doravante referido como "o Aplicativo") coleta, usa e protege as informações do usuário.

O Esculápio foi desenvolvido com foco na transparência e no respeito aos dados do cidadão, alinhado às diretrizes de proteção de dados e saúde pública.

## 1. Coleta de Dados

O Aplicativo foi projetado para funcionar com o mínimo de coleta de dados possível. Não exigimos criação de conta, login ou envio de dados pessoais para servidores proprietários.

### 1.1 Dados de Localização (Geolocalização)
O Aplicativo pode solicitar acesso à sua localização aproximada ou precisa (GPS).
* **Finalidade:** A localização é utilizada exclusivamente para fornecer dados contextualizados de saúde e ambiente, como: alertas de Dengue locais, Índice de Qualidade do Ar (AQI) e Índice Ultravioleta (UV) da sua região.
* **Armazenamento:** A coordenada geográfica é processada em tempo real e não é armazenada em nossos servidores. Ela é enviada de forma anônima para as APIs de terceiros listadas abaixo apenas para obter a previsão local.
* **Controle:** O usuário pode revogar o acesso à localização a qualquer momento nas Configurações do iOS. Caso negado, o usuário poderá selecionar manualmente uma capital brasileira.

### 1.2 Dados de Cache Local
Para melhorar a experiência e permitir o funcionamento offline, o Aplicativo armazena localmente no seu dispositivo (`UserDefaults`):
* A última cidade selecionada.
* Os últimos dados estatísticos visualizados (gráficos da OMS).
Estes dados permanecem apenas no seu dispositivo e são removidos se você desinstalar o aplicativo.

## 2. Compartilhamento com Terceiros

O Esculápio atua como um agregador de dados de saúde pública. Para funcionar, o aplicativo realiza conexões seguras (HTTPS) diretamente do seu dispositivo para os seguintes serviços públicos e abertos:

1.  **InfoDengue (Fiocruz/FGV):** Para obtenção de alertas epidemiológicos de arboviroses.
2.  **Open-Meteo & Air Quality API:** Para dados meteorológicos, radiação UV e qualidade do ar.
3.  **Global Health Observatory (WHO/OMS):** Para dados estatísticos históricos de saúde.
4.  **Google News (RSS):** Para exibição de notícias públicas sobre saúde.

**Nota:** Nenhuma informação pessoal identificável (como nome, CPF ou email) é compartilhada com estes serviços. Eles recebem apenas os parâmetros técnicos necessários para a consulta (ex: geocode da cidade ou coordenadas de latitude/longitude).

## 3. Segurança

Implementamos medidas de segurança padrão da indústria (como Apple App Transport Security) para proteger a comunicação entre o seu dispositivo e as APIs de saúde. O Aplicativo não mantém banco de dados de usuários.

## 4. Retenção de Dados

Como não coletamos dados pessoais em servidores próprios, não possuímos dados para reter. Os dados em cache no seu dispositivo são de sua propriedade e controle total, sendo excluídos automaticamente na desinstalação do app.

## 5. Privacidade de Menores

O Aplicativo não coleta intencionalmente dados de crianças. O conteúdo é informativo e voltado para saúde pública geral.

## 6. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente para refletir melhorias no aplicativo ou mudanças na legislação. Recomendamos que você revise esta página regularmente para obter as informações mais recentes.

## 7. Contato

Se você tiver dúvidas sobre esta Política de Privacidade ou sobre as práticas do aplicativo, entre em contato conosco através do email:

**amguaringue@gmail.com**

---
*Este aplicativo é uma iniciativa independente de vigilância em saúde, utilizando dados abertos governamentais e internacionais.*
