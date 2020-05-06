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
ms.openlocfilehash: d23d1288adf823888c900b44acd5bc905037cd94
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/01/2020
ms.locfileid: "43992895"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office for Mac

Từ Phiên bản 16.28 của Office for Mac trở đi, sẽ có các cài đặt tùy chọn mới cho phép bạn kiểm soát các cài đặt liên quan đến vấn đề sau đây:

- ***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.

- ***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Ngoài ra, còn có một cài đặt tùy chọn mới liên quan đến hộp thoại ** Thông báo dữ liệu bắt buộc** cho Microsoft AutoUpdate (MAU).

Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).

> [!NOTE]
> - Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên máy tính chạy Windows, xem mục [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](manage-privacy-controls.md).
> - Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên thiết bị iOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị chạy iOS](ios-privacy-preferences.md).

## <a name="setting-preferences"></a>Tùy chọn cài đặt

Các tùy chọn cài đặt mới này tương thích với CFPreferences API và có thể được đặt bằng cách sử dụng lệnh `defaults` trong Thiết bị đầu cuối hoặc được áp dụng thông qua một Hồ sơ Cấu hình hoặc máy chủ Quản lý thiết bị di động (MDM). Khi tùy chọn đã được áp dụng thì người dùng không thể thay đổi các giá trị và mọi biện pháp kiểm soát trong ứng dụng sẽ bị vô hiệu hóa.

> [!NOTE]
> Bạn cũng có thể sử dụng dịch vụ chính sách đám mây Office và 5 thiết đặt chính sách này:
> - Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft
> - Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office
> - Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office
> - Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office
> - Cho phép sử dụng các trải nghiệm được kết nối trong Office
>
> Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).


