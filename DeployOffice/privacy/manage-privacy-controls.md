---
title: Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office những thông tin về cách quản lý kiểm soát quyền riêng tư trong Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn (trước đây là Office 365 Proplus) bằng cách sử dụng các thiết đặt chính sách.
hideEdit: true
ms.openlocfilehash: ca076099be15a5a4cd19ac7c99660bfe26de8eed
ms.sourcegitcommit: edd1190877db7996206147ad1d691fd8e84f23b1
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/05/2020
ms.locfileid: "44589050"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-microsoft-365-apps-for-enterprise"></a>Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn

Microsoft cam kết cung cấp cho bạn thông tin và quyền kiểm soát cần thiết để lựa chọn cách thu thập và sử dụng dữ liệu khi bạn dùng Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn (trước đây là Office 365 ProPlus).

Bắt đầu với Phiên bản 1904 của Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn, các thiết đặt chính sách mới sẽ cho phép bạn kiểm soát các thiết đặt liên quan đến những mục sau:

- ***Dữ liệu chẩn đoán*** được thu thập và gửi cho Microsoft về phần mềm máy khách Office đang được sử dụng

- ***Trải nghiệm được kết nối*** sử dụng chức năng dựa trên đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Sau đây là 5 thiết đặt chính sách mới:

- Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft
- Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office
- Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office
- Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office
- Cho phép sử dụng các trải nghiệm được kết nối trong Office

