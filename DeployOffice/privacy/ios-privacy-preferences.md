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
ms.openlocfilehash: ac8b3428734649981f20a82be2f0793c857e09ee
ms.sourcegitcommit: 81295dff0f2fa474f0db39fd40560e3a23fff32a
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 07/09/2020
ms.locfileid: "45092176"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="68a75-103">Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS</span><span class="sxs-lookup"><span data-stu-id="68a75-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="68a75-104">Sẽ có các cài đặt tùy chọn mới cho Office trên thiết bị iOS cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="68a75-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="68a75-105">***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.</span><span class="sxs-lookup"><span data-stu-id="68a75-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="68a75-106">***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="68a75-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="68a75-107">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="68a75-108">Các cài đặt tùy chọn này sẽ áp dụng cho các ứng dụng sau đây:</span><span class="sxs-lookup"><span data-stu-id="68a75-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="68a75-109">Phiên bản 2.30 trở lên trong Word for iOS, Excel for iOS và PowerPoint for iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="68a75-110">Phiên bản 4.30.0 trở lên trong Outlook for iOS</span><span class="sxs-lookup"><span data-stu-id="68a75-110">Version 4.30.0 and later of Outlook for iOS</span></span>
- <span data-ttu-id="68a75-111">Phiên bản 16.30 trở lên trong OneNote for iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-111">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="68a75-112">Phiên bản 11.19.11 trở lên trong OneDrive for iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-112">Version 11.19.11 and later of OneDrive for iOS.</span></span>
- <span data-ttu-id="68a75-113">Phiên bản 1.17 trở lên của Visio Viewer for iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-113">Version 1.17 and later of Visio Viewer for iOS.</span></span>
- <span data-ttu-id="68a75-114">Phiên bản 2.34 trở lên của ứng dụng Office dành cho iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-114">Version 2.34 and later of the Office app for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="68a75-115">Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên các máy tính chạy macOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office for Mac](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-115">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="68a75-116">Cài đặt tùy chọn thiết bị</span><span class="sxs-lookup"><span data-stu-id="68a75-116">Setting device preferences</span></span>
<span data-ttu-id="68a75-117">Các cài đặt tùy chọn mới cũng có thể được đặt ở cấp thiết bị bằng một máy chủ Quản lý Thiết bị Di động (MDM) khi cài đặt ứng dụng Office.</span><span class="sxs-lookup"><span data-stu-id="68a75-117">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="68a75-118">Nhiều máy chủ MDM cho phép người quản trị CNTT thêm một từ điển cấu hình tùy chọn khi máy chủ gửi lệnh MDM `InstallApplication` đến một thiết bị chạy iOS.</span><span class="sxs-lookup"><span data-stu-id="68a75-118">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="68a75-119">Hãy tham khảo tài liệu hướng dẫn máy chủ MDM của bạn để biết thêm chi tiết.</span><span class="sxs-lookup"><span data-stu-id="68a75-119">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="68a75-120">Từ điển được thể hiện dưới dạng một tập hợp các cặp khóa/giá trị theo định dạng XML.</span><span class="sxs-lookup"><span data-stu-id="68a75-120">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="68a75-121">Ví dụ:</span><span class="sxs-lookup"><span data-stu-id="68a75-121">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="68a75-122">Sau khi được gửi tới thiết bị, từ điển cấu hình sẽ nằm bên dưới phím `com.apple.managed.configuration`, nơi nó sẽ được đọc khi ứng dụng Office được khởi chạy.</span><span class="sxs-lookup"><span data-stu-id="68a75-122">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="68a75-123">Bạn cũng có thể sử dụng dịch vụ chính sách đám mây Office và 4 thiết đặt chính sách này:</span><span class="sxs-lookup"><span data-stu-id="68a75-123">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="68a75-124">Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft</span><span class="sxs-lookup"><span data-stu-id="68a75-124">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="68a75-125">Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office</span><span class="sxs-lookup"><span data-stu-id="68a75-125">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="68a75-126">Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office</span><span class="sxs-lookup"><span data-stu-id="68a75-126">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="68a75-127">Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office</span><span class="sxs-lookup"><span data-stu-id="68a75-127">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="68a75-128">Cài đặt quyền riêng tư cho Outlook for iOS và OneDrive for iOS chỉ có thể được cấu hình bằng cách sử dụng dịch vụ chính sách điện toán đám mây của Office.</span><span class="sxs-lookup"><span data-stu-id="68a75-128">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="68a75-129">Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-129">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="68a75-130">Cài đặt tùy chọn dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="68a75-130">Preference setting for diagnostic data</span></span>

