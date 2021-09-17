---
title: Use pacotes de dados de exemplo com sua assinatura do Programa para Desenvolvedores do Microsoft 365
description: Saiba como instalar pacotes de dados de exemplo na sua assinatura de desenvolvedor para ajudar a colocar seu ambiente de área restrita em funcionamento rapidamente.
ms.localizationpriority: high
ms.openlocfilehash: fb111d13a940fc5dffbba12b092a8f2bfd313872
ms.sourcegitcommit: aadd59458002b5ffcb857e92eb46c92669587d78
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/16/2021
ms.locfileid: "59396718"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a>Use pacotes de dados de exemplo com sua assinatura do Programa para Desenvolvedores do Microsoft 365

Você pode instalar pacotes de dados de exemplo na sua assinatura do Programa para Desenvolvedores do Microsoft 365. Os pacotes de dados de exemplo poupam seu tempo, instalando automaticamente dados e conteúdos necessários para criar e testar suas soluções. Inclui os usuários, os metadados e as fotos fictícias para simular um ambiente corporativo pequeno. Você pode instalar rapidamente os dados de exemplo para se concentrar nas suas soluções, em vez de perder tempo criando esses dados de exemplo.

Você pode encontrar pacotes de dados de exemplo no [painel do Programa para Desenvolvedores do Microsoft 365](https://developer.microsoft.com/office/profile), na parte inferior do bloco de assinatura.

![Captura de tela do bloco da assinatura na página de painel](images/sample-data-pack-ux-tile-users-beginning.PNG)

Os pacotes de dados de exemplo a seguir estão atualmente disponíveis:

- Usuários - Instala 16 usuários fictícios com licenças, caixas de correio e metadados, incluindo nomes e fotos para cada usuário. Use as APIs do Microsoft Graph para trabalhar com os dados de exemplo de usuário da seguinte maneira:
  - Obter detalhes específicos do usuário
  - Atualizar usuário
  - Obter relatórios diretos
  - Preparar organograma  
  - Obter usuários por departamento

- Email e eventos - Adiciona conversas de email do Outlook e eventos de calendário para cada um dos 16 exemplos de usuários. Use as APIs do Microsoft Graph para trabalhar com os dados de exemplo de email e eventos da seguinte maneira:
  - Receba emails por usuários
  - Obter emails filtrados por data
  - Obter eventos futuros
  - Atualizar/excluir eventos futuros

> [!NOTE]
> Você deve instalar o pacote de dados de exemplo de Usuários antes de instalar o Email e Eventos.

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a>O que os pacotes de dados de exemplo adicionam à minha assinatura?

O pacote de dados de exemplo de Usuários cria 16 usuários fictícios na sua assinatura e inclui as licenças para cada usuário, e caixas de correio, nomes, metadados e fotos para cada um deles.

O pacote de dados de exemplo de Email e Eventos adiciona conversas de email do Outlook e eventos de calendário para cada um dos 16 usuários instalados.

## <a name="how-do-i-install-the-users-sample-data-pack"></a>Como faço para instalar o pacote de dados de exemplo de Usuários?

Antes de instalar o pacote de dados de exemplo de Usuários, certifique-se de que você tem uma assinatura de desenvolvedor do Microsoft 365 e que atribuiu uma licença a si mesmo como administrador.

> [!NOTE]
> Certifique-se de que tem 16 usuários disponíveis na sua assinatura. Sua assinatura inclui 25 usuários. Se você já tiver configurado mais de 10 usuários, primeiro remova alguns usuários para garantir que a instalação seja bem-sucedida.

Para instalar o pacote de dados de exemplo de Usuários:

1. Selecione a caixa **Usuários** na parte inferior de seu bloco de assinatura.
2. Copie a ID do administrador. Será necessário acessar sua assinatura.
3. Insira sua ID e senha de administrador na página de entrada.
4. Conceda permissões como administrador da sua assinatura de desenvolvedor do Microsoft 365.

![Captura de tela mostrando a caixa de diálogo de permissões e consentimento. ](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. Configurar suas senhas para todos os usuários de amostra. Você precisará ter uma senha compartilhada definida para facilitar a administração de todos os seus usuários fictícios.

![Captura de tela da caixa de diálogo para adicionar senha de usuário compartilhado](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. Os dados serão instalados. A instalação levará cerca de 5 min.

![Captura de tela mostrando o processo de instalação no bloco do painel](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. Quando a instalação for concluída, você receberá uma notificação por email e a caixa em seu bloco de assinatura ficará verde. Agora, você pode instalar o pacote de dados de exemplo de Email e Eventos.

![Captura de tela do bloco do painel com o Email e Eventos prontos para instalação](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a>Como instalar o pacote de dados de exemplo de Email e Eventos?

Depois de instalar o pacote de dados de exemplo Usuários, você pode instalar o Email e Eventos.

1. Escolha a caixa **Email &amp; Eventos** no bloco da sua assinatura.
2. Clique em **Instalar** para iniciar a instalação.

![Captura de tela da caixa de diálogo de instalação](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> Se você acabou de criar sua assinatura, ela deve ser totalmente provisionada antes do início da instalação. Isso pode levar algumas horas. Após iniciada, a instalação pode levar até 20 minutos para ser concluída.

3. Quando a instalação for concluída, você receberá uma notificação por email e a caixa em seu bloco de assinatura ficará verde.

## <a name="how-do-i-install-the-sharepoint-sample-data-pack"></a>Como instalar o pacote de dados de exemplo do SharePoint?

O pacote de dados de exemplo do SharePoint inclui sete modelos de site diferentes do SharePoint à sua escolha para experimentar e modelar soluções do SharePoint para colaboração, comunicação, envolvimento e gerenciamento de conhecimento.

Estes são alguns dos modelos mais populares do [livro de aparência do PnP do SharePoint](https://provisioning.sharepointpnp.com/). Hoje em dia, é simples criar exemplos de soluções de sites e páginas bonitos e rápidos que ficam ótimos em qualquer dispositivo ou tela. Inspire-se com esses designs ou adicione-os ao seu locatário da área restrita para começar a criar seu próximo site.

Os modelos podem ser instalados em sua assinatura. Depois de instalar um modelo, você tem a opção de instalar os demais. O processo de instalação inclui as seguintes etapas:

1. Selecione o modelo que você deseja no menu suspenso.

  ![Captura de tela da tela de seleção de modelo do SharePoint](images/select-sharepoint-template.jpg)

2. Configure opções personalizadas para seus sites ou aceite os valores padrão.
3. Use a ID de administrador do seu locatário da área restrita e a senha para autenticar e dar permissões para a instalação. 

A instalação procederá automaticamente.

>**Observação:** O provisionamento desses modelos de site funciona apenas com as assinaturas de desenvolvedor em inglês do Office 365 E3 ou do Microsoft 365 E5, e todo o conteúdo incluído é apenas em inglês.

## <a name="what-sharepoint-templates-are-available"></a>Quais modelos do SharePoint estão disponíveis?

O pacote de exemplo do SharePoint inclui sete modelos diferentes.

### <a name="team-site-with-data"></a>Site de equipe com dados

Este modelo inclui várias listas e bibliotecas de documentos que são automaticamente associadas a um site de equipe do SharePoint para ajudá-lo a desenvolver soluções usando a Estrutura do SharePoint, o PowerApps e o Microsoft Graph.

Este modelo inclui os seguintes dados:

- Uma lista de contatos com contatos pré-preenchidos
- Uma lista preenchida com mais de 6.000 itens
- Bibliotecas de documentos com exemplos de documentos do PowerPoint, Excel, Word e OneNote
- Uma lista de eventos com itens de anúncio

Este modelo se integra com Dados de exemplo do usuário.

### <a name="work--contoso"></a>Trabalho @ Contoso
O modelo Trabalho @ Contoso consiste em vários conjuntos de sites, todos automaticamente associados ao site do hub, para mostrar como funciona todos os recursos de agregação padrão.

O modelo contém as estruturas e ativos a seguir:

- Conjunto de sites principal como um site do hub
- Dois sites de comunicação associados aos sites do hub – Sites de benefícios e caridade
- Um site de equipe associado ao site do hub - site de equipe
- Exemplos de artigos de notícias nos conjuntos de subsites
- Exemplos de arquivos do Word, do Excel e do PowerPoint.
- Exemplo de conteúdo de imagem usado nos conjuntos de sites

Os conjuntos de subsites usam os mesmos modelos, que também podem ser provisionáveis separadamente deste serviço.

>**Observação:** Se o modelo for aplicado na parte superior de um site de comunicação existente, o conteúdo da página de boas-vindas será substituído.

### <a name="leadership-connection-leadership-news-events-engagement"></a>Conexão de Liderança: notícias sobre liderança, eventos e envolvimento

Este site de liderança fornece informações sobre os objetivos e prioridades da equipe de liderança e inspira o envolvimento com eventos e conversas.

Adicionar esse design ao seu locatário criará o seguinte conteúdo:

- Exemplo de página de boas-vindas com demonstração de Web Parts
- Exemplo de notícias sobre a demonstração de designs de página modernos diferentes

Este modelo se integra com Dados de exemplo do usuário.

### <a name="the-landing-news-resources-personalized-content"></a>A Página Principal: notícias, recursos e conteúdo personalizado

Esse site de comunicação foi projetado para ser o local em que seus funcionários podem encontrar as notícias e os recursos de que precisam, além de conteúdo personalizado sob medida para eles.

Adicionar esse design ao seu locatário criará o seguinte conteúdo:

- Estrutura de demonstração para o site inicial do portal
- Estrutura da página de boas-vindas personalizada
- Seis exemplos adicionais de páginas e notícias modernas
- Exemplo de imagens e documentos do Office

### <a name="the-perspective-news-video-personalized-content"></a>A Perspectiva: notícias, vídeo e conteúdo personalizado

Projetado para oferecer novidades e conteúdo personalizado, este site também inclui vídeos para inspirar ainda mais envolvimento.
Adicionar esse design ao seu locatário criará o seguinte conteúdo:

- Designs da página de boas-vindas personalizada
- Exemplo de modelo de página para artigos de notícias
- Doze exemplos de notícias

### <a name="new-employee-onboarding-hub-connect-engage-inform"></a>Novo Hub de Integração de Funcionários: Conectar, Interagir, Informar

Simplifique e refine seu novo processo de integração de funcionários com modelos pré-desenvolvidos que abordam a Pré-integração, a integração ao Nível empresarial e os cenários de integração ao Nível departamental. Esta solução digital oferece quatro modelos de site diferentes que contêm conteúdo previamente preenchido que pode ser personalizado para se alinhar com os objetivos da sua organização.

Adicionar esse design ao seu locatário criará o seguinte conteúdo:

- Site de pré-lançamento, site de integração corporativo e dois sites de integração departamentais
- Páginas iniciais personalizadas e preenchidas previamente para cada site
- Site de Hub configurado para integração corporativa e sites associados para integração departamental
- Nova lista de verificação de funcionários criada nas Listas do Microsoft Office SharePoint Online para ajudar os novos contratados a se integrarem com êxito
- Conteúdo de exemplo para a Web Part de pessoas, Web Part do Yammer, Web Part de notícias e Web Part de links rápidos
- Perguntas frequentes pré-escritas para cada site
- Recomendações para criar experiências sociais e envolventes, como incluir um vídeo de boas-vindas usando a Web Part do YouTube no site de Pré-integração

### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a>Comunicações de Crise: comunicados, notícias, recursos, comunidades e chamadas de ação

Mantenha as pessoas informadas, envolvidas e progredindo durante crises: de eventos climáticos extremos a emergências de segurança e saúde. Este modelo cria um recurso central para líderes e comunicadores compartilharem notícias e comunicados importantes. Uma única fonte de verdade na qual as pessoas podem se manter atualizadas e um lugar para conectar pessoas em toda a organização.

Adicionar esse design ao seu locatário criará o seguinte conteúdo:

- Página de boas-vindas personalizada criada usando uma Web Part
- Quatro notícias com conteúdo de exemplo

Este modelo se integra com Dados de exemplo do usuário.

## <a name="are-more-sample-data-packs-coming"></a>Mais pacotes de dados de exemplo estão chegando?

Sim. No futuro, consideraremos adicionar pacotes de dados de exemplo para mais produtos e tecnologias, incluindo o Microsoft Teams. Se você tiver sugestões para amostras de pacotes de dados que gostaria de ver, [nos avise](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>Posso instalar pacotes de dados de exemplo em minhas outras assinaturas do Microsoft 365?

Não. Estes exemplos de pacotes de dados só são compatíveis com a assinatura do desenvolvedor Microsoft 365 que você recebe como parte do Programa para Desenvolvedores do Microsoft 365.

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>Como posso ver os dados de exemplo na minha assinatura?

Depois de instalar o pacote de dados de exemplo de Usuários, para ver os usuários que foram adicionados, acesse o [**Centro de Administração do Microsoft 365**](https://admin.microsoft.com/) na assinatura de desenvolvedor de Microsoft 365. Em **Usuários**, selecione **Usuários ativos**. Você verá a lista de 16 usuários. Você pode selecionar um usuário para exibir os metadados associados, incluindo as fotos e as licenças.

![Captura de tela de 16 usuários no Centro de administração do Microsoft 365, com metadados de um usuário selecionado](images/content-packs-07.PNG)

Depois de instalar o pacote de exemplo de E-mail e Eventos, para visualizar os dados de exemplo, no [**Centro de Administração do Microsoft 365**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide), escolha **Mostrar tudo** e, em seguida, selecione **Exchange**. No Centro de administração do Exchange, ao selecionar **destinatários**, você pode ver que todos os 16 usuários têm caixas de correio com email e eventos adicionados.
![Captura de tela de 16 usuários adicionados ao Centro de administração do Exchange](images/content-packs-08.PNG)

## <a name="see-also"></a>Também consulte

- [Configurar uma assinatura de desenvolvedor do Microsoft 365](microsoft-365-developer-program-get-started.md)
