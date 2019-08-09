---
title: Sử dụng tùy chọn để quản lý các điều khiển quyền riêng tư đối với Office for Mac
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
description: Thông tin cho người quản trị Office về cách sử dụng tùy chọn để quản lý các điều khiển quyền riêng tư đối với Office for Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246336"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>Sử dụng tùy chọn để quản lý các điều khiển quyền riêng tư đối với Office for Mac

Từ Phiên bản 16.28 của Office for Mac trở đi sẽ có các thiết đặt tùy chọn mới cho phép bạn kiểm soát các thiết đặt liên quan đến những vấn đề sau đây:

- ***Dữ liệu chẩn đoán*** về phần mềm máy khách Office đang được sử dụng được thu thập và gửi cho Microsoft.

- ***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Ngoài ra, còn có một thiết đặt tùy chọn mới liên quan đến hộp thoại ** Thông báo dữ liệu bắt buộc** cho Microsoft AutoUpdate (MAU).

Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về điều khiển quyền riêng tư](overview-privacy-controls.md).

> [!NOTE]
> Để biết thông tin về các cài đặt tương tự đối với Office trên máy tính chạy Windows, hãy xem mục [ Sử dụng thiết đặt chính sách để quản lý các điều khiển quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)

## <a name="setting-preferences"></a>Tùy chọn thiết đặt

Các tùy chọn thiết đặt mới này tương thích với CFPreferences API và có thể được đặt bằng cách sử dụng `defaults` lệnh trong Thiết bị đầu cuối hoặc được áp dụng thông qua một Hồ sơ Cấu hình hoặc máy chủ Quản lý thiết bị di động (MDM). Khi tùy chọn đã được áp dụng thì người dùng không thể thay đổi các giá trị và mọi điều khiển trong ứng dụng sẽ bị vô hiệu hóa.

## <a name="preference-setting-for-diagnostic-data"></a>Thiết đặt tùy chọn dành cho dữ liệu chẩn đoán