## <a name="preference-setting-for-diagnostic-data"></a>Cài đặt tùy chọn dành cho dữ liệu chẩn đoán

Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm. Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.office` |
|**Khóa**  | `DiagnosticDataTypePreference`  |
|**Kiểu Dữ liệu**  | Chuỗi |
|**Giá trị khả thi**  | `BasicDiagnosticData` *(đặt ở mức Bắt buộc)* <br/> `FullDiagnosticData` *(đặt ở mức Tùy chọn)* <br/> `ZeroDiagnosticData` *(không áp dụng mức nào ở trên)* |
|**Tính khả dụng** |16.28 trở lên |

Từ bản cài đặt mới của Phiên bản 16.30 trở đi, nếu bạn không thiết lập tùy chọn này thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc tới Microsoft, đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đăng nhập bằng tài khoản cơ quan hay trường học hoặc người dùng sở hữu phiên bản Office 2019 for Mac được cấp phép theo số lượng lớn. Ngoài ra, những người dùng này không thể thay đổi cấp dữ liệu chẩn đoán, bất kể bạn đặt tùy chọn này như thế nào.

> [!NOTE]
> - Nếu bạn cài đặt Phiên bản 16.28 hoặc 16.29 và không thiết lập tùy chọn này thì ứng dụng sẽ gửi cả dữ liệu chẩn đoán tự chọn và bắt buộc tới Microsoft. Nếu sau đó bạn nâng cấp lên Phiên bản 16.30 trở lên thì ứng dụng vẫn sẽ gửi cả dữ liệu chẩn đoán tự chọn và bắt buộc tới Microsoft, trừ khi bạn dùng tùy chọn này để thiết lập một giá trị khác.
> - Nếu bạn thiết lập tùy chọn này, tuỳ chọn vẫn sẽ áp dụng cho Teams for Mac phiên bản 1.00.217856 trở lên và Skype for Business for Mac phiên bản 16.28 trở lên.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), thì ứng dụng sẽ chỉ gửi dữ liệu chẩn đoán bắt buộc, trừ khi người dùng chọn gửi cả dữ liệu chẩn đoán tự chọn bằng cách truy cập mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn

Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự. Ví dụ: PowerPoint Designer hoặc Trình nghiên cứu trong Word. Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.office` |
|**Khóa**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối phân tích nội dung sẽ khả dụng với người dùng. 

Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến

Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các mẫu, hình ảnh, mô hình 3D, video và tài liệu tham khảo để cải thiện tài liệu của bạn. Ví dụ: mẫu Office hoặc Trình Bắt đầu Nhanh PowerPoint. Để biết danh sách về các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.office` |
|**Khóa**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.

Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối tải xuống nội dung trực tuyến.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Cài đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn

Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của mình truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học. Ví dụ: các tính năng LinkedIn của Trợ lý Sơ yếu lý lịch trong Word hoặc Thanh Thời tiết trong Outlook sử dụng Thời tiết trên MSN. Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tùy chọn trong Office](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.office` |
|**Khóa**  | `OptionalConnectedExperiencesPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này thì trải nghiệm được kết nối tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 (hoặc Microsoft 365) đã đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn. Trừ khi bạn đã đặt tùy chọn này là `FALSE`, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), sẽ không có tùy chọn tắt trải nghiệm được kết nối tùy chọn.

## <a name="preference-setting-for-most-connected-experiences"></a>Cài đặt tùy chọn cho hầu hết các trải nghiệm được kết nối

Bạn có thể sử dụng tùy chọn này để kiểm soát liệu hầu hết các trải nghiệm được kết nối đã sẵn dùng với người dùng của bạn hay chưa.

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.office` |
|**Khóa**  | `ConnectedOfficeExperiencesPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này, tất cả trải nghiệm được kết nối đều sẽ sẵn dùng với người dùng của bạn, trừ khi bạn đã thiết lập một trong các tùy chọn khác đối với trải nghiệm được kết nối đã đề cập ở trên, chẳng hạn như `OfficeExperiencesAnalyzingContentPreference`.

Ví dụ: nếu bạn đặt tùy chọn này là `FALSE` thì các loại trải nghiệm được kết nối sau sẽ không sẵn dùng cho người dùng của bạn:
- Trải nghiệm phân tích nội dung của bạn
- Trải nghiệm tải xuống nội dung trực tuyến
- Trải nghiệm được kết nối tuỳ chọn

Ngoài ra, nếu bạn đặt tùy chọn này là `FALSE` thì hầu hết các trải nghiệm được kết nối khác cũng sẽ bị tắt, chẳng hạn như đồng tác giả và lưu trữ tệp trực tuyến. Để biết danh sách về các trải nghiệm được kết nối khác kiểu này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Nhưng ngay cả khi bạn đặt tùy chọn này là `FALSE` thì vẫn có một số chức năng Office giới hạn, như chức năng đồng bộ hóa hộp thư trong Outlook và Teams và Skype for Business vẫn tiếp tục hoạt động. [Các dịch vụ cần thiết](essential-services.md), chẳng hạn như dịch vụ cấp phép xác nhận rằng bạn đã được cấp phép sử dụng Office đúng cách, cũng sẽ vẫn khả dụng.

Nếu người dùng có đăng ký Office 365 (hoặc Microsoft 365) và đã đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt hầu hết trải nghiệm được kết nối.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 (hoặc Microsoft 365), họ có thể chọn tắt hầu hết các trải nghiệm được kết nối bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>Cài đặt tùy chọn cho hộp thoại Thông báo dữ liệu bắt buộc cho Microsoft AutoUpdate

Khi lần đầu khởi chạy Microsoft AutoUpdate (MAU) phiên bản 4.12 trở lên, những người dùng sẽ thấy một hộp thoại **Thông báo dữ liệu bắt buộc** cho họ biết những dữ liệu nào từ MAU được gửi tới Microsoft.

Nếu bạn không muốn người dùng của mình thấy hộp thoại **Thông báo dữ liệu bắt buộc** gửi tới cho Microsoft AutoUpdate này, bạn có thể đặt tùy chọn như sau. Bất kể bạn đặt giá trị nào, hộp thoại sẽ không được hiển thị cho người dùng của bạn.

|||
|:-----|:-----|
|**Miền để đặt tùy chọn**  | `com.microsoft.autoupdate2` |
|**Khóa**  | `AcknowledgedDataCollectionPolicy`  |
|**Kiểu Dữ liệu**  | Chuỗi |
|**Giá trị khả thi**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Tính khả dụng** |4.12 trở lên |

Nếu bạn cho phép người dùng của mình thấy hộp thoại này thì khi họ chọn **OK**, giá trị `RequiredDataOnly` sẽ được ghi vào `AcknowledgedDataCollectionPolicy` và hộp thoại sẽ không được hiển thị lại cho người dùng.


## <a name="related-topics"></a>Chủ đề liên quan

- [Tham chiếu Hồ sơ Cấu hình (Tài liệu nhà phát triển Apple)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [Áp dụng tùy chọn dành cho Office for Mac](../mac/deploy-preferences-for-office-for-mac.md)
- [Cài đặt Quyền riêng tư Tài khoản ](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
