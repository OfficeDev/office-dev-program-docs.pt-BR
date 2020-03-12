---
title: Use pacotes de dados de exemplo com sua assinatura do Programa para Desenvolvedores do Microsoft 365
description: Saiba como instalar pacotes de dados de exemplo na sua assinatura de desenvolvedor para ajudar a colocar seu ambiente de área restrita em funcionamento rapidamente.
localization_priority: Priority
ms.openlocfilehash: 2cc7027ccad5b7971c1ae9d49416b9b25663c255
ms.sourcegitcommit: 9c7a1aa1c562adb350fefc8068e154fa6f9a4ee3
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600799"
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

5. Configure suas senhas para todos os usuários de exemplo. Será preciso ter uma senha compartilhada definida para facilitar a administração de todos os seus usuários fictícios.

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

## <a name="are-more-sample-data-packs-coming"></a>Mais pacotes de dados de exemplo estão chegando?

Sim. Adicionaremos pacotes de dados de exemplo do SharePoint e do OneDrive. No futuro, consideraremos adicionar pacotes de dados de exemplo para mais produtos e tecnologias, incluindo Suplementos do Office, o Microsoft Teams e muito mais.

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>Posso instalar pacotes de dados de exemplo em minhas outras assinaturas do Microsoft 365?

Não. Esses pacotes de dados de exemplo são compatíveis apenas com a assinatura de desenvolvedor do Microsoft 365, que você obtém como parte do Programa de Desenvolvedores do Microsoft 365.

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>Como posso ver os dados de exemplo na minha assinatura?

Depois de instalar o pacote de dados de exemplo de Usuários, para ver os usuários que foram adicionados, acesse o **Centro de Administração do Microsoft 365** na assinatura de desenvolvedor de Microsoft 365. Em **Usuários**, selecione **Usuários ativos**. Você verá a lista de 16 usuários. Você pode selecionar um usuário para exibir os metadados associados, incluindo as fotos e as licenças.

![Captura de tela de 16 usuários no Centro de administração do Microsoft 365, com metadados de um usuário selecionado](images/content-packs-07.PNG)

Depois de instalar o pacote de exemplo de Email e Eventos, para visualizar os dados de exemplo, no **Centro de administração do Microsoft 365**, escolha **Mostrar tudo** e, em seguida, selecione **Exchange**. No Centro de administração do Exchange, ao selecionar **destinatários**, você pode ver que todos os 16 usuários têm caixas de correio com email e eventos adicionados.
![Captura de tela de 16 usuários adicionados ao Centro de administração do Exchange](images/content-packs-08.PNG)

## <a name="see-also"></a>Também consulte

- [Configurar uma assinatura de desenvolvedor do Microsoft 365](microsoft-365-developer-program-get-started.md)