Dữ liệu chẩn đoán được sử dụng để giúp cho Office được an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm. Để biết thêm thông tin, hãy xem mục [Dữ liệu chẩn đoán được gửi từ Office 365 ProPlus tới Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.office` |
|**Phím**  | `DiagnosticDataTypePreference`  |
|**Kiểu Dữ liệu**  | Chuỗi |
|**Giá trị khả thi**  | `BasicDiagnosticData` *(đặt ở mức Bắt buộc)* <br/> `FullDiagnosticData` *(đặt ở mức Tùy chọn)* <br/> `ZeroDiagnosticData` *(không áp dụng mức nào ở trên)* |
|**Tính khả dụng** |16.28 trở lên |

> [!NOTE]
> Nếu bạn chọn tùy chọn này thì nó cũng sẽ áp dụng cho các sản phẩm sau đây:
> - Các phiên bản từ 1.00.217856 trở lên của Teams for Mac
> - Các phiên bản từ 16.28 trở lên của Skype for Business for Mac

Nếu bạn không thiết đặt tùy chọn này thì cả dữ liệu chẩn đoán bắt buộc lẫn tùy chọn sẽ được gửi tới Microsoft nếu người dùng có đăng ký Office 365 đang đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 dành cho máy Mac được cấp phép số lượng lớn. Ngoài ra, những người dùng này không thể thay đổi mức độ dữ liệu chẩn đoán của bạn, bất kể việc bạn thiết đặt tùy chọn ra sao.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365 thì chỉ có dữ liệu chẩn đoán bắt buộc mới được gửi đi, trừ khi người dùng vào mục **Tùy chọn** > **Quyền riêng tư** để chọn gửi luôn cả dữ liệu chẩn đoán tùy chọn.

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Thiết đặt tùy chọn cho các trải nghiệm được kết nối phân tích nội dung của bạn

Các trải nghiệm được kết nối phân tích nội dung của bạn là các trải nghiệm sử dụng nội dung Office của bạn để cung cấp cho bạn các đề xuất thiết kế, đề xuất chỉnh sửa, thông tin chi tiết và các tính năng tương tự. Ví dụ: PowerPoint Designer hoặc Trình nghiên cứu trong Word. Để biết về danh sách các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.office` |
|**Phím**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối có phân tích nội dung sẽ sẵn dùng cho người dùng. 

Nếu người dùng có đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối phân tích nội dung.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối phân tích nội dung bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Thiết đặt tùy chọn cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến

Trải nghiệm được kết nối tải xuống nội dung trực tuyến là những trải nghiệm cho phép bạn tìm kiếm và tải xuống nội dung trực tuyến bao gồm các mẫu, hình ảnh, mô hình 3D, video và tài liệu tham khảo để cải thiện tài liệu của bạn. Ví dụ: mẫu Office hoặc Trình Bắt đầu Nhanh PowerPoint. Để biết danh sách về các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.office` |
|**Phím**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này thì các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ sẵn dùng cho người dùng.

Nếu người dùng có đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt trải nghiệm được kết nối tải xuống nội dung trực tuyến.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, người dùng có thể chọn tắt các trải nghiệm được kết nối tải xuống nội dung trực tuyến bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Thiết đặt tùy chọn cho các trải nghiệm được kết nối tùy chọn.

Ngoài các trải nghiệm được kết nối được đề cập ở trên, còn có một số trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của bạn truy cập bằng tài khoản tổ chức của họ - đôi khi được gọi là tài khoản cơ quan hoặc trường học. Ví dụ: các tính năng LinkedIn của Trợ lý Sơ yếu lý lịch trong Word hoặc Thanh Thời tiết trong Outlook sử dụng Thời tiết trên MSN. Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tuỳ chọn trong Office](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.office` |
|**Phím**  | `OptionalConnectedExperiencesPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không thiết đặt tùy chọn này thì dữ liệu chẩn đoán tùy chọn sẽ sẵn dùng đối với người dùng có đăng ký Office 365 đang đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 dành cho máy Mac được cấp phép số lượng lớn. Trừ khi bạn đã đặc tùy chọn này là`FALSE`, những người dùng này có thể chọn tắt trải nghiệm được kết nối tùy chọn bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, sẽ không có tùy chọn để tắt trải nghiệm được kết nối tùy chọn.

## <a name="preference-setting-for-most-connected-experiences"></a>Thiết đặt tùy chọn cho hầu hết các trải nghiệm được kết nối

Bạn có thể sử dụng tùy chọn này để kiểm soát xem hầu hết các trải nghiệm được kết nối đã sẵn dùng với người dùng của bạn hay chưa.

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.office` |
|**Phím**  | `ConnectedOfficeExperiencesPreference`  |
|**Kiểu Dữ liệu**  | Boolean |
|**Giá trị khả thi**  | `TRUE` *(đã bật)* <br/> `FALSE` *(đã tắt)*|
|**Tính khả dụng** |16.28 trở lên |

Nếu bạn không đặt tùy chọn này, tất cả các trải nghiệm được kết nối đều sẽ sẵn dùng với người dùng của bạn, trừ khi bạn đã thiết lập một trong các tùy chọn khác đối với trải nghiệm kết nối đã được đề cập ở trên, chẳng hạn như`OfficeExperiencesAnalyzingContentPreference`.

Ví dụ: nếu bạn thiết lập tùy chọn này là `FALSE` thì các loại trải nghiệm được kết nối sau sẽ không sẵn dùng cho người dùng của bạn:
- Trải nghiệm phân tích nội dung của bạn
- Trải nghiệm tải xuống nội dung trực tuyến
- Trải nghiệm được kết nối tuỳ chọn

Ngoài ra, nếu bạn thiết đặt tùy chọn này là `FALSE` thì hầu hết các trải nghiệm được kết nối khác cũng sẽ bị tắt, chẳng hạn như đồng tác giả và lưu trữ tệp trực tuyến. Để biết danh sách về các trải nghiệm được kết nối khác này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Nhưng ngay cả khi bạn thiết đặt tùy chọn này là `FALSE` thì chức năng Office bị giới hạn sẽ vẫn sẵn dùng, chẳng hạn như chức năng đồng bộ hóa hộp thư trong Outlook và Teams và Skype for Business vẫn tiếp tục hoạt động. [Các dịch vụ cần thiết](essential-services.md), chẳng hạn như dịch vụ cấp phép xác nhận bạn đã được cấp phép sử dụng Office đúng cách, cũng sẽ vẫn sẵn dùng.

Nếu người dùng có đăng ký Office 365 và được đăng nhập bằng tài khoản cơ quan hoặc trường học hoặc nếu người dùng có một phiên bản Office 2019 for Mac được cấp phép số lượng lớn thì người dùng đó sẽ không thể tắt hầu hết trải nghiệm được kết nối.

Đối với những người dùng khác, chẳng hạn như người dùng gia đình có đăng ký Office 365, họ có thể chọn tắt các hầu hết trải nghiệm được kết nối bằng cách vào mục **Tùy chọn** > **Quyền riêng tư**.

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>Cài đặt tùy chọn cho hộp thoại Thông báo dữ liệu bắt buộc cho Microsoft AutoUpdate

Ngay khi các phiên bản từ 4.12 trở lên của Microsoft AutoUpdate (MAU) được tung ra, những người dùng sẽ thấy một hộp thoại **Thông báo dữ liệu bắt buộc** cho họ biết những dữ liệu từ MAU nào được gửi tới Microsoft.

Nếu bạn không muốn người dùng của mình thấy hộp thoại **Thông báo dữ liệu bắt buộc** gửi tới cho Microsoft AutoUpdate này, bạn có thể đặt tùy chọn theo như sau đây. Bất kể bạn đặt giá trị nào, hộp thoại sẽ không được hiển thị cho người dùng của bạn.

|||
|:-----|:-----|
|**Phạm vi tùy chọn**  | `com.microsoft.autoupdate2` |
|**Phím**  | `AcknowledgedDataCollectionPolicy`  |
|**Kiểu Dữ liệu**  | Chuỗi |
|**Giá trị khả thi**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Tính khả dụng** |4.12 trở lên |

Nếu bạn cho phép người dùng của mình nhìn thấy hộp thoại này thì khi họ chọn**OK** thì giá trị `RequiredDataOnly` sẽ được ghi vào `AcknowledgedDataCollectionPolicy` và hộp thoại sẽ không được hiển thị lại cho người dùng.


## <a name="related-topics"></a>Chủ đề liên quan

- [Tham chiếu Hồ sơ Cấu hình (tài liệu nhà phát triển Apple)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [Áp dụng tùy chọn dành cho Office for Mac](../mac/deploy-preferences-for-office-for-mac.md)
- [Thiết đặt Quyền riêng tư Tài khoản ](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
