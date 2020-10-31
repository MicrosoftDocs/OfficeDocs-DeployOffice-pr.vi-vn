---
title: Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: Cung cấp cho người quản trị Office thông tin về cách quản lý kiểm soát quyền riêng tư trên thiết bị iOS.
hideEdit: true
ms.openlocfilehash: ed24ac934625bba61eac25e764a892d48365c005
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794679"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="db2fe-103">Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS</span><span class="sxs-lookup"><span data-stu-id="db2fe-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="db2fe-104">Để biết danh sách các sản phẩm Office trong phạm vi thông tin về quyền riêng tư này, hãy xem [Các biện pháp kiểm soát quyền riêng tư có sẵn dành cho các sản phẩm Office](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="db2fe-105">Có các cài đặt tùy chọn mới cho Office trên thiết bị iOS cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="db2fe-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="db2fe-106">\***Dữ liệu chẩn đoán** _ về phần mềm máy khách Office được sử dụng được thu thập và gửi đến Microsoft.</span><span class="sxs-lookup"><span data-stu-id="db2fe-106">\***Diagnostic data** _ that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="db2fe-107">_*_Trải nghiệm được kết nối_*_ sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="db2fe-107">_*_Connected experiences_*_ that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="db2fe-108">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="db2fe-109">Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên các máy tính chạy macOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office for Mac](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="db2fe-110">Cài đặt tùy chọn thiết bị</span><span class="sxs-lookup"><span data-stu-id="db2fe-110">Setting device preferences</span></span>
<span data-ttu-id="db2fe-111">Các cài đặt tùy chọn mới cũng có thể được đặt ở cấp thiết bị bằng một máy chủ Quản lý Thiết bị Di động (MDM) khi cài đặt ứng dụng Office.</span><span class="sxs-lookup"><span data-stu-id="db2fe-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="db2fe-112">Nhiều máy chủ MDM cho phép người quản trị CNTT thêm một từ điển cấu hình tùy chọn khi máy chủ gửi lệnh MDM `InstallApplication` đến một thiết bị chạy iOS.</span><span class="sxs-lookup"><span data-stu-id="db2fe-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="db2fe-113">Hãy tham khảo tài liệu hướng dẫn máy chủ MDM của bạn để biết thêm chi tiết.</span><span class="sxs-lookup"><span data-stu-id="db2fe-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="db2fe-114">Từ điển được thể hiện dưới dạng một tập hợp các cặp khóa/giá trị theo định dạng XML.</span><span class="sxs-lookup"><span data-stu-id="db2fe-114">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="db2fe-115">Ví dụ:</span><span class="sxs-lookup"><span data-stu-id="db2fe-115">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="db2fe-116">Sau khi được gửi tới thiết bị, từ điển cấu hình sẽ nằm bên dưới phím `com.apple.managed.configuration`, nơi nó sẽ được đọc khi ứng dụng Office được khởi chạy.</span><span class="sxs-lookup"><span data-stu-id="db2fe-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="db2fe-117">Bạn cũng có thể sử dụng dịch vụ chính sách đám mây Office và 4 thiết đặt chính sách này:</span><span class="sxs-lookup"><span data-stu-id="db2fe-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="db2fe-118">Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft</span><span class="sxs-lookup"><span data-stu-id="db2fe-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="db2fe-119">Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office</span><span class="sxs-lookup"><span data-stu-id="db2fe-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="db2fe-120">Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office</span><span class="sxs-lookup"><span data-stu-id="db2fe-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="db2fe-121">Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office</span><span class="sxs-lookup"><span data-stu-id="db2fe-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="db2fe-122">Cài đặt quyền riêng tư cho Outlook for iOS và OneDrive for iOS chỉ có thể được cấu hình bằng cách sử dụng dịch vụ chính sách điện toán đám mây của Office.</span><span class="sxs-lookup"><span data-stu-id="db2fe-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="db2fe-123">Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="db2fe-124">Cài đặt tùy chọn dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="db2fe-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="db2fe-125">Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.</span><span class="sxs-lookup"><span data-stu-id="db2fe-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="db2fe-126">Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="db2fe-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="db2fe-127">_ *Khóa*\*</span><span class="sxs-lookup"><span data-stu-id="db2fe-127">_ *Key*\*</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="db2fe-128">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="db2fe-128">**Data Type**</span></span>  | <span data-ttu-id="db2fe-129">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="db2fe-129">String</span></span> |
|<span data-ttu-id="db2fe-130">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="db2fe-130">**Possible values**</span></span>  | <span data-ttu-id="db2fe-131">`BasicDiagnosticData` *(đặt ở mức Bắt buộc)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-131">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="db2fe-132">`FullDiagnosticData` *(đặt ở mức Tùy chọn)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-132">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="db2fe-133">`ZeroDiagnosticData` *(không áp dụng mức nào ở trên)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-133">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="db2fe-134">Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) đang đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="db2fe-134">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="db2fe-135">Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.</span><span class="sxs-lookup"><span data-stu-id="db2fe-135">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="db2fe-136">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục **Cài đặt** > **Cài đặt Quyền riêng tư** .</span><span class="sxs-lookup"><span data-stu-id="db2fe-136">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings** .</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="db2fe-137">Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="db2fe-137">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="db2fe-138">Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự.</span><span class="sxs-lookup"><span data-stu-id="db2fe-138">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="db2fe-139">Ví dụ: Ý tưởng thiết kế trong PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="db2fe-139">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="db2fe-140">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-140">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="db2fe-141">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="db2fe-141">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="db2fe-142">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="db2fe-142">**Data Type**</span></span>  | <span data-ttu-id="db2fe-143">Boolean</span><span class="sxs-lookup"><span data-stu-id="db2fe-143">Boolean</span></span> |
|<span data-ttu-id="db2fe-144">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="db2fe-144">**Possible values**</span></span>  | <span data-ttu-id="db2fe-145">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-145">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="db2fe-146">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-146">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="db2fe-147">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng.</span><span class="sxs-lookup"><span data-stu-id="db2fe-147">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="db2fe-148">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="db2fe-148">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="db2fe-149">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư** .</span><span class="sxs-lookup"><span data-stu-id="db2fe-149">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="db2fe-150">Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="db2fe-150">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="db2fe-151">Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các biểu mẫu, hình ảnh, video và tài liệu tham khảo để cải thiện tài liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="db2fe-151">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="db2fe-152">Ví dụ: các biểu mẫu Office hoặc chèn biểu tượng trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="db2fe-152">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="db2fe-153">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-153">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="db2fe-154">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="db2fe-154">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="db2fe-155">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="db2fe-155">**Data Type**</span></span>  | <span data-ttu-id="db2fe-156">Boolean</span><span class="sxs-lookup"><span data-stu-id="db2fe-156">Boolean</span></span> |
|<span data-ttu-id="db2fe-157">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="db2fe-157">**Possible values**</span></span>  | <span data-ttu-id="db2fe-158">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-158">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="db2fe-159">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-159">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="db2fe-160">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="db2fe-160">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="db2fe-161">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm tải xuống nội dung trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="db2fe-161">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="db2fe-162">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư** .</span><span class="sxs-lookup"><span data-stu-id="db2fe-162">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="db2fe-163">Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn</span><span class="sxs-lookup"><span data-stu-id="db2fe-163">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="db2fe-164">Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="db2fe-164">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="db2fe-165">Ví dụ: các phần bổ trợ dành cho Office được tải xuống thông qua Office Store đến thiết bị của bạn.</span><span class="sxs-lookup"><span data-stu-id="db2fe-165">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="db2fe-166">Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="db2fe-166">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="db2fe-167">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="db2fe-167">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="db2fe-168">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="db2fe-168">**Data Type**</span></span>  | <span data-ttu-id="db2fe-169">Boolean</span><span class="sxs-lookup"><span data-stu-id="db2fe-169">Boolean</span></span> |
|<span data-ttu-id="db2fe-170">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="db2fe-170">**Possible values**</span></span>  | <span data-ttu-id="db2fe-171">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-171">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="db2fe-172">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="db2fe-172">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="db2fe-173">Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đã đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="db2fe-173">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="db2fe-174">Trừ khi bạn đã đặt tùy chọn này là FALSE, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư** .</span><span class="sxs-lookup"><span data-stu-id="db2fe-174">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings** .</span></span>

<span data-ttu-id="db2fe-175">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.</span><span class="sxs-lookup"><span data-stu-id="db2fe-175">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>