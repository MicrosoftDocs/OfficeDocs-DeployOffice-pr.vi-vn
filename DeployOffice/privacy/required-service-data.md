---
title: Dữ liệu dịch vụ bắt buộc cho Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office cái nhìn tổng quan về dữ liệu dịch vụ bắt buộc được thu thập về các trải nghiệm được kết nối trong Office.
hideEdit: true
ms.openlocfilehash: faa3507708b4768ee3b2b0f51257273c31ad2de7
ms.sourcegitcommit: 73158b40bdc2d83bdadedeafe0fd152b449d2a44
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/11/2020
ms.locfileid: "47440221"
---
# <a name="required-service-data-for-office"></a>Dữ liệu dịch vụ bắt buộc cho Office

> [!NOTE]
> Để biết danh sách các sản phẩm Office nằm trong thông tin về quyền riêng tư này, hãy xem [Kiểm soát về quyền riêng tư sẵn có cho các sản phẩm Office](products-versions-privacy-controls.md).

Office bao gồm các ứng dụng phần mềm máy khách và [trải nghiệm được kết nối](connected-experiences.md) đã được thiết kế để hỗ trợ bạn sáng tạo, giao tiếp và cộng tác hiệu quả hơn. Làm việc với những người khác trên một tài liệu được lưu trữ trên OneDrive for Business hoặc dịch nội dung của tài liệu Word sang một ngôn ngữ khác là những ví dụ về trải nghiệm được kết nối.

Khi bạn sử dụng trải nghiệm được kết nối, dữ liệu sẽ được gửi đến và xử lý bởi Microsoft để cung cấp cho bạn trải nghiệm được kết nối. Dữ liệu này rất quan trọng vì thông tin này cho phép chúng tôi cung cấp các trải nghiệm được kết nối dựa trên nền điện toán đám mây. Chúng tôi gọi các dữ liệu này là dữ liệu dịch vụ bắt buộc.

Dữ liệu dịch vụ bắt buộc có thể bao gồm các thông tin liên quan đến hoạt động của trải nghiệm được kết nối cần thiết để đảm bảo dịch vụ cơ sở an toàn, luôn được cập nhật và hoạt động như mong đợi. Nếu bạn chọn sử dụng trải nghiệm được kết nối sẽ phân tích nội dung của bạn như Dịch trong Word, văn bản bạn đã nhập và đã chọn để dịch trong tài liệu cũng sẽ được gửi đi và xử lý để cung cấp trải nghiệm được kết nối cho bạn. Dữ liệu dịch vụ bắt buộc cũng có thể bao gồm các thông tin mà trải nghiệm được kết nối cần để thực hiện tác vụ của mình như thông tin về cấu hình của ứng dụng Office.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Ví dụ về dữ liệu dịch vụ bắt buộc cho trải nghiệm được kết nối

Hãy xem PowerPoint Designer là một ví dụ khác để cho thấy loại dữ liệu dịch vụ bắt buộc mà trải nghiệm được kết nối gửi đến Microsoft. PowerPoint Designer giúp cải thiện các trang chiếu của bạn bằng cách tự động tạo các ý tưởng thiết kế mà bạn có thể chọn. Khi bạn dự định đưa nội dung vào một trang chiếu, Trình thiết kế sẽ hoạt động trong nền để khớp nội dung đó với các bố trí được thiết kế chuyên nghiệp.

Dữ liệu dịch vụ bắt buộc mà PowerPoint Designer gửi đến Microsoft có thể bao gồm các thông tin sau:
- Văn bản hoặc hình ảnh mà bạn đã thêm vào trang chiếu của mình.
- Trang chiếu bạn đang làm việc và bố cục của trang chiếu.
- Xác minh xem ý tưởng thiết kế có được áp dụng chính xác vào trang chiếu của bạn không.
- Xác minh xem tương tác giữa PowerPoint và dịch vụ Dịch vụ có hoạt động như mong đợi không.

Dữ liệu dịch vụ bắt buộc này sẽ giúp đảm bảo PowerPoint Designer hoạt động như mong đợi.

## <a name="manage-required-service-data"></a>Quản lý dữ liệu dịch vụ bắt buộc

