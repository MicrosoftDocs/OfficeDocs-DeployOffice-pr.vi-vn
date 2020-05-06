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
ms.openlocfilehash: 40fc1ec1f5b2abc587e1b5224dc7fe0a5a656f33
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/01/2020
ms.locfileid: "43992128"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="5e731-103">Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS</span><span class="sxs-lookup"><span data-stu-id="5e731-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="5e731-104">Sẽ có các cài đặt tùy chọn mới cho Office trên thiết bị iOS cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="5e731-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="5e731-105">***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5e731-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="5e731-106">***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="5e731-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="5e731-107">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="5e731-108">Các cài đặt tùy chọn này sẽ áp dụng cho các ứng dụng sau đây:</span><span class="sxs-lookup"><span data-stu-id="5e731-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="5e731-109">Phiên bản 2.30 trở lên trong Word for iOS, Excel for iOS và PowerPoint for iOS.</span><span class="sxs-lookup"><span data-stu-id="5e731-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="5e731-110">Phiên bản 16.30 trở lên trong OneNote for iOS.</span><span class="sxs-lookup"><span data-stu-id="5e731-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="5e731-111">Phiên bản 1.17 trở lên của Visio Viewer for iOS.</span><span class="sxs-lookup"><span data-stu-id="5e731-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="5e731-112">Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên các máy tính chạy macOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office for Mac](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-112">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="5e731-113">Cài đặt tùy chọn thiết bị</span><span class="sxs-lookup"><span data-stu-id="5e731-113">Setting device preferences</span></span>
<span data-ttu-id="5e731-114">Các cài đặt tùy chọn mới cũng có thể được đặt ở cấp thiết bị bằng một máy chủ Quản lý Thiết bị Di động (MDM) khi cài đặt ứng dụng Office.</span><span class="sxs-lookup"><span data-stu-id="5e731-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="5e731-115">Nhiều máy chủ MDM cho phép người quản trị CNTT thêm một từ điển cấu hình tùy chọn khi máy chủ gửi lệnh MDM `InstallApplication` đến một thiết bị chạy iOS.</span><span class="sxs-lookup"><span data-stu-id="5e731-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="5e731-116">Hãy tham khảo tài liệu hướng dẫn máy chủ MDM của bạn để biết thêm chi tiết.</span><span class="sxs-lookup"><span data-stu-id="5e731-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="5e731-117">Từ điển được thể hiện dưới dạng một tập hợp các cặp khóa/giá trị theo định dạng XML.</span><span class="sxs-lookup"><span data-stu-id="5e731-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="5e731-118">Ví dụ:</span><span class="sxs-lookup"><span data-stu-id="5e731-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="5e731-119">Sau khi được gửi tới thiết bị, từ điển cấu hình sẽ nằm bên dưới phím `com.apple.managed.configuration`, nơi nó sẽ được đọc khi ứng dụng Office được khởi chạy.</span><span class="sxs-lookup"><span data-stu-id="5e731-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="5e731-120">Bạn cũng có thể sử dụng dịch vụ chính sách đám mây Office và 4 thiết đặt chính sách này:</span><span class="sxs-lookup"><span data-stu-id="5e731-120">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="5e731-121">Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft</span><span class="sxs-lookup"><span data-stu-id="5e731-121">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="5e731-122">Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office</span><span class="sxs-lookup"><span data-stu-id="5e731-122">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="5e731-123">Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office</span><span class="sxs-lookup"><span data-stu-id="5e731-123">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="5e731-124">Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office</span><span class="sxs-lookup"><span data-stu-id="5e731-124">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="5e731-125">Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-125">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="5e731-126">Cài đặt tùy chọn dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="5e731-126">Preference setting for diagnostic data</span></span>

