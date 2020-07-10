---
title: Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office thông tin về cách quản lý kiểm soát quyền riêng tư cho Office trên thiết bị Android.
hideEdit: true
ms.openlocfilehash: 38d68df0d3a12e6858568906a60973bad9d76709
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087905"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a><span data-ttu-id="b1d58-103">Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android</span><span class="sxs-lookup"><span data-stu-id="b1d58-103">Use policy settings to manage privacy controls for Office on Android devices</span></span>

<span data-ttu-id="b1d58-104">Sẽ có các thiết đặt chính sách mới cho Office trên thiết bị Android cho phép bạn kiểm soát các thiết đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="b1d58-104">There are policy settings for Office on Android devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="b1d58-105">***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.</span><span class="sxs-lookup"><span data-stu-id="b1d58-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="b1d58-106">***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="b1d58-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="b1d58-107">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="b1d58-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="b1d58-108">Các thiết đặt chính sách này sẽ áp dụng cho các ứng dụng sau đây:</span><span class="sxs-lookup"><span data-stu-id="b1d58-108">These policy settings apply to the following applications:</span></span>
- <span data-ttu-id="b1d58-109">Phiên bản 16.0.12228.20260 trở lên trong Word for Android, Excel for Android và PowerPoint for Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-109">Version 16.0.12228.20260 and later of Word for Android, Excel for Android, and PowerPoint for Android.</span></span>
- <span data-ttu-id="b1d58-110">Phiên bản 4.1.71 trở lên trong Outlook for Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-110">Version 4.1.71 and later of Outlook for Android.</span></span>
- <span data-ttu-id="b1d58-111">Phiên bản 16.0.12228.20004 trở lên trong OneNote for Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-111">Version 16.0.12228.20004 and later of OneNote for Android.</span></span>
- <span data-ttu-id="b1d58-112">Phiên bản 5.47 trở lên trong OneDrive for Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-112">Version 5.47 and later of OneDrive for Android.</span></span>

