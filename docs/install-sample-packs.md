---
title: Использование примеров пакетов данных в подписке разработчика на Office 365
description: Узнайте, как установить примеры пакетов данных в подписке разработчика на Office 365, чтобы быстро подготовить среду в песочнице.
localization_priority: Priority
ms.openlocfilehash: 16e605080673678b750ebeab4501ceb980cea6cb
ms.sourcegitcommit: 76c5e3c9b58026471378e7634d121842690fd517
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/10/2019
ms.locfileid: "35618864"
---
# <a name="use-sample-data-packs-with-your-office-365-developer-subscription"></a><span data-ttu-id="68e1a-103">Использование примеров пакетов данных в подписке разработчика на Office 365</span><span class="sxs-lookup"><span data-stu-id="68e1a-103">Use sample data packs with your Office 365 developer subscription</span></span>

<span data-ttu-id="68e1a-104">Вы можете установить примеры пакетов данных в подписке разработчика на Office 365.</span><span class="sxs-lookup"><span data-stu-id="68e1a-104">You can install sample data packs on your Office 365 developer subscription.</span></span> <span data-ttu-id="68e1a-105">Примеры пакетов данных позволяют экономить время, автоматически устанавливая данные и содержимое, необходимые для создания и тестирования решений.</span><span class="sxs-lookup"><span data-stu-id="68e1a-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="68e1a-106">Сюда относятся вымышленные пользователи, метаданные и фотографии для имитации небольшой корпоративной среды.</span><span class="sxs-lookup"><span data-stu-id="68e1a-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="68e1a-107">Вы можете быстро установить пример данных, чтобы не тратить время на их создание, а сосредоточиться на своих решениях.</span><span class="sxs-lookup"><span data-stu-id="68e1a-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="68e1a-108">Примеры пакетов данных можно найти на [информационной панели программы для разработчиков Office 365](https://developer.microsoft.com/office/profile) в нижней части плитки подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="68e1a-108">You can find sample data packs on your [Office 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your Office 365 subscription tile.</span></span>

![Снимок экрана: плитка подписки на странице информационной панели](images/content-packs-06.PNG)

<span data-ttu-id="68e1a-110">В настоящее время доступны следующие примеры пакетов данных.</span><span class="sxs-lookup"><span data-stu-id="68e1a-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="68e1a-111">Пользователи. Устанавливает 16 вымышленных пользователей с лицензиями, почтовыми ящиками и метаданными, включая имена и фотографии для каждого пользователя.</span><span class="sxs-lookup"><span data-stu-id="68e1a-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="68e1a-112">Используйте API Microsoft Graph для работы с примерами данных пользователей следующим образом:</span><span class="sxs-lookup"><span data-stu-id="68e1a-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="68e1a-113">Получение сведений об определенном пользователе</span><span class="sxs-lookup"><span data-stu-id="68e1a-113">Get specific user details</span></span>
  - <span data-ttu-id="68e1a-114">Обновление пользователя</span><span class="sxs-lookup"><span data-stu-id="68e1a-114">Update user</span></span>
  - <span data-ttu-id="68e1a-115">Получение подчиненных</span><span class="sxs-lookup"><span data-stu-id="68e1a-115">Get user's direct reports.</span></span>
  - <span data-ttu-id="68e1a-116">Подготовка организационной диаграммы</span><span class="sxs-lookup"><span data-stu-id="68e1a-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="68e1a-117">Получение пользователей по отделам</span><span class="sxs-lookup"><span data-stu-id="68e1a-117">Get users by department</span></span>

