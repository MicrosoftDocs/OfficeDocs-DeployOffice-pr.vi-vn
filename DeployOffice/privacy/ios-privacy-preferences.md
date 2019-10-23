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
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604305"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="d9eaf-103">Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS</span><span class="sxs-lookup"><span data-stu-id="d9eaf-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="d9eaf-104">Sẽ có các cài đặt tùy chọn mới cho Office trên thiết bị iOS cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="d9eaf-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="d9eaf-105">***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="d9eaf-106">***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="d9eaf-107">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="d9eaf-108">Các cài đặt tùy chọn này sẽ áp dụng cho các ứng dụng sau đây:</span><span class="sxs-lookup"><span data-stu-id="d9eaf-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="d9eaf-109">Phiên bản 2.30 trở lên trong Word for iOS, Excel for iOS và PowerPoint for iOS.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="d9eaf-110">Phiên bản 16.30 trở lên trong OneNote for iOS.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="d9eaf-111">Phiên bản 1.17 trở lên của Visio Viewer for iOS.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="d9eaf-112">Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên các máy tính chạy macOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office for Mac](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="d9eaf-113">Cài đặt tùy chọn thiết bị</span><span class="sxs-lookup"><span data-stu-id="d9eaf-113">Setting device preferences</span></span>
<span data-ttu-id="d9eaf-114">Các cài đặt tùy chọn mới cũng có thể được đặt ở cấp thiết bị bằng một máy chủ Quản lý Thiết bị Di động (MDM) khi cài đặt ứng dụng Office.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="d9eaf-115">Nhiều máy chủ MDM cho phép người quản trị CNTT thêm một từ điển cấu hình tùy chọn khi máy chủ gửi lệnh MDM `InstallApplication` đến một thiết bị chạy iOS.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="d9eaf-116">Hãy tham khảo tài liệu hướng dẫn máy chủ MDM của bạn để biết thêm chi tiết.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="d9eaf-117">Từ điển được thể hiện dưới dạng một tập hợp các cặp khóa/giá trị theo định dạng XML.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="d9eaf-118">Ví dụ:</span><span class="sxs-lookup"><span data-stu-id="d9eaf-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="d9eaf-119">Sau khi được gửi tới thiết bị, từ điển cấu hình sẽ nằm bên dưới phím `com.apple.managed.configuration`, nơi nó sẽ được đọc khi ứng dụng Office được khởi chạy.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="d9eaf-120">Cài đặt tùy chọn dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="d9eaf-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="d9eaf-121">Dữ liệu chẩn đoán được sử dụng để giúp cho Office được an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="d9eaf-122">Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Office 365 ProPlus tới Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d9eaf-123">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="d9eaf-124">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-124">**Data Type**</span></span>  | <span data-ttu-id="d9eaf-125">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="d9eaf-125">String</span></span> |
|<span data-ttu-id="d9eaf-126">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-126">**Possible values**</span></span>  | <span data-ttu-id="d9eaf-127">`BasicDiagnosticData` *(đặt ở mức Bắt buộc)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="d9eaf-128">`FullDiagnosticData` *(đặt ở mức Tùy chọn)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="d9eaf-129">`ZeroDiagnosticData` *(không áp dụng mức nào ở trên)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="d9eaf-130">Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 đang đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="d9eaf-131">Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="d9eaf-132">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục \*\*Cài đặt \*\* > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="d9eaf-133">Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="d9eaf-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="d9eaf-134">Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="d9eaf-135">Ví dụ: Ý tưởng thiết kế trong PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="d9eaf-136">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d9eaf-137">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="d9eaf-138">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-138">**Data Type**</span></span>  | <span data-ttu-id="d9eaf-139">Boolean</span><span class="sxs-lookup"><span data-stu-id="d9eaf-139">Boolean</span></span> |
|<span data-ttu-id="d9eaf-140">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-140">**Possible values**</span></span>  | <span data-ttu-id="d9eaf-141">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9eaf-142">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9eaf-143">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="d9eaf-144">Nếu người dùng có đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="d9eaf-145">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="d9eaf-146">Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="d9eaf-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="d9eaf-147">Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các biểu mẫu, hình ảnh, video và tài liệu tham khảo để cải thiện tài liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="d9eaf-148">Ví dụ: các biểu mẫu Office hoặc chèn biểu tượng trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="d9eaf-149">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d9eaf-150">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="d9eaf-151">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-151">**Data Type**</span></span>  | <span data-ttu-id="d9eaf-152">Boolean</span><span class="sxs-lookup"><span data-stu-id="d9eaf-152">Boolean</span></span> |
|<span data-ttu-id="d9eaf-153">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-153">**Possible values**</span></span>  | <span data-ttu-id="d9eaf-154">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9eaf-155">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9eaf-156">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="d9eaf-157">Nếu người dùng đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc trường học thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="d9eaf-158">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="d9eaf-159">Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn</span><span class="sxs-lookup"><span data-stu-id="d9eaf-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="d9eaf-160">Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="d9eaf-161">Ví dụ: các phần bổ trợ dành cho Office được tải xuống thông qua Office Store đến thiết bị của bạn.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="d9eaf-162">Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9eaf-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d9eaf-163">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="d9eaf-164">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-164">**Data Type**</span></span>  | <span data-ttu-id="d9eaf-165">Boolean</span><span class="sxs-lookup"><span data-stu-id="d9eaf-165">Boolean</span></span> |
|<span data-ttu-id="d9eaf-166">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="d9eaf-166">**Possible values**</span></span>  | <span data-ttu-id="d9eaf-167">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9eaf-168">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="d9eaf-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9eaf-169">Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 đã đăng nhập bằng tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="d9eaf-170">Trừ khi bạn đã đặt tùy chọn này là FALSE, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="d9eaf-171">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.</span><span class="sxs-lookup"><span data-stu-id="d9eaf-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>