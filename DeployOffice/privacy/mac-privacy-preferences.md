---
title: Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office for Mac
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
description: Cung cấp thông tin cho người quản trị Office về cách sử dụng các tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office for Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246336"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="1e36d-103">Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office for Mac</span><span class="sxs-lookup"><span data-stu-id="1e36d-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="1e36d-104">Từ Phiên bản 16.28 của Office for Mac trở đi, sẽ có các cài đặt tùy chọn mới cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:</span><span class="sxs-lookup"><span data-stu-id="1e36d-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="1e36d-105">***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.</span><span class="sxs-lookup"><span data-stu-id="1e36d-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="1e36d-106">***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="1e36d-107">Ngoài ra, còn có một cài đặt tùy chọn mới liên quan đến hộp thoại \*\* Thông báo dữ liệu bắt buộc\*\* cho Microsoft AutoUpdate (MAU).</span><span class="sxs-lookup"><span data-stu-id="1e36d-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="1e36d-108">Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="1e36d-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="1e36d-109">Để biết thông tin về các cài đặt tương tự đối với Office trên máy tính chạy Windows, hãy xem mục [ Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="1e36d-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="1e36d-110">Tùy chọn cài đặt</span><span class="sxs-lookup"><span data-stu-id="1e36d-110">Setting preferences</span></span>

<span data-ttu-id="1e36d-111">Các tùy chọn cài đặt mới này tương thích với CFPreferences API và có thể được đặt bằng cách sử dụng lệnh `defaults` trong Thiết bị đầu cuối hoặc được áp dụng thông qua một Hồ sơ Cấu hình hoặc máy chủ Quản lý thiết bị di động (MDM).</span><span class="sxs-lookup"><span data-stu-id="1e36d-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="1e36d-112">Khi tùy chọn đã được áp dụng thì người dùng không thể thay đổi các giá trị và mọi biện pháp kiểm soát trong ứng dụng sẽ bị vô hiệu hóa.</span><span class="sxs-lookup"><span data-stu-id="1e36d-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="1e36d-113">Cài đặt tùy chọn dành cho dữ liệu chẩn đoán</span><span class="sxs-lookup"><span data-stu-id="1e36d-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="1e36d-114">Dữ liệu chẩn đoán được sử dụng để giúp cho Office được an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.</span><span class="sxs-lookup"><span data-stu-id="1e36d-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="1e36d-115">Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Office 365 ProPlus tới Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="1e36d-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-116">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="1e36d-117">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="1e36d-118">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-118">**Data Type**</span></span>  | <span data-ttu-id="1e36d-119">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="1e36d-119">String</span></span> |
|<span data-ttu-id="1e36d-120">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-120">**Possible values**</span></span>  | <span data-ttu-id="1e36d-121">`BasicDiagnosticData` *(đặt ở mức Bắt buộc)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="1e36d-122">`FullDiagnosticData` *(đặt ở mức Tùy chọn)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="1e36d-123">`ZeroDiagnosticData` *(không áp dụng mức nào ở trên)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="1e36d-124">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-124">**Availability**</span></span> |<span data-ttu-id="1e36d-125">16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="1e36d-126">Nếu bạn đặt tùy chọn này, tùy chọn này cũng sẽ áp dụng cho các sản phẩm sau đây:</span><span class="sxs-lookup"><span data-stu-id="1e36d-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="1e36d-127">Teams for Mac phiên bản 1.00.217856 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="1e36d-128">Skype for Business for Mac phiên bản 16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="1e36d-129">Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 đang đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 for Mac được cấp phép số lượng lớn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="1e36d-130">Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.</span><span class="sxs-lookup"><span data-stu-id="1e36d-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="1e36d-131">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 thì chỉ có dữ liệu chẩn đoán bắt buộc mới được gửi đi, trừ khi người dùng cũng chọn gửi cả dữ liệu chẩn đoán tùy chọn bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="1e36d-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="1e36d-132">Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="1e36d-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="1e36d-133">Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự.</span><span class="sxs-lookup"><span data-stu-id="1e36d-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="1e36d-134">Ví dụ: PowerPoint Designer hoặc Trình nghiên cứu trong Word.</span><span class="sxs-lookup"><span data-stu-id="1e36d-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="1e36d-135">Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="1e36d-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-136">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="1e36d-137">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="1e36d-138">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-138">**Data Type**</span></span>  | <span data-ttu-id="1e36d-139">Boolean</span><span class="sxs-lookup"><span data-stu-id="1e36d-139">Boolean</span></span> |
|<span data-ttu-id="1e36d-140">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-140">**Possible values**</span></span>  | <span data-ttu-id="1e36d-141">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="1e36d-142">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="1e36d-143">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-143">**Availability**</span></span> |<span data-ttu-id="1e36d-144">16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-144">16.28 and later</span></span> |

<span data-ttu-id="1e36d-145">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="1e36d-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="1e36d-146">Nếu người dùng có đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.</span><span class="sxs-lookup"><span data-stu-id="1e36d-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="1e36d-147">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="1e36d-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="1e36d-148">Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="1e36d-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="1e36d-149">Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các mẫu, hình ảnh, mô hình 3D, video và tài liệu tham khảo để cải thiện tài liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="1e36d-150">Ví dụ: mẫu Office hoặc Trình Bắt đầu Nhanh PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1e36d-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="1e36d-151">Để biết danh sách về các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="1e36d-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-152">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="1e36d-153">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="1e36d-154">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-154">**Data Type**</span></span>  | <span data-ttu-id="1e36d-155">Boolean</span><span class="sxs-lookup"><span data-stu-id="1e36d-155">Boolean</span></span> |
|<span data-ttu-id="1e36d-156">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-156">**Possible values**</span></span>  | <span data-ttu-id="1e36d-157">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="1e36d-158">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="1e36d-159">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-159">**Availability**</span></span> |<span data-ttu-id="1e36d-160">16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-160">16.28 and later</span></span> |

<span data-ttu-id="1e36d-161">Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="1e36d-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="1e36d-162">Nếu người dùng có đăng ký Office 365 và đã đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối tải xuống nội dung trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="1e36d-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="1e36d-163">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="1e36d-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="1e36d-164">Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn</span><span class="sxs-lookup"><span data-stu-id="1e36d-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="1e36d-165">Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học.</span><span class="sxs-lookup"><span data-stu-id="1e36d-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="1e36d-166">Ví dụ: các tính năng LinkedIn của Trợ lý Sơ yếu lý lịch trong Word hoặc Thanh Thời tiết trong Outlook sử dụng Thời tiết trên MSN.</span><span class="sxs-lookup"><span data-stu-id="1e36d-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="1e36d-167">Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="1e36d-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-168">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="1e36d-169">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="1e36d-170">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-170">**Data Type**</span></span>  | <span data-ttu-id="1e36d-171">Boolean</span><span class="sxs-lookup"><span data-stu-id="1e36d-171">Boolean</span></span> |
|<span data-ttu-id="1e36d-172">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-172">**Possible values**</span></span>  | <span data-ttu-id="1e36d-173">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="1e36d-174">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="1e36d-175">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-175">**Availability**</span></span> |<span data-ttu-id="1e36d-176">16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-176">16.28 and later</span></span> |

<span data-ttu-id="1e36d-177">Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 đã đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="1e36d-178">Trừ khi bạn đã đặt tùy chọn này là `FALSE`, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="1e36d-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="1e36d-179">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="1e36d-180">Cài đặt tùy chọn cho hầu hết các trải nghiệm được kết nối</span><span class="sxs-lookup"><span data-stu-id="1e36d-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="1e36d-181">Bạn có thể sử dụng tùy chọn này để kiểm soát liệu hầu hết các trải nghiệm được kết nối đã sẵn dùng với người dùng của bạn hay chưa.</span><span class="sxs-lookup"><span data-stu-id="1e36d-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-182">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="1e36d-183">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="1e36d-184">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-184">**Data Type**</span></span>  | <span data-ttu-id="1e36d-185">Boolean</span><span class="sxs-lookup"><span data-stu-id="1e36d-185">Boolean</span></span> |
|<span data-ttu-id="1e36d-186">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-186">**Possible values**</span></span>  | <span data-ttu-id="1e36d-187">`TRUE` *(đã bật)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="1e36d-188">`FALSE` *(đã tắt)*</span><span class="sxs-lookup"><span data-stu-id="1e36d-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="1e36d-189">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-189">**Availability**</span></span> |<span data-ttu-id="1e36d-190">16.28 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-190">16.28 and later</span></span> |

<span data-ttu-id="1e36d-191">Nếu bạn không đặt tùy chọn này, tất cả trải nghiệm được kết nối đều sẽ sẵn dùng với người dùng của bạn, trừ khi bạn đã thiết lập một trong các tùy chọn khác đối với trải nghiệm được kết nối đã đề cập ở trên, chẳng hạn như `OfficeExperiencesAnalyzingContentPreference`.</span><span class="sxs-lookup"><span data-stu-id="1e36d-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="1e36d-192">Ví dụ: nếu bạn đặt tùy chọn này là `FALSE` thì các loại trải nghiệm được kết nối sau sẽ không sẵn dùng cho người dùng của bạn:</span><span class="sxs-lookup"><span data-stu-id="1e36d-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="1e36d-193">Trải nghiệm phân tích nội dung của bạn</span><span class="sxs-lookup"><span data-stu-id="1e36d-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="1e36d-194">Trải nghiệm tải xuống nội dung trực tuyến</span><span class="sxs-lookup"><span data-stu-id="1e36d-194">Experiences that download online content</span></span>
- <span data-ttu-id="1e36d-195">Trải nghiệm được kết nối tuỳ chọn</span><span class="sxs-lookup"><span data-stu-id="1e36d-195">Optional connected experiences</span></span>

<span data-ttu-id="1e36d-196">Ngoài ra, nếu bạn đặt tùy chọn này là `FALSE` thì hầu hết các trải nghiệm được kết nối khác cũng sẽ bị tắt, chẳng hạn như đồng tác giả và lưu trữ tệp trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="1e36d-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="1e36d-197">Để biết danh sách về các trải nghiệm được kết nối khác kiểu này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="1e36d-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="1e36d-198">Nhưng ngay cả khi bạn đặt tùy chọn này là `FALSE` thì vẫn có một số chức năng Office giới hạn, như chức năng đồng bộ hóa hộp thư trong Outlook và Teams và Skype for Business vẫn tiếp tục hoạt động.</span><span class="sxs-lookup"><span data-stu-id="1e36d-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="1e36d-199">[Các dịch vụ thiết yếu](essential-services.md), chẳng hạn như dịch vụ cấp phép xác nhận bạn đã được cấp phép sử dụng Office đúng cách, cũng vẫn sẵn dùng.</span><span class="sxs-lookup"><span data-stu-id="1e36d-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="1e36d-200">Nếu người dùng có đăng ký Office 365 và đã đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt hầu hết trải nghiệm được kết nối.</span><span class="sxs-lookup"><span data-stu-id="1e36d-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="1e36d-201">Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, họ có thể chọn tắt hầu hết các trải nghiệm được kết nối bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.</span><span class="sxs-lookup"><span data-stu-id="1e36d-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="1e36d-202">Cài đặt tùy chọn cho hộp thoại Thông báo dữ liệu bắt buộc cho Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="1e36d-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="1e36d-203">Khi lần đầu khởi chạy Microsoft AutoUpdate (MAU) phiên bản 4.12 trở lên, những người dùng sẽ thấy một hộp thoại **Thông báo dữ liệu bắt buộc** cho họ biết những dữ liệu nào từ MAU được gửi tới Microsoft.</span><span class="sxs-lookup"><span data-stu-id="1e36d-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="1e36d-204">Nếu bạn không muốn người dùng của mình thấy hộp thoại **Thông báo dữ liệu bắt buộc** gửi tới cho Microsoft AutoUpdate này, bạn có thể đặt tùy chọn như sau.</span><span class="sxs-lookup"><span data-stu-id="1e36d-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="1e36d-205">Bất kể bạn đặt giá trị nào, hộp thoại sẽ không được hiển thị cho người dùng của bạn.</span><span class="sxs-lookup"><span data-stu-id="1e36d-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e36d-206">**Miền để đặt tùy chọn**</span><span class="sxs-lookup"><span data-stu-id="1e36d-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="1e36d-207">**Khóa**</span><span class="sxs-lookup"><span data-stu-id="1e36d-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="1e36d-208">**Kiểu Dữ liệu**</span><span class="sxs-lookup"><span data-stu-id="1e36d-208">**Data Type**</span></span>  | <span data-ttu-id="1e36d-209">Chuỗi</span><span class="sxs-lookup"><span data-stu-id="1e36d-209">String</span></span> |
|<span data-ttu-id="1e36d-210">**Giá trị khả thi**</span><span class="sxs-lookup"><span data-stu-id="1e36d-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="1e36d-211">**Tính khả dụng**</span><span class="sxs-lookup"><span data-stu-id="1e36d-211">**Availability**</span></span> |<span data-ttu-id="1e36d-212">4.12 trở lên</span><span class="sxs-lookup"><span data-stu-id="1e36d-212">4.12 and later</span></span> |

<span data-ttu-id="1e36d-213">Nếu bạn cho phép người dùng của mình thấy hộp thoại này thì khi họ chọn **OK**, giá trị `RequiredDataOnly` sẽ được ghi vào `AcknowledgedDataCollectionPolicy` và hộp thoại sẽ không được hiển thị lại cho người dùng.</span><span class="sxs-lookup"><span data-stu-id="1e36d-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="1e36d-214">Chủ đề liên quan</span><span class="sxs-lookup"><span data-stu-id="1e36d-214">Related topics</span></span>

- [<span data-ttu-id="1e36d-215">Tham chiếu Hồ sơ Cấu hình (Tài liệu nhà phát triển Apple)</span><span class="sxs-lookup"><span data-stu-id="1e36d-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="1e36d-216">Áp dụng tùy chọn dành cho Office for Mac</span><span class="sxs-lookup"><span data-stu-id="1e36d-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="1e36d-217">Cài đặt Quyền riêng tư Tài khoản </span><span class="sxs-lookup"><span data-stu-id="1e36d-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
