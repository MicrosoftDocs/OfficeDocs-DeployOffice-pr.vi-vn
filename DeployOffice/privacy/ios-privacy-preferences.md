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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS

Sẽ có các cài đặt tùy chọn mới cho Office trên thiết bị iOS cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:

- ***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.

- ***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).

Các cài đặt tùy chọn này sẽ áp dụng cho các ứng dụng sau đây:
- Phiên bản 2.30 trở lên trong Word for iOS, Excel for iOS và PowerPoint for iOS.
- Phiên bản 4.30.0 trở lên trong Outlook for iOS
- Phiên bản 16.30 trở lên trong OneNote for iOS.
- Phiên bản 11.19.11 trở lên trong OneDrive for iOS.
- Phiên bản 1.17 trở lên của Visio Viewer for iOS.
- Phiên bản 2.34 trở lên của ứng dụng Office dành cho iOS.

> [!NOTE]
> Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên các máy tính chạy macOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office for Mac](mac-privacy-preferences.md).


## <a name="setting-device-preferences"></a>Cài đặt tùy chọn thiết bị
Các cài đặt tùy chọn mới cũng có thể được đặt ở cấp thiết bị bằng một máy chủ Quản lý Thiết bị Di động (MDM) khi cài đặt ứng dụng Office. Nhiều máy chủ MDM cho phép người quản trị CNTT thêm một từ điển cấu hình tùy chọn khi máy chủ gửi lệnh MDM `InstallApplication` đến một thiết bị chạy iOS. Hãy tham khảo tài liệu hướng dẫn máy chủ MDM của bạn để biết thêm chi tiết.

Từ điển được thể hiện dưới dạng một tập hợp các cặp khóa/giá trị theo định dạng XML. Ví dụ:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Sau khi được gửi tới thiết bị, từ điển cấu hình sẽ nằm bên dưới phím `com.apple.managed.configuration`, nơi nó sẽ được đọc khi ứng dụng Office được khởi chạy.

> [!NOTE]
> Bạn cũng có thể sử dụng dịch vụ chính sách đám mây Office và 4 thiết đặt chính sách này:
> - Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft
> - Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office
> - Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office
> - Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office
>
> Cài đặt quyền riêng tư cho Outlook for iOS và OneDrive for iOS chỉ có thể được cấu hình bằng cách sử dụng dịch vụ chính sách điện toán đám mây của Office.
>
> Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).

## <a name="preference-setting-for-diagnostic-data"></a>Cài đặt tùy chọn dành cho dữ liệu chẩn đoán

Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm. Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|||
|:-----|:-----|
|**Khóa**  | `DiagnosticDataTypePreference`  |
|**Kiểu Dữ liệu**  | Chuỗi |
|**Giá trị khả thi**  | `BasicDiagnosticData` *(đặt ở mức Bắt buộc)* <br/> `FullDiagnosticData` *(đặt ở mức Tùy chọn)* <br/> `ZeroDiagnosticData` *(không áp dụng mức nào ở trên)* |

Nếu bạn không đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc và tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) đang đăng nhập bằng tài khoản cơ quan hoặc trường học. Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục **Cài đặt ** > **Cài đặt Quyền riêng tư**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn

Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự. Ví dụ: Ý tưởng thiết kế trong PowerPoint. Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Khóa**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|


Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng.

Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến

Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các biểu mẫu, hình ảnh, video và tài liệu tham khảo để cải thiện tài liệu của bạn. Ví dụ: các biểu mẫu Office hoặc chèn biểu tượng trực tuyến. Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Khóa**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|


Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.

Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc thì người dùng đó sẽ không thể tắt trải nghiệm tải xuống nội dung trực tuyến.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn

Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học. Ví dụ: các phần bổ trợ dành cho Office được tải xuống thông qua Office Store đến thiết bị của bạn. Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Khóa**  | `OptionalConnectedExperiencesPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|


Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đã đăng nhập bằng tài khoản cơ quan hoặc trường học. Trừ khi bạn đã đặt tùy chọn này là FALSE, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Cài đặt** > **Cài đặt Quyền riêng tư**.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.