- <span data-ttu-id="68e1a-118">Почта и события. Добавляет беседы электронной почты Outlook и события календаря для каждого из 16 примеров пользователей.</span><span class="sxs-lookup"><span data-stu-id="68e1a-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="68e1a-119">Используйте API Microsoft Graph для работы с примерами данных почты и событий следующим образом:</span><span class="sxs-lookup"><span data-stu-id="68e1a-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="68e1a-120">Получение сообщений электронной почты для пользователей</span><span class="sxs-lookup"><span data-stu-id="68e1a-120">Get emails by users</span></span>
  - <span data-ttu-id="68e1a-121">Получение сообщений электронной почты, отфильтрованных по дате</span><span class="sxs-lookup"><span data-stu-id="68e1a-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="68e1a-122">Получение предстоящих событий</span><span class="sxs-lookup"><span data-stu-id="68e1a-122">Get upcoming events</span></span>
  - <span data-ttu-id="68e1a-123">Обновление и удаление предстоящих событий</span><span class="sxs-lookup"><span data-stu-id="68e1a-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="68e1a-124">Перед установкой примера данных "Почта и события" требуется установить пример пакета данных "Пользователи".</span><span class="sxs-lookup"><span data-stu-id="68e1a-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-office-365-subscription"></a><span data-ttu-id="68e1a-125">Что добавляют примеры пакетов данных в мою подписку на Office 365?</span><span class="sxs-lookup"><span data-stu-id="68e1a-125">What do the sample data packs add to my Office 365 subscription?</span></span>

<span data-ttu-id="68e1a-126">Пример пакета данных "Пользователи" создает в вашей подписке 16 вымышленных пользователей и добавляет лицензии, а также почтовые ящики, имена, метаданные и фотографии для каждого пользователя.</span><span class="sxs-lookup"><span data-stu-id="68e1a-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="68e1a-127">Пример пакета данных "Почта и события" добавляет беседы электронной почты Outlook и события календаря для каждого из 16 установленных пользователей.</span><span class="sxs-lookup"><span data-stu-id="68e1a-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="68e1a-128">Как установить пример пакета данных "Пользователи"?</span><span class="sxs-lookup"><span data-stu-id="68e1a-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="68e1a-129">Перед установкой примера пакета данных "Пользователи" убедитесь в наличии подписки разработчика на Office 365 и назначьте для себя лицензию администратора.</span><span class="sxs-lookup"><span data-stu-id="68e1a-129">Before you install the Users sample data pack, make sure that you have an Office 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

<span data-ttu-id="68e1a-130">Чтобы установить пример пакета данных "Пользователи":</span><span class="sxs-lookup"><span data-stu-id="68e1a-130">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="68e1a-131">Выберите поле **Пользователи** внизу плитки подписки.</span><span class="sxs-lookup"><span data-stu-id="68e1a-131">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="68e1a-132">Скопируйте идентификатор администратора. Он потребуется для входа в вашу подписку.</span><span class="sxs-lookup"><span data-stu-id="68e1a-132">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="68e1a-133">Введите идентификатор администратора и пароль на странице входа.</span><span class="sxs-lookup"><span data-stu-id="68e1a-133">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="68e1a-134">Предоставьте согласие на предоставление доступа в качестве администратора подписки разработчика на Office 365.</span><span class="sxs-lookup"><span data-stu-id="68e1a-134">Consent to the permissions as an administrator of your Office 365 developer subscription.</span></span>

![Снимок экрана: диалоговое окно согласия на предоставление доступа](images/content-packs-01.png)

5. <span data-ttu-id="68e1a-136">Настройте пароли для всех пользователей из примера.</span><span class="sxs-lookup"><span data-stu-id="68e1a-136">Configure your passwords for all sample users.</span></span> <span data-ttu-id="68e1a-137">Для удобства администрирования всех вымышленных пользователей потребуется задать один общий пароль.</span><span class="sxs-lookup"><span data-stu-id="68e1a-137">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![Снимок экрана: диалоговое окно добавления общего пароля для пользователей](images/content-packs-02.png)

6. <span data-ttu-id="68e1a-139">Будет выполнена установка данных,</span><span class="sxs-lookup"><span data-stu-id="68e1a-139">The data will be installed.</span></span> <span data-ttu-id="68e1a-140">занимающая около 5 минут.</span><span class="sxs-lookup"><span data-stu-id="68e1a-140">The installation should take about 5 minutes.</span></span>

![Снимок экрана: процесс установки на плитке информационной панели](images/content-packs-03.PNG)