<span data-ttu-id="5e731-127">Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.</span><span class="sxs-lookup"><span data-stu-id="5e731-127">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="5e731-128">Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="5e731-128">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5e731-129">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="5e731-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="5e731-130">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="5e731-130">**Data Type**</span></span>  | <span data-ttu-id="5e731-131">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="5e731-131">String</span></span> |
|<span data-ttu-id="5e731-132">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="5e731-132">**Possible values**</span></span>  | <span data-ttu-id="5e731-133">`BasicDiagnosticData` *(đặt ở mức Bắt buộc)*</span><span class="sxs-lookup"><span data-stu-id="5e731-133">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="5e731-134">`FullDiagnosticData` *(đặt ở mức Tùy chọn)*</span><span class="sxs-lookup"><span data-stu-id="5e731-134">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="5e731-135">`ZeroDiagnosticData` *(không áp dụng mức nào ở trên)*</span><span class="sxs-lookup"><span data-stu-id="5e731-135">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="5e731-136">Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) đang đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="5e731-136">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="5e731-137">Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.</span><span class="sxs-lookup"><span data-stu-id="5e731-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="5e731-138">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục \*\*Cài đặt \*\* > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="5e731-138">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="5e731-139">Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="5e731-139">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="5e731-140">Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự.</span><span class="sxs-lookup"><span data-stu-id="5e731-140">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="5e731-141">Ví dụ: Ý tưởng thiết kế trong PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="5e731-141">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="5e731-142">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-142">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5e731-143">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="5e731-143">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="5e731-144">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="5e731-144">**Data Type**</span></span>  | <span data-ttu-id="5e731-145">Boolean</span><span class="sxs-lookup"><span data-stu-id="5e731-145">Boolean</span></span> |
|<span data-ttu-id="5e731-146">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="5e731-146">**Possible values**</span></span>  | <span data-ttu-id="5e731-147">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="5e731-147">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="5e731-148">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="5e731-148">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="5e731-149">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng.</span><span class="sxs-lookup"><span data-stu-id="5e731-149">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="5e731-150">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="5e731-150">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="5e731-151">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="5e731-151">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="5e731-152">Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="5e731-152">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="5e731-153">Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các biểu mẫu, hình ảnh, video và tài liệu tham khảo để cải thiện tài liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="5e731-153">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="5e731-154">Ví dụ: các biểu mẫu Office hoặc chèn biểu tượng trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="5e731-154">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="5e731-155">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-155">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5e731-156">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="5e731-156">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="5e731-157">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="5e731-157">**Data Type**</span></span>  | <span data-ttu-id="5e731-158">Boolean</span><span class="sxs-lookup"><span data-stu-id="5e731-158">Boolean</span></span> |
|<span data-ttu-id="5e731-159">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="5e731-159">**Possible values**</span></span>  | <span data-ttu-id="5e731-160">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="5e731-160">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="5e731-161">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="5e731-161">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="5e731-162">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="5e731-162">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="5e731-163">Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm tải xuống nội dung trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="5e731-163">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="5e731-164">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="5e731-164">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="5e731-165">Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn</span><span class="sxs-lookup"><span data-stu-id="5e731-165">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="5e731-166">Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="5e731-166">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="5e731-167">Ví dụ: các phần bổ trợ dành cho Office được tải xuống thông qua Office Store đến thiết bị của bạn.</span><span class="sxs-lookup"><span data-stu-id="5e731-167">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="5e731-168">Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="5e731-168">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5e731-169">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="5e731-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="5e731-170">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="5e731-170">**Data Type**</span></span>  | <span data-ttu-id="5e731-171">Boolean</span><span class="sxs-lookup"><span data-stu-id="5e731-171">Boolean</span></span> |
|<span data-ttu-id="5e731-172">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="5e731-172">**Possible values**</span></span>  | <span data-ttu-id="5e731-173">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="5e731-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="5e731-174">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="5e731-174">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="5e731-175">Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đã đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="5e731-175">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="5e731-176">Trừ khi bạn đã đặt tùy chọn này là FALSE, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="5e731-176">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="5e731-177">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.</span><span class="sxs-lookup"><span data-stu-id="5e731-177">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>