> [!NOTE]
>- <span data-ttu-id="b1d58-113">Các thiết đặt chính sách này cũng áp dụng cho phiên bản 16.0.12130.20272 trở lên của bản xem trước công khai của [ứng dụng Office dành cho thiết bị di động](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-113">These policy settings also apply to Version 16.0.12130.20272 and later of the public preview of the [Office Mobile app](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) for Android.</span></span>
>- <span data-ttu-id="b1d58-114">Việc sử dụng bản xem trước công khai của ứng dụng Office dành cho thiết bị di động Android sẽ thu thập các nhật ký sự cố có thể có trong một số trường hợp chứa nội dung.</span><span class="sxs-lookup"><span data-stu-id="b1d58-114">Use of the public preview of the Office Mobile app for Android will collect crash logs which may in some circumstances contain content.</span></span>
>- <span data-ttu-id="b1d58-115">Nếu bạn quan tâm đến việc thu thập dữ liệu từ bản xem trước công khai của ứng dụng Office dành cho thiết bị di động Android, bạn nên thông báo cho người dùng của mình không đăng nhập vào ứng dụng bằng tài khoản cơ quan hoặc trường học của họ.</span><span class="sxs-lookup"><span data-stu-id="b1d58-115">If you're concerned about the collection of data from the public preview of the Office Mobile app for Android, you should inform your users not to log into the application with their work or school accounts.</span></span>

## <a name="policy-settings-available-for-office-on-android-devices"></a><span data-ttu-id="b1d58-116">Các thiết đặt chính sách sẵn dùng cho Office trên các thiết bị chạy Android</span><span class="sxs-lookup"><span data-stu-id="b1d58-116">Policy settings available for Office on Android devices</span></span>

<span data-ttu-id="b1d58-117">Bảng sau liệt kê các thiết đặt chính sách nào sẵn dùng cho Office trên thiết bị Android và liên kết đến thông tin bổ sung về từng thiết đặt chính sách.</span><span class="sxs-lookup"><span data-stu-id="b1d58-117">The following table lists which policy settings are available for Office on Android devices and a link to additional information about each policy setting.</span></span>

> [!NOTE]
>- <span data-ttu-id="b1d58-118">Thông tin bổ sung được cung cấp bao gồm các thiết đặt chính sách đối với Office trên các thiết bị chạy Windows.</span><span class="sxs-lookup"><span data-stu-id="b1d58-118">The additional information provided covers the policy settings for Office on devices running Windows.</span></span> <span data-ttu-id="b1d58-119">Nhưng thông tin tương tự sẽ áp dụng cho Office trên các thiết bị chạy Android vì chúng là các thiết đặt chính sách tương tự.</span><span class="sxs-lookup"><span data-stu-id="b1d58-119">But the same information applies to Office on Android devices because they are the same policy settings.</span></span>
>- <span data-ttu-id="b1d58-120">\* cho phép sử dụng các trải nghiệm được kết nối trong thiết đặt chính sách Office\* sẵn dùng cho Office trên các thiết bị chạy Windows không áp dụng cho Office trên thiết bị Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-120">The *Allow the use of connected experiences in Office* policy setting that's available for Office on devices running Windows does not apply to Office on Android devices.</span></span> 


|<span data-ttu-id="b1d58-121">Tên của thiết đặt chính sách</span><span class="sxs-lookup"><span data-stu-id="b1d58-121">Name of policy setting</span></span>  |<span data-ttu-id="b1d58-122">Thông tin bổ sung</span><span class="sxs-lookup"><span data-stu-id="b1d58-122">Additional information</span></span> |
|---------|---------|
|<span data-ttu-id="b1d58-123">Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft</span><span class="sxs-lookup"><span data-stu-id="b1d58-123">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>|[<span data-ttu-id="b1d58-124">Thiết đặt chính sách dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="b1d58-124">Policy setting for diagnostic data</span></span>](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|<span data-ttu-id="b1d58-125">Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office</span><span class="sxs-lookup"><span data-stu-id="b1d58-125">Allow the use of connected experiences in Office that analyze content</span></span>| [<span data-ttu-id="b1d58-126">Thiết đặt chính sách cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="b1d58-126">Policy setting for connected experiences that analyze your content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|<span data-ttu-id="b1d58-127">Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office</span><span class="sxs-lookup"><span data-stu-id="b1d58-127">Allow the use of connected experiences in Office that download online content</span></span> |[<span data-ttu-id="b1d58-128">Thiết đặt chính sách cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="b1d58-128">Policy setting for connected experiences that download online content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|<span data-ttu-id="b1d58-129">Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office</span><span class="sxs-lookup"><span data-stu-id="b1d58-129">Allow the use of additional optional connected experiences in Office</span></span> |[<span data-ttu-id="b1d58-130">Thiết đặt chính sách cho các trải nghiệm được kết nối tuỳ chọn</span><span class="sxs-lookup"><span data-stu-id="b1d58-130">Policy setting for optional connected experiences</span></span>](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a><span data-ttu-id="b1d58-131">Sử dụng dịch vụ chính sách đám mây của Office để áp dụng các thiết đặt chính sách</span><span class="sxs-lookup"><span data-stu-id="b1d58-131">Use Office cloud policy service to apply policy settings</span></span>

<span data-ttu-id="b1d58-132">Để áp dụng bất kỳ thiết đặt chính sách nào trong số 4 thiết đặt này cho Office trên thiết bị Android, bạn cần sử dụng dịch vụ chính sách đám mây của Office.</span><span class="sxs-lookup"><span data-stu-id="b1d58-132">To apply any of these 4 policy settings for Office on Android devices, you need to use the Office cloud policy service.</span></span> <span data-ttu-id="b1d58-133">Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây của Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây của Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="b1d58-133">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

> [!NOTE]
> <span data-ttu-id="b1d58-134">Nếu trước đây bạn đã sử dụng dịch vụ chính sách đám mây của Office để đặt cấu hình các thiết đặt chính sách này cho Office trên các thiết bị chạy Windows, thì các thiết đặt tương tự đó sẽ áp dụng cho Office trên thiết bị Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-134">If you previously used Office cloud policy service to configure these policy settings for Office on devices running Windows, those same settings will apply to Office on Android devices.</span></span> <span data-ttu-id="b1d58-135">Để điều đó xảy ra, bạn chỉ cần đăng nhập vào dịch vụ chính sách đám mây của Office và dịch vụ sẽ tự động áp dụng các thiết đặt cho Office trên thiết bị Android.</span><span class="sxs-lookup"><span data-stu-id="b1d58-135">For that to happen, you just need to sign in to the Office cloud policy service and the service will apply the settings automatically to Office on Android devices.</span></span>