<span data-ttu-id="68a75-131">Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.</span><span class="sxs-lookup"><span data-stu-id="68a75-131">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="68a75-132">Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="68a75-132">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="68a75-133">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="68a75-133">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="68a75-134">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="68a75-134">**Data Type**</span></span>  | <span data-ttu-id="68a75-135">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="68a75-135">String</span></span> |
|<span data-ttu-id="68a75-136">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="68a75-136">**Possible values**</span></span>  | <span data-ttu-id="68a75-137">`BasicDiagnosticData` *(đặt ở mức Bắt buộc)*</span><span class="sxs-lookup"><span data-stu-id="68a75-137">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="68a75-138">`FullDiagnosticData` *(đặt ở mức Tùy chọn)*</span><span class="sxs-lookup"><span data-stu-id="68a75-138">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="68a75-139">`ZeroDiagnosticData` *(không áp dụng mức nào ở trên)*</span><span class="sxs-lookup"><span data-stu-id="68a75-139">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="68a75-140">Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) đang đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="68a75-140">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="68a75-141">Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.</span><span class="sxs-lookup"><span data-stu-id="68a75-141">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="68a75-142">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục \*\*Cài đặt \*\* > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="68a75-142">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="68a75-143">Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="68a75-143">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="68a75-144">Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự.</span><span class="sxs-lookup"><span data-stu-id="68a75-144">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="68a75-145">Ví dụ: Ý tưởng thiết kế trong PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="68a75-145">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="68a75-146">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-146">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="68a75-147">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="68a75-147">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="68a75-148">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="68a75-148">**Data Type**</span></span>  | <span data-ttu-id="68a75-149">Boolean</span><span class="sxs-lookup"><span data-stu-id="68a75-149">Boolean</span></span> |
|<span data-ttu-id="68a75-150">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="68a75-150">**Possible values**</span></span>  | <span data-ttu-id="68a75-151">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="68a75-151">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="68a75-152">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="68a75-152">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="68a75-153">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng.</span><span class="sxs-lookup"><span data-stu-id="68a75-153">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="68a75-154">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="68a75-154">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="68a75-155">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="68a75-155">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="68a75-156">Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="68a75-156">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="68a75-157">Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các biểu mẫu, hình ảnh, video và tài liệu tham khảo để cải thiện tài liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="68a75-157">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="68a75-158">Ví dụ: các biểu mẫu Office hoặc chèn biểu tượng trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="68a75-158">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="68a75-159">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-159">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="68a75-160">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="68a75-160">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="68a75-161">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="68a75-161">**Data Type**</span></span>  | <span data-ttu-id="68a75-162">Boolean</span><span class="sxs-lookup"><span data-stu-id="68a75-162">Boolean</span></span> |
|<span data-ttu-id="68a75-163">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="68a75-163">**Possible values**</span></span>  | <span data-ttu-id="68a75-164">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="68a75-164">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="68a75-165">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="68a75-165">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="68a75-166">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="68a75-166">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="68a75-167">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm tải xuống nội dung trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="68a75-167">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="68a75-168">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="68a75-168">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="68a75-169">Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn</span><span class="sxs-lookup"><span data-stu-id="68a75-169">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="68a75-170">Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="68a75-170">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="68a75-171">Ví dụ: các phần bổ trợ dành cho Office được tải xuống thông qua Office Store đến thiết bị của bạn.</span><span class="sxs-lookup"><span data-stu-id="68a75-171">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="68a75-172">Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="68a75-172">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="68a75-173">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="68a75-173">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="68a75-174">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="68a75-174">**Data Type**</span></span>  | <span data-ttu-id="68a75-175">Boolean</span><span class="sxs-lookup"><span data-stu-id="68a75-175">Boolean</span></span> |
|<span data-ttu-id="68a75-176">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="68a75-176">**Possible values**</span></span>  | <span data-ttu-id="68a75-177">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="68a75-177">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="68a75-178">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="68a75-178">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="68a75-179">Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đã đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="68a75-179">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="68a75-180">Trừ khi bạn đã đặt tùy chọn này là FALSE, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="68a75-180">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="68a75-181">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.</span><span class="sxs-lookup"><span data-stu-id="68a75-181">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>