7. <span data-ttu-id="68e1a-142">После завершения установки вы получите уведомление по электронной почте, а поле на плитке подписки станет зеленым.</span><span class="sxs-lookup"><span data-stu-id="68e1a-142">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="68e1a-143">Теперь вы можете установить пример пакета данных "Почта и события".</span><span class="sxs-lookup"><span data-stu-id="68e1a-143">You can now install the Mail and Events sample data pack.</span></span>

![Снимок экрана: плитка информационной панели с готовым к установке пакетом "Почта и события"](images/content-packs-04.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="68e1a-145">Как установить пример пакета данных "Почта и события"?</span><span class="sxs-lookup"><span data-stu-id="68e1a-145">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="68e1a-146">После установки примера пакета данных "Пользователи" можно установить пакет данных "Почта и события".</span><span class="sxs-lookup"><span data-stu-id="68e1a-146">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="68e1a-147">На плитке подписки выберите поле **Почта и события**.</span><span class="sxs-lookup"><span data-stu-id="68e1a-147">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="68e1a-148">Нажмите кнопку **Установить**, чтобы начать установку.</span><span class="sxs-lookup"><span data-stu-id="68e1a-148">Select **Install** to begin installation.</span></span>

![Снимок экрана: диалоговое окно установки](images/content-packs-05.png)

> [!NOTE]
> <span data-ttu-id="68e1a-150">Если вы только что создали свою подписку, ее требуется полностью подготовить перед началом установки.</span><span class="sxs-lookup"><span data-stu-id="68e1a-150">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="68e1a-151">Это может занять несколько часов.</span><span class="sxs-lookup"><span data-stu-id="68e1a-151">This can take up to a few hours.</span></span> <span data-ttu-id="68e1a-152">После запуска установка может занять до 20 минут.</span><span class="sxs-lookup"><span data-stu-id="68e1a-152">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="68e1a-153">После завершения установки вы получите уведомление по электронной почте, а поле на плитке подписки станет зеленым.</span><span class="sxs-lookup"><span data-stu-id="68e1a-153">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="68e1a-154">Ожидаются ли дополнительные примеры пакетов данных?</span><span class="sxs-lookup"><span data-stu-id="68e1a-154">Are more sample data packs coming?</span></span>

<span data-ttu-id="68e1a-155">Да.</span><span class="sxs-lookup"><span data-stu-id="68e1a-155">Yes.</span></span> <span data-ttu-id="68e1a-156">Мы добавим примеры пакетов данных для SharePoint и OneDrive.</span><span class="sxs-lookup"><span data-stu-id="68e1a-156">We will add sample data packs for SharePoint and OneDrive.</span></span> <span data-ttu-id="68e1a-157">В дальнейшем мы предполагаем добавить примеры пакетов данных для других продуктов и технологий, включая надстройки Office, Microsoft Teams и т. д.</span><span class="sxs-lookup"><span data-stu-id="68e1a-157">In the future, we will consider adding sample data packs for more products and technologies, including Office Add-ins, Microsoft Teams, and more.</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-office-365-subscriptions"></a><span data-ttu-id="68e1a-158">Можно ли установить примеры пакетов данных в другие подписки на Office 365?</span><span class="sxs-lookup"><span data-stu-id="68e1a-158">Can I install sample data packs on my other Office 365 subscriptions?</span></span>

<span data-ttu-id="68e1a-159">Нет.</span><span class="sxs-lookup"><span data-stu-id="68e1a-159">No.</span></span> <span data-ttu-id="68e1a-160">Эти примеры пакетов данных совместимы только с подпиской разработчика на Office 365, предоставляемой в рамках программы для разработчиков Office 365.</span><span class="sxs-lookup"><span data-stu-id="68e1a-160">These sample data packs are only compatible with the Office 365 Developer Subscription you get as part of the Office 365 Developer Program.</span></span>

## <a name="see-also"></a><span data-ttu-id="68e1a-161">См. также</span><span class="sxs-lookup"><span data-stu-id="68e1a-161">See also</span></span>

- [<span data-ttu-id="68e1a-162">Настройка подписки разработчика Office 365</span><span class="sxs-lookup"><span data-stu-id="68e1a-162">Set up an Office 365 developer subscription</span></span>](office-365-developer-program-get-started.md)
