---
title: Dữ liệu dịch vụ bắt buộc cho Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office cái nhìn tổng quan về dữ liệu dịch vụ bắt buộc được thu thập về các trải nghiệm được kết nối trong Office.
hideEdit: true
ms.openlocfilehash: 88f8aadc098af6e167206486566e32af1767c741
ms.sourcegitcommit: 894a18676566981183dbe2d78f7466c9bb2c6354
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/29/2019
ms.locfileid: "33468571"
---
# <a name="required-service-data-for-office"></a>Dữ liệu dịch vụ bắt buộc cho Office 

> [!IMPORTANT]
> Thông tin trong bài viết này áp dụng cho Phiên bản 1904 trở lên của phần mềm máy khách Office sau được cài đặt trên máy tính chạy Windows:
> - Office 365 Business và Office 365 ProPlus.
> - Office 365 Personal, Office 365 Home hoặc các phiên bản Office khác là một phần của đăng ký Office 365.
> - Project và Visio đi kèm với một số gói đăng ký, chẳng hạn như gói Project Online Professional hoặc Visio Online Plan 2.

Office bao gồm các ứng dụng phần mềm máy khách và các trải nghiệm được kết nối được thiết kế để cho phép bạn tạo, giao tiếp và cộng tác hiệu quả hơn. Làm việc với những người khác trên một tài liệu được lưu trữ trên OneDrive for Business hoặc dịch nội dung của tài liệu Word sang một ngôn ngữ khác là những ví dụ về trải nghiệm được kết nối.

Dữ liệu dịch vụ bắt buộc là dữ liệu cho phép chúng tôi cung cấp các trải nghiệm được kết nối dựa trên đám mây này và giúp làm cho các trải nghiệm này trở nên an toàn và hoạt động như mong đợi dành cho các khách hàng của chúng tôi. Dữ liệu dịch vụ bắt buộc gồm ba loại thông tin sau:

- **Nội dung khách hàng** là nội dung bạn tạo bằng cách sử dụng Office, chẳng hạn như văn bản đã được nhập trong tài liệu Word và được sử dụng kết hợp với trải nghiệm được kết nối.
- **Dữ liệu chức năng** bao gồm thông tin mà trải nghiệm được kết nối cần để thực hiện nhiệm vụ của mình, chẳng hạn như thông tin cấu hình về ứng dụng.
- **Dữ liệu chẩn đoán dịch vụ** là dữ liệu cần thiết để giữ an toàn cho dịch vụ, cập nhật và hoạt động như mong đợi. Vì dữ liệu này liên quan chặt chẽ đến trải nghiệm được kết nối, nên nó tách biệt với các mức độ dữ liệu chẩn đoán bắt buộc hoặc tùy chọn.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Ví dụ về dữ liệu dịch vụ bắt buộc cho trải nghiệm được kết nối

Để giúp bạn hiểu về dữ liệu dịch vụ bắt buộc, sau đây là một kịch bản ví dụ, sử dụng PowerPoint Designer - một trải nghiệm được kết nối mà bạn có thể sử dụng khi tạo các trang chiếu cho bản trình bày. PowerPoint Designer giúp cải thiện các trang chiếu của bạn bằng cách tự động tạo các ý tưởng thiết kế mà bạn có thể chọn. Khi bạn dự định đưa nội dung vào một trang chiếu, Trình thiết kế sẽ hoạt động trong nền để khớp nội dung đó với các bố trí được thiết kế chuyên nghiệp.

Dữ liệu dịch vụ bắt buộc được gửi tới Microsoft để cho phép những trải nghiệm được kết nối dành cho bạn này có thể bao gồm các thông tin sau:

- *Nội dung khách hàng*, chẳng hạn như văn bản hoặc hình ảnh mà bạn đã thêm vào trang chiếu của mình.
- *Dữ liệu chức năng*, chẳng hạn như trang chiếu mà bạn đang làm việc và bố trí.
- *Dữ liệu chẩn đoán dịch vụ*, chẳng hạn như các sự kiện cho chúng tôi biết nếu ý tưởng thiết kế được áp dụng chính xác trang chiếu của bạn và các cuộc gọi dịch vụ đang thực hiện một cách chính xác.

## <a name="view-and-manage-required-service-data"></a>Xem và quản lý dữ liệu dịch vụ bắt buộc