Các thiết đặt chính sách này có thể được thực hiện bằng cách sử dụng Chính sách nhóm hoặc [dịch vụ chính sách đám mây Office](https://docs.microsoft.com/DeployOffice/overview-office-client-policy-service). Nếu bạn sử dụng Chính sách nhóm, bạn cần tải xuống phiên bản mới nhất của tệp Mẫu quản trị (ADMX/ADML) từ [Trung tâm tải xuống Microsoft](https://www.microsoft.com/download/details.aspx?id=49030).

> [!NOTE]
> - Để biết thông tin về cách quản lý kiểm soát quyền riêng tư đối với Office cho Mac, hãy xem mục [Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office cho Mac](mac-privacy-preferences.md).
> - Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên thiết bị iOS, xem mục [Sử dụng tuỳ chọn để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị chạy iOS](ios-privacy-preferences.md).
> - Để tìm hiểu thông tin về các cài đặt tương tự cho Office trên thiết bị Android, xem mục [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android](android-privacy-controls.md).


Nếu bạn sử dụng công cụ quản lý chính sách nhóm, tất cả các cài đặt chính sách này đều được đặt trong Cấu hình người dùng\\Chính sách\\Mẫu quản trị\\Microsoft Office 2016\\Quyền riêng tư\\Trung tâm Tin cậy.

Các thiết đặt chính sách mới này cũng áp dụng cho các phiên bản Project và Visio trên máy tính để bàn đi kèm với một số gói đăng ký, chẳng hạn như Gói Project 5 hoặc Gói Visio 2. Thiết đặt này cũng áp dụng cho Ứng dụng Microsoft 365 dành cho doanh nghiệp (trước đây là Office 365 Business).

Ngoài ra, một số thiết đặt chính sách hiện tại sẽ không còn áp dụng cho Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn và có một số thay đổi giao diện người dùng (UI) đối với thiết đặt bảo mật. Bạn nên hiểu rõ những thay đổi này vì người dùng của bạn có thể nhận ra và thắc mắc về những thay đổi đó.

Cũng giống như bất kỳ thiết đặt chính sách mới nào, bạn nên kiểm tra cẩn thận trong môi trường được kiểm soát, hạn chế để đảm bảo các thiết đặt bạn cấu hình có hiệu quả mong muốn trước khi bạn triển khai thiết đặt chính sách rộng rãi hơn trong tổ chức của mình.

## <a name="policy-setting-for-diagnostic-data"></a>Thiết đặt chính sách dành cho dữ liệu chẩn đoán

Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm.

Bạn có thể sử dụng thiết đặt chính sách *Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi đến Microsoft* để chọn mức độ dữ liệu chẩn đoán được gửi đến Microsoft.

Nếu bạn bật thiết đặt chính sách này, bạn phải chọn mức độ dữ liệu chẩn đoán được gửi đến Microsoft. Lựa chọn của bạn được Bắt buộc, Tùy chọn hoặc Không có lựa chọn nào.

- Nếu bạn chọn ***Bắt buộc***, thì dữ liệu tối thiểu cần thiết để giúp Office an toàn, cập nhật và hoạt động như mong đợi trên thiết bị mà nó được cài đặt được gửi đến Microsoft.

- Nếu bạn chọn ***Tuỳ chọn***, dữ liệu bổ sung giúp chúng tôi cải tiến sản phẩm và cung cấp thông tin nâng cao để giúp chúng tôi phát hiện, chẩn đoán và khắc phục các sự cố được gửi đến Microsoft. Nếu bạn chọn gửi cho dữ liệu chẩn đoán tùy chọn, dữ liệu chẩn đoán bắt buộc cũng sẽ được bao gồm.

- Nếu bạn chọn ***Không có lựa chọn nào***, thì không có dữ liệu chẩn đoán nào về phần mềm máy khách Office chạy trên thiết bị người dùng được thu thập và gửi cho Microsoft. Tuy nhiên, tùy chọn này hạn chế đáng kể khả năng phát hiện, chẩn đoán và khắc phục các sự cố của Microsoft mà người dùng của bạn có thể gặp phải khi sử dụng Office.

Nếu bạn vô hiệu hóa hoặc không cấu hình thiết đặt chính sách này, cả dữ liệu chẩn đoán tùy chọn và bắt buộc sẽ được gửi đến Microsoft.

Để biết thêm thông tin về dữ liệu chẩn đoán, hãy xem các mục sau:

- [Tổng quan về các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md)
- [Dữ liệu chẩn đoán bắt buộc cho Office](required-diagnostic-data.md)
- [Dữ liệu chẩn đoán tuỳ chọn cho Office](optional-diagnostic-data.md)
- [Sử dụng Trình xem chẩn đoán dữ liệu với Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="policy-settings-for-connected-experiences"></a>Thiết đặt chính sách cho các trải nghiệm được kết nối

Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn bao gồm các ứng dụng phần mềm máy khách cùng những trải nghiệm kết nối được thiết kế nhằm hỗ trợ bạn khởi tạo, giao tiếp và cộng tác một cách hiệu quả hơn. Làm việc với những người khác trên một tài liệu được lưu trữ trên OneDrive for Business hoặc dịch nội dung của tài liệu Word sang một ngôn ngữ khác là những ví dụ về trải nghiệm được kết nối.

Chúng tôi hiểu rằng bạn có thể muốn chọn loại trải nghiệm được kết nối có sẵn cho người dùng của mình khi làm việc trong các ứng dụng Office. Vì vậy, chúng tôi đã cung cấp bốn thiết đặt chính sách mới cho bạn:

- Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office
- Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office
- Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office
- Cho phép sử dụng các trải nghiệm được kết nối trong Office

Nếu bạn không cấu hình các thiết đặt chính sách này, tất cả các trải nghiệm được kết nối sẽ có sẵn. Qua đó, người dùng của bạn sẽ sử dụng được tất cả các tính năng và chức năng có thể truy cập thông qua Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn. Nhưng chúng tôi hiểu rằng bạn có thể cần phải tắt một số hoặc tất cả những trải nghiệm được kết nối này để đáp ứng các yêu cầu nhất định của tổ chức của bạn.

Nếu bạn chọn không cung cấp cho người dùng của mình một số loại trải nghiệm được kết nối nhất định, lệnh ruy băng hoặc menu cho những trải nghiệm được kết nối đó sẽ bị mờ đi hoặc người dùng sẽ nhận được thông báo lỗi khi họ cố gắng sử dụng những trải nghiệm được kết nối đó. Trong trường hợp đó, sẽ không có [dữ liệu dịch vụ bắt buộc](required-service-data.md) cho những trải nghiệm được kết nối nào được gửi đến Microsoft.

Người dùng của bạn sẽ không thể chọn bật hoặc tắt các trải nghiệm được kết nối này với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn sau khi đăng nhập vào Office bằng thông tin đăng nhập tổ chức, đôi khi được gọi là tài khoản cơ quan hoặc trường học.

### <a name="policy-setting-for-connected-experiences-that-analyze-your-content"></a>Thiết đặt chính sách cho các trải nghiệm được kết nối phân tích nội dung của bạn

Đây là trải nghiệm sử dụng nội dung Office của bạn để cung cấp đề xuất thiết kế, đề xuất chỉnh sửa, dữ liệu thông tin chuyên sâu và các tính năng tương tự. Ví dụ: PowerPoint Designer hoặc Trình soạn thảo trong Word. Để biết danh sách về các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối phân tích nội dung trong Office* để kiểm soát xem các loại trải nghiệm được kết nối này có khả dụng cho người dùng của bạn hay không. Nếu bạn không cấu hình các cài đặt chính sách này, những trải nghiệm được kết nối này sẽ có sẵn cho người dùng của bạn.

Lưu ý rằng nếu bạn vô hiệu hóa thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối trong Office*, các trải nghiệm được kết nối phân tích nội dung sẽ không có sẵn cho người dùng của bạn.

### <a name="policy-setting-for-connected-experiences-that-download-online-content"></a>Thiết đặt chính sách cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến

Đây là trải nghiệm giúp bạn tìm kiếm và tải xuống nội dung trực tuyến, bao gồm các mẫu, hình ảnh, mô hình 3D, video và các tài liệu tham khảo để cải thiện tài liệu của bạn. Ví dụ: mẫu Office hoặc Trình Bắt đầu Nhanh PowerPoint. Để biết danh sách về các trải nghiệm được kết nối này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tải xuống nội dung trực tuyến trong Office* để kiểm soát xem các loại trải nghiệm được kết nối này có khả dụng cho người dùng của bạn hay không. Nếu bạn không cấu hình các cài đặt chính sách này, những trải nghiệm được kết nối này sẽ có sẵn cho người dùng của bạn.

Lưu ý rằng nếu bạn vô hiệu hóa thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối trong Office*, các trải nghiệm được kết nối tải xuống nội dung trực tuyến sẽ không có sẵn cho người dùng của bạn.

### <a name="policy-setting-for-optional-connected-experiences"></a>Thiết đặt chính sách cho các trải nghiệm được kết nối tuỳ chọn

Ngoài các trải nghiệm được kết nối được đề cập ở trên có mặt trong Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn, còn có một số trải nghiệm được kết nối tùy ý mà bạn có thể chọn để cho phép người dùng truy cập bằng tài khoản tổ chức. Ví dụ: các tính năng LinkedIn của Trợ lý Sơ yếu lý lịch trong Word hoặc các tính năng bản đồ 3D trong Excel mà sử dụng Bing. Để biết thêm về các ví dụ, hãy xem mục [Tổng quan về trải nghiệm được kết nối tuỳ chọn trong Office](optional-connected-experiences.md).

Các trải nghiệm được kết nối này là khác nhau vì chúng không nằm trong thỏa thuận thương mại của tổ chức của bạn với Microsoft. Các trải nghiệm được kết nối tùy chọn do Microsoft cung cấp trực tiếp cho người dùng của bạn và chịu sự điều chỉnh của [Thỏa thuận Dịch vụ của Microsoft](https://www.microsoft.com/servicesagreement) thay vì [Điều khoản Dịch vụ Trực tuyến](https://www.microsoft.com/licensing/product-licensing/products). Trong một số trường hợp, nội dung hoặc chức năng của bên thứ ba được cung cấp thông qua các trải nghiệm được kết nối tùy chọn này và các điều khoản khác cũng có thể được áp dụng. Để biết thêm thông tin, hãy xem mục [Tổng quan về trải nghiệm được kết nối tuỳ chọn trong Office](optional-connected-experiences.md).

Bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office* để kiểm soát xem các loại trải nghiệm được kết nối này có khả dụng cho người dùng của bạn hay không. Nếu bạn không cấu hình các cài đặt chính sách này, những trải nghiệm được kết nối tuỳ chọn này sẽ có sẵn cho người dùng của bạn.

> [!NOTE]
> Bạn cũng có thể đặt cấu hình cho cài đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office* để áp dụng cho các ứng dụng Office dành cho web sau đây:
> - Excel dành cho web
> - OneNote dành cho web
> - PowerPoint dành cho web
> - Visio dành cho web
> - Word dành cho web
>
> Để đặt cấu hình thiết đặt chính sách này cho các ứng dụng Office dành cho web, bạn cần sử dụng [dịch vụ chính sách trên nền điện toán đám mây Office](../overview-office-cloud-policy-service.md).

Ngay cả khi bạn chọn cung cấp các trải nghiệm được kết nối tuỳ chọn này cho người dùng của mình, họ vẫn sẽ có tùy chọn tắt các trải nghiệm này đi với tư cách một nhóm bằng cách đi tới [hộp thoại cài đặt quyền riêng tư](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Người dùng của bạn sẽ chỉ có lựa chọn này nếu họ đăng nhập vào Office bằng thông tin đăng nhập tổ chức của họ (đôi khi được gọi là tài khoản cơ quan hoặc trường học), chứ không phải nếu họ đăng nhập bằng địa chỉ email cá nhân.

Ngoài ra, một số trải nghiệm được kết nối tùy chọn này cũng được coi là trải nghiệm được kết nối phân tích nội dung hoặc tải xuống nội dung trực tuyến. Ví dụ: Chèn ảnh trực tuyến là một trải nghiệm được kết nối tùy chọn, được cung cấp bởi Microsoft Bing, nhưng nó cũng được coi là một trải nghiệm được kết nối tải xuống nội dung trực tuyến. Lưu ý rằng nếu bạn vô hiệu hóa thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tải xuống nội dung trực tuyến trong Office*, tính năng Chèn ảnh trực tuyến sẽ không có sẵn cho người dùng của bạn. Tính năng này sẽ không có sẵn ngay cả khi bạn đã bật thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office*. Để biết thêm thông tin về trải nghiệm được kết nối phân tích nội dung hoặc tải xuống nội dung trực tuyến, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Có một ngoại lệ cần lưu ý. Thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office* không kiểm soát các trải nghiệm yêu cầu bạn kết nối tài khoản LinkedIn với tài khoản cơ quan hoặc trường học Microsoft của bạn. Để kiểm soát các loại trải nghiệm này, chẳng hạn như thông tin LinkedIn trên [thẻ hồ sơ](https://support.office.com/article/365-e80f931f-5fc4-4a59-ba6e-c1e35a85b501) trong Outlook, hãy xem mục [Kết nối tài khoản LinkedIn và Microsoft của bạn](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381) và [Đồng ý kết nối tài khoản LinkedIn với Azure Active Directory tổ chức](https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration).

### <a name="policy-setting-for-most-connected-experiences"></a>Thiết đặt chính sách cho hầu hết các trải nghiệm được kết nối

Bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối trong Office* để kiểm soát xem người dùng của bạn có thể sử dụng hầu hết các trải nghiệm được kết nối và truy cập thông qua Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn hay không. Nếu bạn tắt thiết đặt chính sách, các loại trải nghiệm được kết nối sau đây sẽ không có sẵn cho người dùng của bạn:

- Trải nghiệm phân tích nội dung của bạn
- Trải nghiệm tải xuống nội dung trực tuyến
- Trải nghiệm được kết nối tuỳ chọn

Ngoài ra, nếu bạn tắt cài đặt chính sách này, hầu hết các trải nghiệm được kết nối khác cũng sẽ bị tắt, chẳng hạn như đồng tác giả và lưu trữ tệp trực tuyến. Để biết danh sách về các trải nghiệm được kết nối khác này, hãy xem mục [Trải nghiệm được kết nối trong Office](connected-experiences.md).

Nhưng ngay cả khi bạn tắt thiết đặt chính sách này, chức năng Office bị giới hạn sẽ vẫn khả dụng, chẳng hạn như đồng bộ hóa hộp thư trong Outlook và Teams và Skype for Business sẽ tiếp tục hoạt động. [Các dịch vụ cần thiết](essential-services.md), chẳng hạn như dịch vụ cấp phép xác nhận rằng bạn đã được cấp phép sử dụng Office đúng cách, cũng sẽ vẫn khả dụng.

## <a name="existing-policy-settings-that-are-replaced-by-new-policy-settings"></a>Các thiết đặt chính sách hiện tại được thay thế bằng các thiết đặt chính sách mới

Có hai thiết đặt chính sách hiện tại không còn áp dụng được cho Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn, bắt đầu từ Phiên bản 1904. Các thiết đặt chính sách đó bao gồm:

- **Gửi thông tin cá nhân**, có thể tìm thấy trong Chính sách người dùng \\Chính sách\\Mẫu quản trị\\Microsoft Office 2016\\Quyền riêng tư\\Trung tâm Tin cậy.

- **Tùy chọn nội dung trực tuyến** có thể được tìm thấy bên dưới Cấu hình người dùng\\Chính sách\\Mẫu quản trị\\Microsoft Office 2016\\Công cụ | Tuỳ chọn | Chung | Tuỳ chọn dịch vụ...\\Nội dung trực tuyến.

Bắt đầu từ Phiên bản 1904, việc cấu hình hai thiết đặt chính sách hiện tại này sẽ không có hiệu lực đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn. Chúng không còn được áp dụng vì chức năng của chúng được thay thế bởi các thiết đặt chính sách mới sau:

- Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office
- Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office
- Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office
- Cho phép sử dụng các trải nghiệm được kết nối trong Office

Các thiết đặt chính sách mới này có thể cung cấp cho bạn quyền kiểm soát với mức độ tốt hơn hai cài đặt chính sách hiện có. Ví dụ: trước đây nếu bạn đã sử dụng thiết đặt chính sách *Gửi thông tin cá nhân*, cả Trình bắt đầu nhanh PowerPoint và Tra cứu thông minh sẽ bị tắt. Nhưng hiện tại, với các thiết đặt chính sách mới, nếu bạn sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối phân tích nội dung trong Office* để tắt loại trải nghiệm được kết nối đó, thì chỉ có Tra cứu thông minh được tắt. Trình bắt đầu nhanh PowerPoint vẫn sẽ sẵn dùng cho người dùng của bạn.

Thiết đặt chính sách vẫn xuất hiện trong công cụ Quản lý chính sách nhóm vì chúng vẫn có thể áp dụng cho các phiên bản Office 2016 và Office 2019 được cấp phép số lượng lớn, chẳng hạn như Office Professional Plus 2019.

## <a name="what-about-existing-policy-settings-that-control-connected-experiences"></a>Thế còn các thiết đặt chính sách hiện có kiểm soát các trải nghiệm được kết nối thì sao?

Như bạn có thể đã biết, có một số thiết đặt chính sách hiện có cho phép bạn kiểm soát các trải nghiệm được kết nối. Dưới đây là một vài ví dụ về thiết đặt chính sách hiện có:

- *Tùy chọn PowerPoint Designer* bên dưới Cấu hình người dùng\\Chính sách\\Mẫu quản trị\\Microsoft Office 2016\\Công cụ | Tuỳ chọn | Chung | Tuỳ chọn dịch vụ...\\PowerPoint Designer

- *Tắt Trình bắt đầu nhanh*, bên dưới Cấu hình người dùng\\Chính sách\\Mẫu quản trị\\Microsoft PowerPoint 2016\\Tuỳ chọn PowerPoint\\Chung

- *Cho phép tính năng Trợ lý Sơ yếu lý lịch LinkedIn*, bên dưới Cấu hình người dùng\\Chính sách\\Mẫu quản trị\\Microsoft Word 2016\\Tuỳ chọn Word\\Chung

 Bạn vẫn có thể sử dụng các thiết đặt chính sách hiện có này nếu bạn muốn tắt các trải nghiệm được kết nối riêng lẻ. Nhưng hãy nhớ rằng nếu bạn sử dụng một trong các thiết đặt chính sách mới, thiết đặt chính sách mới đó có thể tắt trải nghiệm được kết nối mà bạn đã bật bằng cách sử dụng thiết đặt chính sách khác. Ví dụ: nếu bạn bật thiết đặt chính sách *Cho phép tính năng Trợ lý Sơ yếu lý lịch LinkedIn*, nhưng tắt thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối trong Office*, Trợ lý Sơ yếu lý lịch LinkedIn sẽ không có sẵn cho người dùng của bạn.

Nói chung, nếu một cài đặt chính sách được cấu hình để bật trải nghiệm được kết nối cụ thể đồng thời thiết đặt chính sách khác được cấu hình để tắt loại trải nghiệm được kết nối đó, thì trải nghiệm được kết nối cụ thể đó sẽ bị tắt cho người dùng của bạn.

## <a name="privacy-related-changes-to-the-office-ui"></a>Thay đổi liên quan đến quyền riêng tư đối với giao diện người dùng Office

Có một số thay đổi đối với giao diện người dùng (UI) của Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn liên quan đến quyền riêng tư mà người dùng của bạn có thể nhận thấy và thắc mắc. Những thay đổi này là kết quả trực tiếp của các kiểm soát quyền riêng tư và thiết đặt chính sách mới có sẵn bắt đầu từ Phiên bản 1904.

### <a name="dialog-about-optional-connected-experiences"></a>Hộp thoại về trải nghiệm được kết nối tùy chọn

Nếu bạn đã chọn cung cấp cho người dùng của mình [các trải nghiệm kết nối tùy chọn](optional-connected-experiences.md), lần đầu tiên người dùng của bạn mở ứng dụng Office sau khi họ được cập nhật lên Phiên bản 1904 trở lên, một hộp thoại thông tin sẽ xuất hiện. Hộp thoại này thông báo cho người dùng của bạn rằng bạn đã cho họ lựa chọn sử dụng các trải nghiệm được kết nối tùy chọn này và cho họ biết rằng họ có thể đi đến **Tệp** > **Tài khoản** > **Quyền riêng tư tài khoản** để thay đổi thiết đặt này.

### <a name="privacy-settings-removed-from-the-office-ui"></a>Thiết đặt quyền riêng tư bị xóa khỏi Giao diện người dùng Office

Các thiết đặt sau bị loại bỏ khỏi **Tệp** > **Tuỳ chọn** > **Trung tâm Tin cậy** > **Thiết đặt Trung tâm Tin cậy…** > **Tùy chọn Quyền riêng tư**:

- Nhận thiết kế, thông tin, đề xuất và dịch vụ bằng cách cho phép Office truy cập và cải tiến sản phẩm dựa trên nội dung Office trên thiết bị của tôi.

- Cho phép Office kết nối với các dịch vụ trực tuyến của Microsoft để cung cấp chức năng phù hợp với việc sử dụng và sở thích của bạn.

Ngoài ra, Ngoài ra, bên dưới **Tệp** > **Tuỳ chọn** > **Chung**, lựa chọn kích hoạt các dịch vụ thông minh của Office sẽ bị xóa.

Là người quản trị cho tổ chức của bạn, giờ đây bạn sẽ kiểm soát các thiết đặt tương đương với các thiết đặt này thông qua các thiết đặt chính sách mới được mô tả trước đó.

### <a name="privacy-settings-added-to-the-office-ui"></a>Thiết đặt quyền riêng tư được thêm vào giao diện người dùng Office

Sau đây là thành phần mới được thêm vào giao diện người dùng Office:

- Bên dưới **Tệp** > **Tài khoản**, người dùng sẽ thấy một sự lựa chọn mới cho **Quyền riêng tư tài khoản** > **Quản lý thiết đặt**. Lựa chọn đó nằm trong phần **Quản lý thiết đặt** nơi người dùng có thể tắt các trải nghiệm được kết nối tùy chọn, nếu bạn đã cung cấp cho họ tùy chọn đó.

- Bên dưới **Tệp** > **Tuỳ chọn** > **Trung tâm Tin cậy** > **Thiết đặt Trung tâm Tin cậy…** > **Tuỳ chọn quyền riêng tư**, có một tùy chọn để cho phép sử dụng [Trình xem dữ liệu chẩn đoán](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855) trên thiết bị.

 
## <a name="control-privacy-settings-by-editing-the-registry"></a>Kiểm soát cài đặt quyền riêng tư bằng cách chỉnh sửa sổ đăng ký

Một số người quản trị muốn thay đổi các thiết đặt trực tiếp trong sổ đăng ký, ví dụ: bằng cách sử dụng tập lệnh, thay vì sử dụng Chính sách nhóm hoặc dịch vụ chính sách đám mây Office. Bạn có thể sử dụng thông tin sau đây để đặt cấu hình cài đặt quyền riêng tư trực tiếp trong sổ đăng ký.


|**Thiết đặt chính sách** |**Thiết đặt sổ đăng ký**  |**Giá trị**  |
|---------|---------|---------|---------|
|Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft  | Gửi_phép_đo_từ_xa |1=Bắt buộc <br/> 2=Tuỳ chọn <br/> 3=Không có lựa chọn nào|
|Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office  | Nội_dung_người_dùng_đã_bị_tắt | 1=Đã bật <br/> 2=Đã tắt|
|Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office  | Nội_dung_tải_xuống_đã_bị_tắt | 1=Đã bật <br/> 2=Đã tắt|
|Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office   | Dịch_vụ_được_kết_nối_kiểm_soát_đã_được_bật  |1=Đã bật <br/> 2=Đã tắt|
|Cho phép sử dụng các trải nghiệm được kết nối trong Office | Trạng_thái_ngắt_kết_nối  | 1=Đã bật <br/> 2=Đã tắt|

Để tạo tệp .reg cho cài đặt quyền riêng tư, hãy mở Notepad và sao chép vào các dòng sau. Điều chỉnh các giá trị cho phù hợp với nhu cầu của bạn, rồi lưu tệp. Hãy đảm bảo rằng tên tệp có phần mở rộng là .reg

```console
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\16.0\common\privacy]
"disconnectedstate"=dword:00000001
"usercontentdisabled"=dword:00000001
"downloadcontentdisabled"=dword:00000001
"controllerconnectedservicesenabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\common\clienttelemetry]
"sendtelemetry"=dword:00000002
```

Ví dụ: bạn có thể sử dụng tệp .reg này bằng lệnh regedit.exe trong tập lệnh để đặt cấu hình cài đặt quyền riêng tư cho người dùng.