Chúng tôi tạo điều kiện để bạn có thể lựa chọn loại trải nghiệm được kết nối mà bạn muốn sử dụng trong Office, từ đó xác định dữ liệu dịch vụ bắt buộc nào sẽ được gửi đến Microsoft. Ví dụ: Tính năng Đọc chính tả trong Word là một trong số ít trải nghiệm được kết nối sẽ phân tích nội dung của bạn. Nếu bạn chọn tắt trải nghiệm được kết nối có phân tích nội dung, không có dữ liệu dịch vụ bắt buộc nào về tính năng Đọc chính tả trong Word sẽ được gửi đến Microsoft vì tính năng Đọc chính tả trong Word sẽ không thể sử dụng được. Để biết thêm thông tin, hãy xem [Chọn xem các trải nghiệm được kết nối này có thể sử dụng được không](connected-experiences.md#choose-whether-these-connected-experiences-are-available-to-use).

Dữ liệu dịch vụ bắt buộc khác với [dữ liệu chẩn đoán](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft) tùy chọn hoặc bắt buộc, đây là các dữ liệu liên quan đến thông tin về việc sử dụng phần mềm Office đang chạy trên thiết bị của bạn. Vì vậy, các cài đặt quyền riêng tư mà bạn chọn cho dữ liệu chẩn đoán tùy chọn hoặc bắt buộc không ảnh hưởng đến dữ liệu dịch vụ bắt buộc nào sẽ được gửi đến Microsoft.

Dữ liệu dịch vụ bắt buộc cũng sẽ được thu thập và gửi đến Microsoft để hỗ trợ các [dịch vụ thiết yếu](essential-services.md) của Office như dịch vụ cấp phép sẽ xác nhận bạn đã được cấp phép hợp lệ để sử dụng Office. Mặc dù bạn có thể kiểm soát nhiều trải nghiệm được kết nối sẵn dùng đối với bạn hoặc đối với người dùng của bạn nếu bạn là người quản trị trong tổ chức của bạn nhưng bộ dịch vụ này vẫn rất quan trọng đối với cách hoạt động của Office và do đó không thể bị tắt được. Dữ liệu của các dịch vụ thiết yếu luôn được gửi đến và xử lý bởi Microsoft khi sử dụng Office dù đã đặt cấu hình cho các cài đặt khác liên quan đến quyền riêng tư như thế nào.

Dữ liệu dịch vụ bắt buộc có sẵn thông qua các Yêu cầu dịch vụ dữ liệu (DSR). Để biết thêm thông tin, hãy xem [Điều khoản về quyền riêng tư của Microsoft](https://privacy.microsoft.com/privacystatement) và [Yêu cầu chủ thể dữ liệu Office 365 đối với GDPR và CCPA](https://docs.microsoft.com/microsoft-365/compliance/gdpr-dsr-office365).

Nếu bạn là người quản trị cho tổ chức của bạn và muốn quản lý trải nghiệm được kết nối, hãy xem các bài viết sau:

- [Tổng quan về các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office cho Mac](mac-privacy-preferences.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS](ios-privacy-preferences.md)
- [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android](android-privacy-controls.md)
- [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với các ứng dụng Office trên web](office-web-privacy-controls.md)

## <a name="categories-of-required-service-data"></a>Danh mục dữ liệu dịch vụ bắt buộc

Dữ liệu dịch vụ bắt buộc được phân chia thành các danh mục sau:

- Thiết lập phần mềm và hàng tồn kho
- Sử dụng sản phẩm và dịch vụ
- Hiệu suất sản phẩm và dịch vụ
- Khả năng kết nối và cấu hình thiết bị

Thông tin trong các danh mục này cho phép Microsoft đánh giá xem trải nghiệm được kết nối hoặc dịch vụ thiết yếu có an toàn, đã được cập nhật và hoạt động như mong đợi không.

Ví dụ: Thông tin trong danh mục hiệu suất sản phẩm và dịch vụ có thể bao gồm các sự cố không mong muốn (lỗi không hoạt động), thời gian hoặc hiệu suất phản hồi chậm chạp hoặc lỗi chức năng.

Đối với danh mục mức sử dụng sản phẩm và dịch vụ, thông tin có thể được thu thập để cho biết xem dịch vụ dùng bởi trải nghiệm được kết nối đã khởi động thành công và sẵn dùng khi cần thiết chưa.