Bạn có thể xem dữ liệu chẩn đoán dịch vụ bằng cách sử dụng Trình xem dữ liệu chẩn đoán. Để biết thêm thông tin, hãy xem mục [Ví dụ về các sự kiện dành cho dữ liệu chẩn đoán dịch vụ](#examples-of-events-for-service-diagnostic-data).

Chúng tôi tạo điều kiện để bạn có thể lựa chọn loại trải nghiệm được kết nối mà bạn muốn sử dụng trong Office, từ đó xác định loại dữ liệu dịch vụ bắt buộc nào sẽ được gửi cho chúng tôi. Ví dụ, PowerPoint Designer là một trong một số trải nghiệm được kết nối sẽ phân tích nội dung của bạn. Nếu bạn chọn tắt trải nghiệm được kết nối có phân tích nội dung, sẽ không có dữ liệu dịch vụ bắt buộc nào về PowerPoint Designer được gửi cho chúng tôi vì tính năng này không được kích hoạt trong PowerPoint Designer.

Dữ liệu dịch vụ bắt buộc cũng được thu thập và gửi tới Microsoft để hỗ trợ các dịch vụ thiết yếu của Office, chẳng hạn như dịch vụ cấp phép để xác nhận rằng bạn được cấp phép sử dụng Office đúng theo quy trình. Dữ liệu này dành cho các dịch vụ thiết yếu được gửi bất kể các thiết đặt liên quan đến quyền riêng tư khác mà bạn đã cấu hình.

Để biết thêm thông tin, hãy xem các nguồn sau:

- [Các trải nghiệm kết nối trong Office](connected-experiences.md)
- [Các dịch vụ cần thiết cho Office](essential-services.md)
- [Sử dụng Trình xem chẩn đoán dữ liệu với Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Nếu bạn là người quản trị cho tổ chức của bạn, bạn cũng có thể quan tâm đến những điều sau:

- [Tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)

## <a name="examples-of-events-for-service-diagnostic-data"></a>Ví dụ về các sự kiện dành cho dữ liệu chẩn đoán dịch vụ.

Dữ liệu chẩn đoán dịch vụ xuất hiện trong Trình xem dữ liệu chẩn đoán và được sắp xếp thành các danh mục cần sử dụng và sử dụng dữ liệu chẩn đoán tùy chọn. Ví dụ: *Sử dụng sản phẩm và dịch vụ* hoặc *Hiệu suất sản phẩm và dịch vụ.*

Các sự kiện dành cho dữ liệu chẩn đoán dịch vụ cung cấp cho chúng tôi thông tin cần thiết về việc liệu trải nghiệm được kết nối có hoạt động như khách hàng mong đợi hay không. Ví dụ: liệu dịch vụ được sử dụng bởi trải nghiệm được kết nối có khởi động thành công và có sẵn khi cần hay không, liệu có xảy ra lỗi hoặc sự cố không mong muốn khác (sự cố) khi tương tác với dịch vụ và khả năng đáp ứng hoặc hiệu suất của dịch vụ.

Bảng sau đây cung cấp một số ví dụ về các sự kiện dành cho dữ liệu chẩn đoán dịch vụ.

| **Name**      | **Mô tả**    |
| ---------- | --------------------- |
| Office.Excel.Coauth.SaveXrr     | Một sự kiện được kích hoạt trong Excel khi sử dụng dịch vụ cộng tác sẽ báo cáo chi tiết về các bản hiệu đính riêng lẻ được ghi vào nhật ký hiệu đính. Điều này cung cấp khả năng giám sát độ trễ và chỉ ra các lỗi trong Excel có liên quan đến sự cộng tác  |
| Office.Excel.Coauth.CloseWorkbook  | Một sự kiện được kích hoạt trong Excel khi sử dụng dịch vụ cộng tác sẽ báo cáo khi sổ làm việc đã được đóng. Điều này là cần thiết trong việc xác định các lỗi khi tải lại và tự động làm mới. Sự kiện này cung cấp sự đo lường mức độ thành công cho các hoạt động dịch vụ cộng tác.   |
| Office.Security.OCX.NonTrustedEncounter    | Một sự kiện được kích hoạt trong các ứng dụng Office (bao gồm Word, Excel, Outlook, PowerPoint và Visio) khi người dùng mở một tài liệu không đáng tin cậy bằng điều khiển ActiveX. Sự kiện này được sử dụng để đánh giá rộng rãi việc sử dụng các điều khiển ActiveX được nhúng trong tài liệu Office và để giảm thiểu bảo mật nhằm đối phó với các sự cố bảo mật.  |
| Office.Security.UrlReputation.GetUrlReputation | Một sự kiện được kích hoạt trong các ứng dụng Office (bao gồm Word, Excel, PowerPoint, Visio và Publisher) theo dõi sự thành công hay thất bại của các cuộc gọi Liên kết an toàn. Sự kiện này được sử dụng để đảm bảo rằng dịch vụ Liên kết an toàn hoạt động tốt và chẩn đoán được mọi sự cố.  |
| Office.Voice.VoiceManager.StreamingAudio   | Một sự kiện được kích hoạt trong các ứng dụng Office (bao gồm Word, Outlook và PowerPoint) cung cấp thông tin về trạng thái của âm thanh truyền đến dịch vụ giọng nói. Sự kiện này chứa thông tin về kích thước của âm thanh được truyền và bất kỳ lỗi nào có thể xảy ra. Thông tin này được sử dụng để theo dõi trạng thái dịch vụ và để chẩn đoán bất kỳ sự cố nào có thể được khách hàng báo cáo. |
